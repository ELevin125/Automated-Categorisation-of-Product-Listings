## Automated Categorisation of Product Listings

### Overview
The main objective of this project was to develop a robust product classification model, that is capable of accurately categorising product description into predefined classes related to the e-commerce domain.

In short, this project will need to accurately assign product descriptions that would be available on a seller's page, to one of these four categories from the identified dataset:
- "Electronics"
- "Household"
- "Books"
- "Clothing & Accessories"

The approach used in this project, was Naïve Bayes with TF-IDF vectorization. As for the input data used, not too much pre-processing was required, aside from removing symbols, stopwords and any blank or missing entries.

---

### Dataset Used
- **Size** - The dataset consists of a collection of 50 425 entries.
- **Data Types / Structure** - The dataset consist of a singular CSV file with two string columns. The file lacks a header row, but based off of the description, the first column contains the class name, and the second column the product description. There are four possible classes that a product can belong to
- **Data Source** - The dataset was accessed via Kaggle at [this link](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification). It was posted by a user "Saurabh Shahane" who based the dataset off of [this dataset](https://zenodo.org/records/3355823) from Zenodo.
