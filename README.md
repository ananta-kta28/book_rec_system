# Book-Recommendation-System

## Description:
<p>A Book Recommendation System which recommends the users a selection of books based on their interests.
It also has a separate page for the list of all books.</p>
<p>Data from <a href="https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset">here</a>.</p>

### 1. Data Cleaning and Pre-Processing
The dataset consists of three tables; Books, Users, and Ratings. Data from all three tables are cleaned and preprocessed separately.<br><br>

### 2. Algorithms Implemented:
#### 2.1 Popularity Based Recommendation :

* ##### Popular in the Whole Collection <br>
We have sorted the dataset according to the total ratings each of the books have received in non-increasing order and then recommended top 50 books.

#### 2.2 Content Based Recommendation
This system recommends books by calculating similarities in Book Titles. For this, TF-IDF feature vectors were created for unigrams and bigrams of Book-Titles; only those books' data has been considered which are having at least 50 ratings.

### 3. Libraries Used:

* ipython-notebook
* sklearn
* numpy, scipy
* pandas

### 4. Frontend

* HTML, CSS & Javascript

### 5. Execution
* Install the requirements
* Run the book-recommender-system.ipynb file
* Run app.py

Made by:
Ananta Taneja