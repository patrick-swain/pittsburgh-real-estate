# pittsburgh-real-estate
An analysis of Pittsburgh real estate sales prices and their determinants.

For Prof. Randall Walsh's MQE course Evidence-Based Analysis in Labor, Public, and Health Economics, I conducted an analysis of a >500k observation dataset from the Western Pennsylvania Regional Data Center on all real estate transactions in the Pittsburgh metropolitan area going back to the 1960s. I aimed to understand which areas in Pittsburgh were the most and least expensive to buy a home and why.

After cleaning the data, adjusting nominal sales prices for inflation, and filtering for residential transactions within the city limits, I analyzed differences between wards, neighborhoods, and ZIP codes based on real sales price per bedroom, lot size, and finished living space. I ran an XGBoost model to predict real sales price with 80% accuracy and found that square footage of finished living space, neighborhood, and home condition were the most influential features. After changing the target variable to real sales price per square foot and omitting size- and location-based features, I found that condition, year built, and exterior finish were among the most influential.
