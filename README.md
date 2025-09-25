
# Age Estimation and Gender Classification

The objective of this project is to train a Convolutional Neural Netowrk (CNN) model to predict the age and the gender of a person using the functional API Keras.  

## :file_folder: Project Structure

```bash
cnn-utkface
├── notebooks
│   ├── cnn_age_gender.ipynb
│  
├── data
│   ├── train_val
│   ├── test_val
│
├── README.md
├── requirements.txt
└── .gitignore

```

## :rocket: Code Execution
There are two different ways to execute the code.

### Google Colab
1. Open the notebook using the link: [Google Colab Link](https://colab.research.google.com/drive/1vgaCN0RBkPp5qTK1S7NPWhATAdEr7YbB?usp=sharing)
2. Upload the data folder provided to Google Drive.
3. Define the folder path where you uploaded the data folder in section Set variables.
4. Run all cells.

### Local
1. Clone the repository
```bash
  git clone 
```
2. Create a virtual environment
```bash
  python -m venv .venv
  source .venv/bin/activate
```
3. Install all dependencies
```bash
  pip install -r requirements.txt
```
4. Open the notebook and set the environment flag to local in the Set environment section.
```bash
  env = 'local'
```
5. Run all cells.

## :bulb: Blog
In order to follow a step by step process with the analysis of the results go to: [Train a CNN model from scratch using Keras](https://crist2201.github.io/projects/cnn_utkface/)

## :wrench: Technologies
- TensorFlow - Keras
- Kaggle dataset
- Matplotlib
- Python
- Google Colab
