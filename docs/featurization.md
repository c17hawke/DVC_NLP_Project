# Featurization stage in progress

### Step 01- create train and test data path and relevanr directories as needed

### Step 02- create a dataframe from the train data

### Step 03- Apply Bag of words
```python
bag_of_words = CountVectorizer(
        stop_words="english",
        max_features=max_features,
        ngram_range=(1, n_grams)
    )
```

### Step 04- Apply TFIDF
```python
tfidf = TfidfTransformer(smooth_idf=False)
    tfidf.fit(train_words_binary_matrix)
    train_words_tfidf_matrix = tfidf.transform(train_words_binary_matrix)
```

### Step 05- Apply same steps for test data but without the fit method

### Step 06- Save the data in form of pkl object





