# LLM Zero Shot Classifier to Improve Dataset Accuracy

- Using LLMs as zero shot classifiers for multilabel sentiment classifcation on 50K movie reviews dataset from IMDB.

- Dataset link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download

- Model: Bert Meta Large

- Labels = Positive | Negative | Neutral 

- Boosted Infrence on GPU using Accelerate: NVIDIA 3080 3hrs Infrence time

- around 6K reviews assigned a new sentiment based on LLM Bert Large;  12% of the dataset
