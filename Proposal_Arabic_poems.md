# Arabic Poems NLP
## Abstract
Arabic poems are the oldest and the most prominent form of Arabic literature today. Ancient Arabic poetry is probably the primary source for describing the social, political, and intellectual life in the Arab world.
In this project, we will develop an Arabic poems topic modeling to predict the correct phase of poems that can correctly classify the topic.
## Problem
Our Problem is about **Arabic poems NLP** and our task will be To prepare a dataset & classify each document into a category.
1. Annotate the given dataset
2. Train your model
3. Predict the categories in test set (in a new column)
## Data Description
the dataset contains over 1M Arabic poems that extend from the 6th century to the present day. The datase that will be used in this project has been downloaded from [here]( https://hci-lab.github.io/LearningMetersPoems/).the total number of terms is **1,831,770** poetic terms. Each terms is labeled by its **meter**, the poet who wrote it, and the **age** which it was written in. There are **22 meters**, **3701 poets and 11 ages**: Pre-Islamic, Islamic, Umayyad, Mamluk, Abbasid, Ayyubid, Ottoman, Andalusian, era between Umayyad and Abbasid, Fatimid, and finally the modern age.  It is important to note that the terms diacritic states are not consistent. This means that a term can carry full, semi diacritics, or it can carry nothing.
## Tools:
* Software Platform :Jupyter Notebook
* Programming Language: Python
* Python Libraries:
  * Statistics libraries:
  * Sklearn
  * nltk
* Data manipulation libraries:
  * Pandas
  * Numpy
  * byArabic package
* Visualization libraries
  * Matplotlib
  * Seaborn
* Storage libraries
  * Pickle
