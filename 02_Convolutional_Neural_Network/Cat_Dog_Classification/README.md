Follow these steps to make the clean execution of Program.
1. Download the dataset from [here](https://www.kaggle.com/c/dogs-vs-cats/data).
2. From the train folder, select first 12500 images and stored them inside separate folder with name `cat`.
3. From the same folder, select last 12500 images and stored them inside another separate folder with name `dog`.
4. Make sure these folders are inside the train folder.
5. The structure of the directory should resemble this.
```
|-- Cat_Dog_Classification
    |-- README.md
    |-- data_preparation.ipynb    
    |-- cat_dog_classification.ipynb
    |-- train
        |-- cat
            |-- cat.0.jpg
            |-- cat.1.jpg
            |-- ...
        |-- dog
            |-- dog.0.jpg
            |-- dog.1.jpg
            |-- ...
    |-- test
        |-- 1.jpg
        |-- 2.jpg
        |-- ...
```
6. Once you setup everything, run the `data_preparation.ipynb` notebook to pre-process images and make them ready for modelling.
7. After, run the `cat_dog_classification.ipynb` notebook to train the model.