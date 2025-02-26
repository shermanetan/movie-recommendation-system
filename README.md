# Movie Recommendation System

## Project Overview

This project is a movie recommendation system that suggests movies based on textual similarity. It leverages Natural Language Processing (NLP) techniques and machine learning to find similarities between movie descriptions and recommend relevant movies.

## Data Source

**`movies.csv`**: Includes movie descriptions and metadata

## Features

• Text-based movie recommendations using TF-IDF and cosine similarity

• Interactive UI with ipywidgets for user-friendly movie selection

• Efficient similarity calculations powered by scikit-learn

## Approach

#### 1. Data Inspection & Preprocessing
• Load and explore the dataset

• Clean and standardise movie descriptions

• Apply TF-IDF vectorisation to extract meaningful text features

#### 2. Movie Recommendation Model
• Compute similarity scores using cosine similarity

• Implement an interactive UI using ipywidgets for dynamic recommendations

• Optimise performance for efficient search and retrieval

#### 3. Evaluation & Findings
• Assess the relevance of recommendations

• Compare text-based similarity results with alternative recommendation techniques

## Results

The model effectively suggests movies based on text-based similarity. It identifies relevant movies based on descriptions and presents recommendations dynamically. The interactive interface provides an intuitive user experience, allowing users to explore recommendations easily. Overall, the system demonstrates efficiency in similarity calculations and user-friendly interactions.

## Techniques Used

• **Python** (Pandas and NumPy for data manipulation and analysis)

• **Scikit-learn** (TF-IDF vectorisation & similarity calculations)

• **Jupyter Notebook** (for interactive development)

• **IPython Display & Ipywidgets** (for UI components)

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

2. Set up a virtual environment (optional but recommended)

```bash
python -m venv venv source venv/bin/activate``` # On Windows use `venv\Scripts\activate`)
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook

```bash
jupyter notebook
```

5. Open **`movie_rec_system.ipynb`**

   • Use the interactive UI to explore movie recommendations

## Conclusion

This project demonstrates a content-based movie recommendation system that efficiently analyses textual similarities to suggest relevant movies. It highlights the effectiveness of NLP techniques in recommendation engines and explores how interactive components enhance user experience.
