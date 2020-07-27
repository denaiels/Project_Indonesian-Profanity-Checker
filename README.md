# Project_Indonesian-Profanity-Checker

This is an application to check whether an input sentence contains profane/harsh words or not. In this project, the dataset used is a list of YoouTube video comments from the Indonesian YouTuber Ericko Lim, which mostly is of Indonesian language (many are slang languages) and these comments tend to have profane/harsh words within them, and each of the comment is tagged as 'PROFANE' or 'CLEAN'. This Porfanity Checker works using Bag-of-Words method, where in the training process, it is fed with the dataset we have provided and it learns which words are profane by counting the words' occurence in sentences that are considered profane or not profane.

Made by Team:
1. Albert Lilian Thamson (2201754412)
2. Daniel Santoso (2201756506)
3. Luwis Lim (2201761771)
4. Steven Odolf Yuwono (2201758045)

Dataset from: https://www.kaggle.com/alvinf/data-komentar-video-youtube-toxic-ericko-lim

Our references:
- https://victorzhou.com/blog/better-profanity-detection-with-scikit-learn/
- https://github.com/vzhou842/profanity-check
