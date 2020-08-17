## Visual story telling part 1: green buildings

Her on-staff considered removing a few buildings with very low occupancy rates, which I think makes sense. The floors in the data range from 1 to 110 floors, and floors have a certain impact on rent. In order to reduce this impact, I chose the data of 10 to 30 floors for analysis.


 Building quality is divided into 3 categories in total, and the rents corresponding to these three types of buildings are calculated separately. Class A buildings are generally the highest-quality properties in a given market. The median market rent in the non-green buildings was $\$$28.00 per square foot per year, while the median market rent in the green buildings was $\$$29.79 per square foot per year: about $1.79 more per square foot. It is estimated that these costs can be recovered in 5000000/(250000*1.79)=11.2 years.

 Class B buildings are a notch down, but still of reasonable quality. The median market rent in the non-green buildings was $\$$25.44 per square foot per year, while the median market rent in the green buildings was $\$$21.37 per square foot per year. On the contrary, the rent of the building is relatively low, and the construction of green buildings will not obtain additional benefits.

 Class C buildings are the least desirable properties in a given market.The median market rent in the non-green buildings was $\$$22.5 per square foot per year, while the median market rent in the green buildings was $\$$28.9 per square foot per year: about $6.4 more per square foot. It is estimated that these costs can be recovered in 5000000/(250000*6.4)=3.1 years.


So for Class A or Class C buildings,building a green building seems like a good financial move to build the green building.But it is not suitable for Class B.

## Visual story telling part 2: flights at ABIA

Austin-Bergstrom Interational Airport is in Texas, the United States. The three airports with the most flights into and out of Austin are DAL, DFW, and IAH. It can be seen from the figure that these four airports are in Texas State


## Portfolio modeling

- Government Bonds ETFs offer investors exposure to fixed income securities issued by government agencies. Bonds featured in these ETFs include U.S. Treasuries of varying maturities, floating rate Treasury bonds, and TIPS.Select 5 ETFs from Government Bonds ETFs for analysis as follows.

- China equities ETFs are funds that invest in China-based corporations. The funds in this category include index funds as well as category specific funds.Choose 5 ETFs from China equities ETFs for analysis as follows.

- Choose 3 ETFs from Government Bonds ETFs and 2 ETFs from China equities ETFs. Together, construct the investment portfolio as follows.

From the above results, it can be seen that the risk of Bonds is relatively small, and the VaR value of the portfolio is -1889.072. Equities risk is relatively large first, and the VaR value of the constituted portfolio is -11344.47. The VaR value of the portfolio composed of Bonds and equity is -3635.952, and the risk is also in the middle of the three.


## Market segmentation


 The sharp decreases from one to three clusters (with little decrease after) suggests a three-cluster solution.
 
It can be seen from the results that the first group of family, food, music scores are the highest, the second group of religion, food scores are the highest, and the third group of chatter, photo_sharing scores are the highest.

## Author attribution

Read the files in the C50train directory as training set data, read the files in the C50test directory as test set data. Then preprocess the text content, convert it to doc-term-matrix, then use the random forest algorithm to build a model, and then Test the data set for prediction.

## Association rule mining

Importing the required libraries

Getting the data and preprocessing it.We can read each row of data in a loop, and then use strsplit to convert each row of data into a vector, and all rows of data are formed into a list object. Then use the as method to convert to transactions object.

Package arules provides a more concise way, using the read.transactions method to directly convert the file into the required transaction format.

The following graphic shows the 10 items with the highest frequency.

Below we use the apriori method, the default setting of the method is: (1) supp = 0.1, which is the minimum support for the rule; (2) conf = 0.8, which is the minimum confidence of the rule; (3) maxlen = 10, This is the maximum length of the rule. It can be seen from the results that no association rules have been filtered out.

It can be seen from the results that white bread and ham have the highest correlation.

It can be seen from the results that bottled beer, red/blush wine and liquor have the highest correlation.