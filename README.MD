### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.  

You will also want to download [nltk](https://www.nltk.org/data.html) - directions for this can be found in the text processing portion of the workbook.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from AirBnB homes located in Seattle and Boston.  Specifically, I looked at the following questions:

Question 1: There are several variables(features) which are related to review score such as “review_scores_rating”,”review_scores_accuracy”,”review_scores_cleanliness”,should I put all those variables into the model predicting? and if other variables have the same situation?

Question 2: which features are highly related to “price”?

Question 3: If you change the LinearRegression model to another model,can we have better score? The features which are the most negatively correlation of “price” will change ?

Question 4: In Part 2,I will see the model built in the airbnb in Boston,will the score be better? and which features are highly related to “price”?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `【Part 1】Project 1 Seattle Airbnb.ipynb` - a notebook of the analysis ,mainly focuses on the dataset of Seattle of Airbnb ,performed following the CRISP-DM process, and which is exported into `【Part 1】Project 1 Seattle Airbnb.html`.

* `【Part 2】Project 1 Boston Airbnb.ipynb` - a notebook of the analysis ,mainly focuses on the dataset of Boston of Airbnb ,performed following the CRISP-DM process, and which is exported into `【Part 2】Project 1 Boston Airbnb.html`.

* `calendar_seattle.csv` and `calendar_boston.csv` - csvs containing **home_id**, **date**, **availability**, and **price** for each home

* `listings_seattle.csv` and `listings_boston.csv` - csvs containing **id**, **listing_url**, **scrape_id**, and other columns for each home

* `reviews_seattle.csv` and `reviews_boston.csv` - csvs containing the **home_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.


## Results<a name="results"></a>

The main findings of the code can be found at the [blog post available here](https://medium.com/@happydanil/exploratory-analysis-of-boston-and-seattle-airbnb-data-4cd7a24e061d).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the [Boston data on Kaggle](https://www.kaggle.com/airbnb/boston) and for the [Seattle data](https://www.kaggle.com/airbnb/seattle).
 
