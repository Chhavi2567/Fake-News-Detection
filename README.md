# Fake News Prediction

## About the Dataset
The dataset used in this project contains the following features:

1. **id**: Unique identifier for a news article.  
2. **title**: Title of the news article.  
3. **author**: Author of the news article.  
4. **text**: Content of the news article (may be incomplete).  
5. **label**: Indicates whether the news article is real or fake:  
   - `1`: Fake news  
   - `0`: Real news  

## Project Overview
This project aims to classify news articles as real or fake using machine learning techniques. The key steps include:

- **Importing Dependencies**: Preparing the necessary Python libraries and packages.  
- **Data Preprocessing**: Cleaning and transforming the data to prepare it for model training.  

## Features of the Project
- Exploratory Data Analysis (EDA) to understand the dataset.
- Data preprocessing techniques such as handling missing values and text tokenization.
- Implementation of machine learning models for classification.
- Evaluation of model performance using metrics like accuracy, precision, and recall.

## How to Run the Project
1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd fake-news-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Copy of Project 5. Fake News Prediction.ipynb"
   ```

5. Run all cells in the notebook to execute the project.

## Results
- The model effectively distinguishes between real and fake news articles.
- Performance metrics are detailed in the notebook.

## Future Improvements
- Explore more advanced models like transformers for text classification.
- Incorporate additional features from the dataset for better predictions.

## Contributing
Contributions are welcome! If you would like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The dataset used in this project was sourced from publicly available repositories. Special thanks to the contributors who made it accessible.
