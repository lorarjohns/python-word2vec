# Word2Vec in Python

This is my implementation of word2vec for Stanford's NLP with deep learning graduate course.

![sample vectors](word_vectors.png)

- Create and activate virtual environment (using pyenv)
```
pyenv virtualenv 3.6.8 w2v

```

- Install requirements
```
python -m pip install -r requirements.txt
```

- You can create and activate a virtual environment using conda
```
conda env create --file local_env.yml
conda activate A2
conda deactivate
```


- Train word2vec and generate files *sampleVectors.json* and *word_vectors.png*

```
python run.py
```

- Sanity check on sampleVectors.json
```
python test_sample_vectors.py
```
