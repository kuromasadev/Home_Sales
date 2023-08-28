# Home_Sales
 determine key metrics about home sales data

## Executive Summary

This report presents a comprehensive analysis of home sales data for various criteria. The data was analyzed to extract insights regarding average prices, view ratings, and performance comparisons. Below are the key findings and conclusions:

1. **Average Price for Four-Bedroom Houses by Year:** The average price for a four-bedroom house sold each year was observed as follows:

   | Year | Average Price |
   | ---- | ------------- |
   | 2019 | $300,263.70   |
   | 2020 | $298,353.78   |
   | 2021 | $301,819.44   |
   | 2022 | $296,363.88   |

2. **Average Price of Homes with 3 Bedrooms and 3 Bathrooms:** The average price of homes built each year with 3 bedrooms and 3 bathrooms was analyzed:

   | Year Built | Average Price |
   | ---------- | ------------- |
   | 2010       | $292,859.62   |
   | 2011       | $291,117.47   |
   | 2012       | $293,683.19   |
   | 2013       | $295,962.27   |
   | 2014       | $290,852.27   |
   | 2015       | $288,770.30   |
   | 2016       | $290,555.07   |
   | 2017       | $292,676.79   |

3. **Average Price of Homes with Specific Criteria:** The average price of homes built each year with 3 bedrooms, 3 bathrooms, two floors, and at least 2,000 square feet was analyzed:

   | Year Built | Average Price |
   | ---------- | ------------- |
   | 2010       | $285,010.22   |
   | 2011       | $276,553.81   |
   | 2012       | $307,539.97   |
   | 2013       | $303,676.79   |
   | 2014       | $298,264.72   |
   | 2015       | $297,609.97   |
   | 2016       | $293,965.10   |
   | 2017       | $280,317.58   |

4. **Average "View" Rating for Homes with High Prices:** The average "view" rating for homes with prices greater than or equal to $350,000 was calculated as 32.26, rounded to two decimal places.

## Analysis Runtime

The runtimes for various analyses were compared:

- Cached Runtime: 0.7879 seconds
- Uncached Runtime: 0.4425 seconds
- Parquet Cached Runtime: 0.3760 seconds
- Parquet Uncached Runtime: 1.0986 seconds

The comparison reveals that caching data significantly improves query performance, as demonstrated by the shorter runtime in both the cached and Parquet cached cases. Parquet storage format generally offers improved performance over uncached data due to its optimized columnar storage.
