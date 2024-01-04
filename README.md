The dataset provides information about various television models. 
EACH FEATURE TELLS ABOUT:
  -  Brand : The brand name of the television manufacturer (e.g., TOSHIBA, TCL, realme, Mi, SONY).
  -  Resolution : The display resolution of the television (e.g., Ultra HD, QLED Ultra HD, HD).
  -  Size : The size of the television screen in inches.
  -  Selling Price : The current selling price of the television model.
  -  Original Price : The original or list price of the television model before any discounts or promotions.
  -  Operating System : The operating system used by the television (e.g., VIDAA, Android, Linux).
  -  Rating : The rating of the television model, presumably based on user reviews or some other metric.

CONCLUSIONS:
          from descriptive analysis:
          - now there is no missing values
          - there are `59` unique brands and `SAMSUNG` with most frequent brand(140 times) 
          - there are `5` unique display resolutions and `Ultra HD LED`(399) is the most common 
          - The sizes range from a minimum of 17 inches to a maximum of 85 inches, with an average size of approximately 45.94 inches.
          - Selling prices vary widely, with a minimum of 4,849 and a maximum of 499,990.The mean selling price is 59,358.61.
          - Original prices also exhibit a considerable range, from 6,999 to 549,990.
          - There are 7 unique operating systems, with `Android`(485 times) being the most common .
          - Ratings range from a minimum of 2 to a maximum of 5, with an average rating of 4.23.
          
          from univariable analysis:
          - There is a high demand for televisions with `Ultra HD` resolution, indicating a preference for higher picture quality.
          - `SAMSUNG` and `LG` emerge as the leading brands, possibly indicating a high level of consumer trust and market influence.
          - Sharp has the highest average selling price.Samsung, SAMSUNG, and LG are also among the brands with higher average selling prices, suggesting that these brands might have premium or high-end television models.
          - Android is the most prevalent operating system, appearing 485 times in the dataset. This indicates a significant market share and popularity among the analyzed televisions.
          
          from coorelation analysis:
          - There is a moderate positive correlation between the size of the television and its selling price. As the size increases, the selling price tends to increase.
          - There is a strong positive correlation between the size of the television and its original price. Larger televisions tend to have higher original prices.
          - There is a very strong positive correlation between the selling price and the original price. 
          - There is a weak positive correlation between the size of the television and its rating. Larger televisions may have slightly higher ratings, but the correlation is not very strong.
          - There is a weak positive correlation between the selling price and the rating.
          - There is a weak positive correlation between the original price and the rating.
          - There is a very weak positive correlation between the size of the television and the discount percentage.
          - There is a moderate negative correlation between the selling price and the discount percentage. As the selling price increases, the discount percentage tends to decrease.
          - There is a very weak positive correlation between the original price and the discount percentage. 
          - There is a very weak negative correlation between the rating and the discount percentage. 
