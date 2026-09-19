# Movie Recommendation System

A simple **content-based movie recommendation system** built with Python and the TMDB 5000 Movie Dataset.

The system recommends movies based on their **genres, keywords, top 3 cast members, director, and plot overview** using **TF-IDF vectorization** and **cosine similarity**.

## Features

- Content-based movie recommendations
    
- TF-IDF feature extraction
    
- Cosine similarity for finding similar movies
    
- Uses genres, keywords, cast, director, and overview
    
- Weighted feature model for improved recommendations
    
- Top 10 recommendations with similarity scores
    
- Basic dataset analysis and visualizations
    
- Interactive movie search within the notebook
## Tech Stack

- Python
    
- Jupyter Notebook
    
- Pandas
    
- NumPy
    
- Scikit-learn
    
- Seaborn
## Dataset

This project uses:

- **TMDB 5000 Movies Dataset**
    
- **TMDB 5000 Credits Dataset**

The original CSV datasets are not included in the `data/` folder because of GitHub's file size limitations.

Dataset download links are provided in:

```text
data/dataset_links.txt
```

Download both datasets and place the CSV files inside the `data/` directory.

## Project Structure

```text
movie-recommendation/
│
├── data/
│   └── dataset_links.txt
│
├── movie_recommendation.ipynb
│
└── README.md
```

## Running Locally

1. Clone the repository.
    
2. Download both datasets using the links in `data/dataset_links.txt`.
    
3. Place the downloaded CSV files in the `data/` folder.
    
4. Open `movie_recommendation.ipynb` using Jupyter Notebook or JupyterLab.
    
5. Run the cells in order.
    
6. Use the interactive recommendation section to enter a movie title.

## How It Works

```text
Movie Metadata
      ↓
Data Preprocessing
      ↓
Feature Extraction
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Top 10 Similar Movies
```

The project uses **content-based filtering**, so recommendations are generated from movie metadata rather than user-rating history.

## Future Improvements

- Web-based interface
    
- Personalized recommendations using user ratings
    
- Collaborative filtering
