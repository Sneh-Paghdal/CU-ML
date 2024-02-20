# Fake News Detection

This repository contains code and resources for a fake news detection project. The goal of this project is to develop a machine learning model that can classify news articles as either fake or real.

## Dataset

The dataset used for this project is not included in this repository. However, you can find the dataset on the following GitHub repository: [Fake News Dataset](https://github.com/mdrizwan1018/fakenews/tree/main/data).

The dataset consists of two main files:
- `fake.csv`: Contains fake news articles.
- `real.csv`: Contains real news articles.

Each file contains the following columns:
- `title`: Title of the news article.
- `text`: Content of the news article.
- `subject`: Subject or category of the news article.
- `date`: Date of publication.

## Project Structure

The repository has the following structure:
- `data/`: Directory to store the dataset files.
- `src/`: Directory to store the source code.
  - `data_processing.ipynb`: Jupyter Notebook for data preprocessing.
  - `model_training.ipynb`: Jupyter Notebook for training the fake news detection model.
  - `utils.py`: Utility functions used in the project.

## Usage

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/mdrizwan1018/fakenews.git`
2. Download the dataset files from the [Fake News Dataset](https://github.com/mdrizwan1018/fakenews/tree/main/data) repository and place them in the `data/` directory.
3. Open and run the Jupyter Notebooks in the `src/` directory for data preprocessing and model training.
4. Modify or extend the code as needed for your specific requirements.

## Dependencies

The project code requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

You can install the dependencies using pip: `pip install -r requirements.txt`.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to acknowledge the contributors of the [Fake News Dataset](https://github.com/mdrizwan1018/fakenews/tree/main/data) for providing the dataset used in this project. Their efforts in collecting and curating the data are greatly appreciated.
