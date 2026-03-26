# movie-recommendation
This project implements a **Content-Based Movie Recommendation System** using Python and machine learning techniques. The system analyzes various attributes of movies and recommends similar movies based on user input.
It leverages natural language processing (NLP) techniques to compute similarity between movies and provide personalized recommendations.
## Objectives
* To build a recommendation system using content-based filtering
* To process and analyze movie metadata
* To generate accurate movie suggestions based on similarity
## Tech Stack
* **Programming Language:** Python
* **Libraries & Tools:**
  * Pandas
  * NumPy
  * Scikit-learn
  * Difflib
* **Environment:** Jupyter Notebook / Google Colab
## Dataset
The dataset (`movies.csv`) contains structured information about movies, including:
* Title
* Genres
* Keywords
* Tagline
* Cast
* Director
## Methodology
### Data Preprocessing
* Selected relevant features: genres, keywords, tagline, cast, and director
* Handled missing values by replacing them with empty strings
Feature Engineering
* Combined selected features into a single textual representation
* Applied **TF-IDF Vectorization** to convert text into numerical form
Similarity Computation
* Used **Cosine Similarity** to measure the similarity between movies
###  Recommendation Logic
* Accepts user input (movie name)
* Uses fuzzy matching (`difflib`) to find the closest match
* Returns a list of top recommended movie
##Execution Steps
1. Install required dependencies:
pip install pandas numpy scikit-learn
2. Open the notebook (`movies.ipynb`) in Jupyter Notebook or Google Colab
3. Run all cells sequentially
4. Provide a movie name when prompted
5. View the recommended movies
## Sample Output
Enter your favourite movie name: Avatar  
Movies suggested for you:  
1. Guardians of the Galaxy  
2. Star Trek  
3. John Carter  
##  Key Features
* Content-based recommendation approach
* Handles approximate user input (spelling variations)
* Efficient similarity computation using vectorization
* Scalable and easy to extend
## Future Enhancements
* Integrate collaborative filtering
* Deploy as a web application (Flask/Streamlit)
* Improve recommendation accuracy using deep learning
* Add user interface for better interactioon
##  Conclusion
The project successfully demonstrates the implementation of a **movie recommendation engine** using content-based filtering techniques. It highlights the practical application of NLP and similarity measures in real-world systems.
