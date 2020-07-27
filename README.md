# Project_Indonesian-Profanity-Checker

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Luwis Lim (2201761771)
4. Steven Odolf Yuwono (2201758045)

**Dataset from:**

https://www.kaggle.com/alvinf/data-komentar-video-youtube-toxic-ericko-lim

**Our references:**
- https://victorzhou.com/blog/better-profanity-detection-with-scikit-learn/
- https://github.com/vzhou842/profanity-check

**Description:**

Indonesian Profanity Checker is a program to check whether an input sentence contains profane/harsh words or not. In this project, the dataset used is a list of YouTube video comments from the Indonesian YouTuber Ericko Lim, which mostly is of Indonesian language (many are slang languages) and these comments tend to have profane/harsh words within them, and each of the comment is tagged as 'PROFANE' or 'CLEAN'. Our Indonesian Profanity Checker works using Bag-of-Words method, where in the training process, it is fed with the dataset we have provided and it learns which words are profane by counting the words' occurence in sentences that are considered profane or not profane. We also used Indonesian common stopwords to filter the dataset.

**Results:**

We tried the program with 3 versions of dataset splits, where the ratio is train:test, those are 70:30, 80:20, and 90:10. From the experiment we did, we found out that the most optimal dataset to use is the 70:30 ratio, because it gets the highest accuracy among the others.

*DISCLAIMER: Examples shown may contain words that are offensive.*

70:30 Data Split
![](/data(split70+stopwords)/percobaan(70).png)
![](/data(split70+stopwords)/acc(70).png)

80:20 Data Split
![](/data(split80+stopwords)/percobaan(80).png)
![](/data(split80+stopwords)/acc(80).png)

90:10 Data Split
![](/data(split90+stopwords)/percobaan(90).png)
![](/data(split90+stopwords)/acc(90).png)
