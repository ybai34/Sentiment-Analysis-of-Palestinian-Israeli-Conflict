# Data Directory Overview

The `Data` directory houses two CSV files which are subsets of the data collected for this project:

- `data_10k_rows.csv`: This is a larger dataset containing 10,000 rows. It encompasses a comprehensive range of data points suitable for in-depth analysis and model training purposes.

- `data_5k_rows.csv`: A smaller dataset consisting of 5,000 rows. This dataset is ideal for testing, quick experiments, and validation processes due to its reduced size.

It is important to note that the complete dataset is not included within this repository due to its substantial size, which exceeds the upload limits of GitHub.

## Data Collection

All the data present in the above files were meticulously gathered using the `Crawler.ipynb` Jupyter notebook located in the `Code` directory. The script is specifically designed to crawl and collect data from Reddit, a popular social news aggregation and discussion website. The crawler is set up to navigate through the site, access the desired content, and retrieve data in a structured format, which is then saved into CSV files for further use.

For those interested in replicating or extending the dataset, the crawler notebook can be executed with the appropriate configurations to gather more data as needed.

