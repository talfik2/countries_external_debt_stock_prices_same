# countries_external_debt_stock_prices_same
In this repo, I clustered the countries that have external debt stocks prices tend to change in the same way from 1970 to 2019 according the data from Gapminder.
External debt stock is the portion of a country's debt that was borrowed from foreign lenders including commercial banks, governments or international financial institutions.
Source of data is : https://www.gapminder.org/data/
I used Sklearn's `SimpleImputer` to replacing Na values.
Detected how many clusters do I need for the best practice by DataCamp's custom function. (https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=6)
Crosstabulated data for better understanding
Preprocessed data with sklearns `Normalizer`
Applied `KMeans` with `n_clusters=3`
And joined these two steps with sklearn.pipeline's `make_pipeline`
