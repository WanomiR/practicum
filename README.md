# Practicum US
Projects I worked on during my study at Practicum.
## Externships
| Project | Description | Libraries  |
|:- |:- |:- |
|[Music valence prediction](https://github.com/WanomiR/practicum/tree/main/Externship%20projects/Music%20valence%20prediction)| Before starting this project, I learned about signal processing techniques. For models training, I used one publicly available dataset of labeled songs, and another dataset obtained with the `spotipy` API and *HTML scraping*. I developed an algorithm for extracting audio features from an input audio file, then I trained several models on each dataset separately and on combined data, evaluating each model using the cross-validation technique and tuning hyperparameters with `GridSearchCV`. Additionally, I conducted a little test to see which model’s predictions are the closest to my personal subjective valence estimation. For the final solution, I wrote a Python script that takes an audio input and returns an estimated valence score with a 95% confidence interval. |*librosa, spotipy, beautifulsoup, catboost, lightgbm, xgboost, scikit-learn,  matplotlib, seaborn*|

## Data Science
| Project | Description | Libraries  |
|:- |:- |:- |
|[Telecom churn prediction](https://github.com/WanomiR/practicum/blob/main/DS%20projects/Telecom%20churn%20prediction/telecom-churn-prediction.ipynb)| Discovered patterns in customers’ behavior and dependencies between contract options and charges. Preprocessed data for training and tried several ML models. Used oversampling pipeline to avoid target leakage during parameter grid search. Determined the factors that affect churn. |*tensorflow keras, catboost, sklearn, imblearn, matplotlib, seaborn, pandas, numpy*|
|[Movie reviews classification](https://github.com/WanomiR/practicum/blob/main/DS%20projects/Movie%20reviews%20classification/movie-reviews-classification.ipynb)| Visualy explored the data to confirm that the train/test splitting is correct. Tried several text processing techniques using different libraries. Tested three ML models and determined the best model + processing technique combination for this dataset. | *torch, transformers, nltk, spacy, sklearn, lightgbm, matplotlib, seaborn, numpy, pandas*|
|[Age prediction by photo](https://github.com/WanomiR/practicum/blob/main/DS%20projects/Age%20prediction%20by%20photo/age-prediction.ipynb)| With ImageDataGenerator module built a `flow_from_directory` pipeline. Composed a script for the ResNet50 model training, uploaded and ran the model on the cloud-based GPU platform. | *tensorflow keras, ImageDataGen, matplotlib, seaborn, pandas, numpy*|
|[Car price prediction](https://github.com/WanomiR/practicum/blob/main/DS%20projects/Car%20price%20prediction/car-price-prediction.ipynb)| Explored and preprocessed the dataset, removed outliers. Applied one-hot and ordinal encoding for different ML algorithms, standardized numeric values. Evaluated 5 models with hyperparameters tuning, estimated each model's average error, training and prediction time.  | *sklearn, lightgbm, xgboost, catboost, matplotlib, seaborn, numpy, pandas* |

## Data Analysis
| Project | Description | Libraries  |
|:- |:- |:- |
|[Phone plans analyzis](https://github.com/WanomiR/practicum/blob/main/DA%20projects/Phone%20plans%20analyzis/phone-plans-analyzis.ipynb)| Preprocessed and merged data from several datasets. Used data aggregation and custom functions to calculate revenue. On histograms, showed the difference in plans and users' behavior. Ran statistical tests to validate findings. | *scipy, matplotlib, pandas, numpy* |