# Arabic Poems NLP
### Goal of the project:
The core objective of this project is develop an Arabic poems topic modeling to predict the correct phase of poems that can correctly classify the topic.
### Exploratory data analysis:
After performing the initial EDA which included:
- Checked for nulls values.
- Checked for duplicates and remove.
- Chose a sample of 10,000 rows.
- Romoved unneeded columns.
### Natrual Langauge Processing
- Remove harakat, tashkeel and tatweel
- Remove extra spaces and punctuations
- Remove numbers
- Replace [آ إ أ] with [ا]
- Replace [ؤ] with [و]
- Replace repetted letter with single letter like [وو]  ,[ىى],[اا].
- Vectorization.
- Tokenization.
- Stemming.
- Remove Stop Word.
The number of columns and rows before cleaning were **8** and **1831770** After cleaning up the data the number of columns and rows are **1** and **1683815**.
![arabicpoem](https://user-images.githubusercontent.com/90555474/141990071-6a9e59e0-c828-431f-bb15-b2243ce9120b.png)
As shown in the figure above, these are the most common words in our data sample.
### Future Work:
we are working in  Topic Modeling using NMF and LDA. Finally, we will chose the best model and visualize the results to figure out the topics.
