# Boston AirBnB analysis Project

## Idea and Design
In this project, we will take a look at the analysis of the Airbnb dataset for Boston and take a look at what story the dataset will tell us. We will do some exploratory data analysis, and some data cleaning, and answer some questions involving

* Top and bottom listings,
* Reviewers and their rankings,
* Reviewer’s general mood to check review reliability,
* The mood around listings, customer satisfaction, and positivity

## Blog post
I wrote a blog to explain the project and the questions we solved in the code, do take a look if it is something you are interested in.
https://medium.com/@anand0427/how-should-you-choose-airbnb-346a869870f2

## Dependencies
* Software dependencies
    - Python
    - Python Environment
    - Jupyter lab
* Library dependencies
    - textblob
    - geopandas
    - plotly
    - matplotlib
    - pandas
    - seaborn

## File Description
* Data Source - Data folder is from [isnideairbnb](http://insideairbnb.com/get-the-data/)
* Data/sentiment_values.csv - Store sentiment analysis results to not slow down the notebook on subsequent runs.
* Notebooks/AirBNB EDA.ipynb - Notebook analysis of Boston AirBnB dataset
Output Images/ - Snips of output plots in the notebook 


## Instructions
1. To run this file you will need to install Anaconda and a few other packages shown above.

    - For example
        `conda install -c conda-forge geopandas`

2. Run the following command in the app's directory to open up the localhost jupyter application.
    `jupyter lab`

3. When the application launches, go to the notebook `AirBNB EDA.ipynb` and run all the cells. 

## Licensing, Authors, and Acknowledgements
This dataset is part of Airbnb Inside, and the original source can be found [here](http://insideairbnb.com/get-the-data/).