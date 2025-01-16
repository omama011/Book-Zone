# Book-Zone
This project is a web application built using Flask that provides book recommendations based on user input. It utilizes preprocessed data and similarity scores to suggest books similar to the user's choice. The app also displays a list of popular books with details like author, ratings, and votes.

## Features
- Popular Books Display: Shows a curated list of the top 50 books based on ratings and votes.  
- Personalized Recommendations: Users can input the name of a book and get a list of similar books as recommendations.  
- Book Details: Each recommendation includes the book title, author, and cover image.  

# <small>Setup Instructions</small>
<small>
**Prerequisites**  
- Python 3.7 or higher installed.  
- Required Python libraries: Flask, NumPy, Pandas.  
- Pickle files:  
    - `popular.pkl`: Contains data for the top 50 books.  
    - `pt.pkl`: A pivot table for book similarity.  
    - `books.pkl`: Detailed book information.  
    - `similarity_scores.pkl`: Precomputed similarity scores.
</small>
