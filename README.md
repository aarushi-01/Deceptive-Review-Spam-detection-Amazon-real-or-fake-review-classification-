---

# Deceptive Opinion Spam Detection

This project involves performing sentiment analysis on the Amazon Review Dataset to detect deceptive opinion spam, specifically distinguishing between fake and real reviews. The analysis includes plotting networking graphs based on review similarities using various Natural Language Processing (NLP) tools and techniques.

## Project Overview

The main objectives of this project are:

- Analyzing sentiment in a dataset of 30,000 Amazon reviews labeled as either fake or real.
- Utilizing NLP tools to extract features and similarities between reviews.
- Constructing networking graphs to visualize review connections and patterns.
- Developing a machine learning model to predict and identify fake spamming reviews.

## Key Features

- **Sentiment Analysis**: Conducted sentiment analysis on the Amazon Review Dataset using Python, Pandas, and NLP libraries.
  
- **Network Graphs**: Employed NetworkX to plot graphs where reviews are nodes connected based on their similarity parameters. This visualization strategy aids in understanding the structure of the review dataset.
  
- **Analysis by Product Categories**: The networking graphs were created for 30 different product categories, allowing for insights into how fake and real reviews behave across various types of products.
  
- **Identifying Patterns**: Observed that fake reviews exhibit higher similarity and interconnectedness compared to real reviews, which tend to be more random in their connections.

## Stack Used

The project leverages the following technologies and libraries:

- Python
- Pandas
- NumPy
- Natural Language Processing (NLP) tools
- NetworkX (for plotting networking graphs)
- Matplotlib (for data visualization)
- Machine Learning Algorithms (for building the predictive model)

## Usage

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/aarushi-01/deceptive-opinion-spam-detection.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib networkx <other_required_libraries>
   ```

3. **Run the Analysis**:
   - Open and run the provided Python scripts or Jupyter notebooks to replicate the sentiment analysis, networking graph plotting, and machine learning model training.

## Results

The insights gained from this project are valuable for understanding deceptive opinion spam in online reviews. By leveraging machine learning and NLP techniques, this project aims to contribute to the development of more robust spam detection systems.

## Contributors

- [Aarushi Singh](https://github.com/aarushi-01)
