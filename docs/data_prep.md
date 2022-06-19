# Data Preparation stage

- Convert my data into train and test.tsv in 70:30 ratio 
```
data.xml
    |-train.tsv
    |-test.tsv
```

- We are choosing only three tags in the xml data - 1. row Id, 2. title and body 3. Tags
(Stackoverflow Tags specific to python)
 

|Tags|feature names|
|-|-|
|row Id|row ID|
|title and body|text|
|stackoverflow tags|Label - Python|
