# Coffee Quality Analysis Project

## Overview
This project is dedicated to analyzing the factors affecting coffee quality. Utilizing data from the Coffee Quality Database (CQD), we aim to investigate how different features of coffee batches contribute to the overall quality classification as either good (score >= 82.5) or poor (score < 82.5).

## Data Source
The datasets used in this analysis come from the Coffee Quality Database (CQD), provided by the Coffee Quality Institute, a non-profit organization. The datasets include various attributes related to coffee production and quality assessment.

## Variables
The analysis focuses on the following attributes for each coffee batch:
- `country_of_origin`: The country where the coffee originates.
- `aroma`: Aroma grade of the coffee batch.
- `flavor`: Flavor grade of the coffee batch.
- `acidity`: Acidity grade of the coffee batch.
- `category_two_defects`: Count of category 2 defects in the coffee batch.
- `altitude_mean_meters`: Mean altitude of the grower's farm.
- `harvested`: Harvest year of the coffee batch.
- `Qualityclass`: Quality classification based on the score.

## Methodology
After completing data cleaning, we conducted exploratory data analysis (EDA) and then used generalized linear models (GLM) to analyze the impact of various factors on coffee quality.
The `Qualityclass` serves as the response variable, with a binary outcome indicating whether the quality of coffee is good or poor.


## Repository Structure
- `dataset12.csv`: This directory contains the datasets used in the analysis.
- `/scripts`: This directory contains the R scripts for the GLM analysis.
- `/results`: This directory will store the output of the analyses, including figures and tables.
- `README.md`: Provides an overview and instructions for this repository.

## Getting Started
To run the analysis, follow these steps:
1. Clone this repository to your local machine.
2. Make sure R and the necessary packages (`tidyverse`, `MASS`, etc.) are installed.
3. Run the scripts located in the `/scripts` directory.

## How to Contribute
Contributions to this project are welcome! To contribute, please:
1. Fork the repository.
2. Create a new branch for your feature.
3. Add your feature or enhancement.
4. Submit a pull request.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For any questions or comments, please open an issue in this repository or contact the repository maintainer directly.
