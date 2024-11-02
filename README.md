# Movie-Recommendation-System


This project is a **Movie Recommendation System** built using machine learning in Python. It leverages techniques such as **TF-IDF Vectorization** and **Cosine Similarity** to suggest movies based on the similarity of their descriptions to a given movie or user preference.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Libraries Used](#libraries-used)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)

## Project Overview

This recommendation system uses a **content-based filtering approach** to suggest movies. The main goal is to provide a personalized experience by recommending movies similar to the ones users like. 

## Features

- Recommends movies based on user input
- Uses TF-IDF Vectorization to convert movie descriptions into a meaningful numerical format
- Calculates similarity between movies using Cosine Similarity

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook Project_18_Movie_Recommendation_System_using_Machine_Learning_with_Python.ipynb
   ```

## Usage

1. Run the notebook and execute all cells.
2. Enter the name of a movie you like.
3. The system will output a list of recommended movies similar to the one you entered.

## Libraries Used

- **NumPy** - For numerical operations
- **Pandas** - For data manipulation
- **Difflib** - For matching movie titles
- **sklearn** - For TF-IDF Vectorization and Cosine Similarity

## Project Structure

- `Project_18_Movie_Recommendation_System_using_Machine_Learning_with_Python.ipynb` - Jupyter Notebook containing the code and explanations.

## Future Enhancements

- Integrate collaborative filtering for better recommendations
- Add user rating-based filtering
- Enhance the dataset with more features, such as movie genre and release year

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have ideas for improvements.

---
