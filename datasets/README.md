There are three custom datasets that are included here. Each pickle file holds a pandas dataframe. The data inside each file is a filtered & customized version of the original datasets. The data has been filtered so that effective stacked bar charts can be created easily.

Below are the datasets that were used for this problem. 

1. **Time Usage Survey Dataset:**
This is the baseline dataset used for this dataset. It has 5 categories and 16 bars on the baseline design. The original dataset comes from the following website (https://timeuse.ipums.org/). This data has been filtered to only show number of people in each family income group. The people are split into categories (races).

2. **Cereal Dataset:**
This is a simpler dataset to see if the design can work on an already easy to scale down design. This design should be easier to scale down because there are multiple bars with zero height (no values in them). Thus, these areas should be compressed easily. It has 20 bars and 7 categories. The one complexity in this dataset is the number of categories is still large. This dataset allows us to see if the use of color is properly scaled down and not only focus on the number of bars. The dataset comes from a Kaggle set (https://www.kaggle.com/crawford/80-cereals). The data is filtered to show the rating for different cereals. The cereals are split into categories (by manufacturer). 

3. **Museums Dataset:**
This is more complicated dataset to work with. There are 20 bars and 9 categories. Additionally, the distribution of data is bimodal and harder to scale down. This dataset should let us see how our problem works with more complicated problems. The dataset comes from kaggle here (https://www.kaggle.com/imls/museum-directory). The data is filtered to show the revenue of different museums. The museums are split into categories (type of museum). 
