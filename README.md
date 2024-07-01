# SMS Spam Detection Task

This project aims to detect spam messages from SMS texts using machine learning algorithms. The dataset used is the SMS Spam Collection dataset from Kaggle. The project involves data preprocessing, text vectorization using TF-IDF, and training models using Naive Bayes, Logistic Regression, and Support Vector Machine (SVM) classifiers.

## Installation

To get started, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/sms-spam-detection.git
    cd sms-spam-detection
    ```

2. **Install the required dependencies:**

    ```bash
    pip install pandas numpy scikit-learn
    ```

3. **Download the dataset from Kaggle:**

    ```bash
    from google.colab import files
    files.upload()
    ```

    After uploading your `kaggle.json` file, run:

    ```bash
    !mkdir -p ~/.kaggle
    !cp kaggle.json ~/.kaggle/
    !chmod 600 ~/.kaggle/kaggle.json
    !kaggle datasets download -d uciml/sms-spam-collection-dataset
    !unzip sms-spam-collection-dataset.zip
    ```

## Dataset

The dataset used in this project is the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from Kaggle.

## Data Preprocessing

The dataset is preprocessed to remove unnecessary columns and handle missing values. The labels are converted to binary format, where `0` indicates 'ham' (not spam) and `1` indicates 'spam'.

## Model Training and Evaluation

Three models are trained and evaluated in this project:

1. Naive Bayes
2. Logistic Regression
3. Support Vector Machine (SVM)

The text data is vectorized using TF-IDF before training the models. The data is split into training and testing sets to evaluate the performance of each model.

## Results

- **Naive Bayes** achieved an accuracy of 96.86%.
- **Logistic Regression** achieved an accuracy of 94.44%.
- **SVM** achieved an accuracy of 97.22%.

The Naive Bayes model was chosen as the best for this task due to its high accuracy and simplicity.

## Contact

If you have any questions or suggestions, feel free to contact me:

- **Email:** gaurityagi21@gmail.com
- **Linkedin:** https://www.linkedin.com/in/gaurityagi21/
- **GitHub:** https://github.com/gaurityagi21/
  

Thank you for checking out this project!
