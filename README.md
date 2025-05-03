# FIFA 21 Data Analysis: Uncovering Hidden Gems and Player Trends

FIFA 21 offers a treasure trove of player data that can reveal fascinating insights about the world's most popular sport. In this analysis, I'll walk through the process of cleaning and transforming raw FIFA 21 data to uncover meaningful patterns and player insights that might not be immediately obvious.

**About the Dataset**
The FIFA 21 dataset is a comprehensive collection of player statistics and attributes from the FIFA 21 video game. This dataset contains information on 18,979 football players with 77 different attributes ranging from basic biographical information to detailed performance metrics.

**Data Cleaning Challenges**
The dataset requires several cleaning operations before it can be effectively analyzed:

    Height and Weight Conversion: The height and weight columns are stored as strings with inconsistent units (e.g., "185cm" or "6'2"" for height, "75kg" or "165lbs" for weight)

    Monetary Values: Financial values like player market value, wage, and release clause are stored as strings with currency symbols and abbreviations (e.g., "€10.5M" for 10.5 million euros)

    Star Ratings: Some columns contain star characters (★) that need to be removed and converted to numerical values

    Newline Characters: Several text fields contain unwanted newline characters that need to be removed

    Date Parsing: The 'Joined' column contains dates that need to be converted to a proper datetime format for calculating player tenure

