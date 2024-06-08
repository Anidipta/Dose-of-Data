# **Pokemon Data Analysis**

![Pokemon](https://media.licdn.com/dms/image/D5612AQHcM0VMFJgApQ/article-cover_image-shrink_720_1280/0/1693159389529?e=1723075200&v=beta&t=Zyzi7Gmq52ZgIBws46Fb-1D9rAJLLw1HjktPqWuoRj0)

## **Overview**

The Pokémon dataset encompasses a variety of attributes for each Pokémon, including name, types, base stats, abilities, and more. In this analysis, our objectives are:

- **Conduct Comprehensive Exploratory Data Analysis (EDA)**: Visualize the distributions of Pokémon attributes, uncover patterns, and identify correlations within the data.
- **Develop Predictive Models**: Utilize classification algorithms to accurately categorize Pokémon as legendary or non-legendary based on their attributes.
- **Present Insights Effectively**: Showcase the findings with detailed visualizations, insightful descriptions, and thorough documentation.


## **Dataset**

The Pokémon dataset contains detailed information about various Pokémon species, including their attributes, abilities, and classifications. This document provides an overview of the dataset and its attributes.

<details><summary>Attributes</summary>

|    Field Name                   |   Description                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **abilities**| A list of abilities possessed by each Pokémon.|
| **against_**| Attributes representing the effectiveness of each Pokémon type against other types (e.g., against_bug, against_dark).|
| **attack**| Base attack stat of the Pokémon.|
| **defense**| Base defense stat of the Pokémon.|
| **sp_attack**| Base special attack stat of the Pokémon.|
| **sp_defense**| Base special defense stat of the Pokémon.|
| **speed**| Base speed stat of the Pokémon.|
| **weight_kg**|Weight of the Pokémon in kilograms.|
| **height_m**| Height of the Pokémon in meters.|
| **base_total**| The total base stats of the Pokémon.|
| **capture_rate**| Capture rate of the Pokémon.|
| **classification**| Classification of the Pokémon.|
| **experience_growth**| Experience growth rate of the Pokémon.|
| **generation**| Generation in which the Pokémon was introduced.|
| **is_legendary**| Binary attribute indicating whether the Pokémon is legendary (1) or not (0).|
| **japanese_name**| Japanese name of the Pokémon.|
| **name**| English name of the Pokémon.|
| **percentage_male**| Percentage of male Pokémon in the species.|
 |**pokedex_number**| Pokédex number of the Pokémon.|
| **type1**| Primary type of the Pokémon.|
| **type2**| Secondary type of the Pokémon.|
</details>

## Objectives

1. **Explore the Dataset**: Analyze Pokémon attributes, types, and generations.
2. **Perform EDA**: Visualize distributions and identify correlations.
3. **Build Models**: Develop algorithms to classify Pokémon as legendary or non-legendary.
4. **Analyze Patterns**: Uncover trends and insights in Pokémon data.
5. **Present Findings**: Provide clear visualizations and comprehensive documentation.

## **Contents**

## Methodology

1. **Data Loading**: Load the Pokémon dataset.
2. **Data Cleaning and Wrangling**: Handling missing values, correcting and changing data types, and removing duplicates to ensure data integrity and accuracy.
3. **Exploratory Data Analysis (EDA)**: Visualize distributions, correlations, and patterns in the data using python libraries like matplotlib ,squarify ,and seaborn.
4. **Data Preprocessing**: Normalizing features, encoding categorical variables, and splitting the dataset into training and testing sets for model training.
5. **Predictive Modeling**: Build and evaluate machine learning models using scikit-learn to classify Pokémon as legendary or non-legendary.

## **How to run**

To run the analysis notebook locally, follow these steps:

1. Clone this repository to your local machine.
2. Install Dependencies --> run `pip install -r requirements.txt`.
3. Open the Jupyter Notebook (`pokemon-anidipta.ipynb`).
4. Execute the Code .

## Conclusion

The Pokémon Dataset Analysis project provides deep insights into Pokémon characteristics and classifications. These findings are valuable for enthusiasts, researchers, and anyone interested in data analysis and machine learning.

## Author

| Name                  |
|-----------------------|
| Anidipta Pal |
