# Recommender System Project README

## Project Overview

This project demonstrates the implementation of a Recommender System, a type of machine learning model that provides personalized recommendations to users based on their preferences and behaviors. In this project, we focus on building a collaborative filtering-based recommender system using the MovieLens 100K dataset. Collaborative filtering methods make recommendations by using the preferences and behaviors of other users. Two approaches are explored in this project: Memory-Based Collaborative Filtering and Model-Based Collaborative Filtering.

## Prerequisites

Before running the code in this project, make sure you have the following prerequisites installed:

- Python (3.x recommended)
- Jupyter Notebook or any Python IDE
- Required Python libraries (numpy, pandas, scikit-learn, scipy)

You can install the required libraries using the following command:

```bash
pip install numpy pandas scikit-learn scipy
```

## Project Structure

- `Recommender_System_Project.ipynb`: Jupyter Notebook containing the code and explanations for the recommender system analysis.
- `u.data`: MovieLens 100K dataset containing user ratings.
- `Movie_Id_Titles`: CSV file containing movie titles for the dataset.

## Installation

1. Clone or download this project repository to your local machine.
2. Open the Jupyter Notebook (`Recommender_System_Project.ipynb`) using your preferred Python IDE or Jupyter Notebook itself.
3. Ensure you have the dataset file named `u.data` and the movie titles file named `Movie_Id_Titles` in the same directory as the notebook.

## Usage

1. Open the Jupyter Notebook and run each cell step by step to follow the recommender system analysis process.
2. The notebook contains detailed comments and explanations for each code cell to help you understand the workflow.

## Memory-Based Collaborative Filtering

The project begins with Memory-Based Collaborative Filtering:

- Loading the MovieLens 100K dataset and exploring its structure.
- Splitting the dataset into training and testing sets using `train_test_split` from scikit-learn.
- Creating user-item matrices for both training and testing data.
- Calculating user-user and item-item similarity matrices using cosine similarity.
- Implementing prediction functions for user-based and item-based collaborative filtering.
- Evaluating the models using Root Mean Squared Error (RMSE) as a performance metric.

## Model-Based Collaborative Filtering

The project explores Model-Based Collaborative Filtering:

- Measuring the sparsity level of the MovieLens 100K dataset.
- Implementing Singular Value Decomposition (SVD) to reduce dimensionality and build a model-based recommender system.
- Using SVD components to make predictions and evaluate the model's performance with RMSE.

## Contributing

If you want to contribute to this project, feel free to fork the repository, make changes, and create a pull request. We welcome any contributions or improvements.


---

Feel free to reach out if you have any questions or need further assistance with this project. Happy coding!
