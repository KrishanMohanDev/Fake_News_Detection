# Fake News Detection Project

This project aims to classify news articles as either fake or real using machine learning techniques. Below are the necessary steps to run this project:

## Description

The Fake News Detection project utilizes machine learning algorithms to classify news articles as either fake or real. The dataset consists of labeled news articles, with features extracted from the text content. The project preprocesses the data, trains several classification models including Logistic Regression, Decision Trees, Gradient Boosting, and Random Forest, and evaluates their performance using metrics such as accuracy, precision, recall, and F1-score.

After training the models, users can manually test the news classification using the `manual_testing` function, which takes input news articles and predicts their authenticity based on the trained models.

## Files

1. `Fake_News_Detection.ipynb`: Jupyter Notebook containing the Python script for fake news detection.
2. `Dataset/Fake.csv` and `Dataset/True.csv`: CSV files containing labeled news articles, with features extracted from the text content.

## Installation

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/KrishanMohanDev/Fake_News_Detection.git
   ```

2. **Install Dependencies:**
   Ensure you have the required dependencies installed. You can install them using pip:
   ```
   pip install pandas scikit-learn
   ```

   
## Usage
3. **Run the Code:**
   Open the cloned repository in your preferred Python environment and run the code in a Jupyter Notebook or any Python editor.
   Open the `Fake_News_Detection.ipynb` notebook and execute the cells to run the fake news detection script.
   ```
   jupyter notebook Fake_News_detection.ipynb
   ```

5. **Data Preparation:**
   Ensure the datasets `Fake.csv` and `True.csv` are placed in the `Dataset` directory within the project folder.

6. **Execute the Code:**
   Execute the code cells provided in the Jupyter Notebook or Python script. This will preprocess the data, train different machine learning models, and evaluate their performance.

7. **Manual Testing:**
   After training the models, you can manually test the news classification using the `manual_testing` function. Enter a news article when prompted, and the models will predict whether it's fake or real.

8. **Interpret Results:**
   Interpret the results obtained from the classification models to determine their effectiveness in detecting fake news.

9. **Experimentation:**
   Feel free to experiment with different machine learning models, hyperparameters, and feature engineering techniques to improve the performance of the fake news detection system.

10. **Contribute:**
   Contributions to this project, such as adding new features or improving existing algorithms, are welcome. Fork the repository, make your changes, and submit a pull request.

11. **Enjoy!**
   Explore the code, learn about fake news detection techniques, and enjoy experimenting with the project!


## Notes

- Ensure the datasets `Fake.csv` and `True.csv` are placed in the `Dataset` directory within the project folder.

## Author

- [Krishan Mohan Mandal](https://github.com/KrishanMohanDev)

## License

This project is licensed under the [MIT License](LICENSE).
