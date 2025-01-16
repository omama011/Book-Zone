# Book-Zone
This project is a web application built using Flask that provides book recommendations based on user input. It utilizes preprocessed data and similarity scores to suggest books similar to the user's choice. The app also displays a list of popular books with details like author, ratings, and votes.

## Features
- **Popular Books Display**: Shows a curated list of the top 50 books based on ratings and votes.  
- **Personalized Recommendations**: Users can input the name of a book and get a list of similar books as recommendations.  
- **Book Details** : Each recommendation includes the book title, author, and cover image.  

## Setup Instructions
**Prerequisites**  
- Python 3.7 or higher installed.  
- Required Python libraries: Flask, NumPy, Pandas.  
- Pickle files:  
    - `popular.pkl`: Contains data for the top 50 books.  
    - `pt.pkl`: A pivot table for book similarity.  
    - `books.pkl`: Detailed book information.  
    - `similarity_scores.pkl`: Precomputed similarity scores.

Steps to Run the Project Locally
Clone the repository:
```
git clone https://github.com/yourusername/book-recommender-system.git
```
Navigate to the project folder:
```
cd book-recommender-system
```
Install required libraries:
```
pip install -r requirements.txt
```

Run the application:
```
python app.py
```
**Usage**
Homepage:
Browse the top 50 books, along with their ratings and votes.
Recommendations:
Go to the "Recommend" page.
Enter the title of a book in the input field.
Receive a list of books similar to your input, complete with details like title, author, and cover image.
Project Structure
perl
Copy
Edit
book-recommender-system/
│
├── templates/
│   ├── index.html           # Homepage displaying popular books
│   ├── recommend.html       # Recommendation page
│
├── static/                  # Optional folder for static assets like CSS, JS, and images
│
├── app.py                   # Main Flask application
├── popular.pkl              # Data for top 50 books
├── pt.pkl                   # Pivot table for similarity
├── books.pkl                # Detailed book information
├── similarity_scores.pkl    # Precomputed similarity scores
├── requirements.txt         # List of dependencies
└── README.md                # Project documentation