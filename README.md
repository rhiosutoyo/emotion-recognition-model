# Indonesian Twitter Emotion Recognition using Feature Engineering
This research explores feature engineering techniques to find the best features for building an emotion recognition model on the Indonesian Twitter dataset. Two different text data representations were used, namely TF-IDF and word embedding.<br><br>
This research proposed 12 feature engineering configurations in TF-IDF by combining data stemming, data augmentation, and machine learning classifiers. Moreover, this research proposed 27 feature engineering configurations in word embedding by combining three-word embedding models, three pooling techniques, and three machine-learning classifiers. In total, there are 39 feature engineering combinations.

## Dataset & Experiment Results

- **Dataset**<br>
The preprocessed dataset was derived from the [Indonesian Twitter Emotion Dataset](https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset) from [Saputri et al.](https://doi.org/10.1109/IALP.2018.8629262). In the data preprocessing, this work performs case-folding, removes irrelevant information, applies standardization, data stemming, and removes stop words. The file can be downloaded in this [CSV file](https://github.com/rhiosutoyo/emotion-recognition-model/blob/main/preprocessed-dataset.csv).

- **Experiment Results**<br>
The full results of the experiment can be seen in this [CSV file](https://github.com/rhiosutoyo/emotion-recognition-model/blob/main/full-experiment%20result.csv).
The order is sorted by f1 score (descending).

## BibTeX Citation

If you use this dataset in a scientific publication, we would appreciate using the following citations:

```
@article{Sutoyo2023,
  title = {Indonesian Twitter Emotion Recognition Model using Feature Engineering},
  journal = {International Journal of Advanced Computer Science and Applications},
  doi = {10.14569/IJACSA.2023.01412108},
  url = {http://dx.doi.org/10.14569/IJACSA.2023.01412108},
  year = {2023},
  publisher = {The Science and Information Organization},
  volume = {14},
  number = {12},
  author = {Rhio Sutoyo and Harco Leslie Hendric Spits Warnars and Sani Muhamad Isa and Widodo Budiharto}
}
```
