“This project focuses on building a multilingual language detection system using NLP and machine learning.
The goal was to automatically identify the language of a given text input, which is an important preprocessing step for applications like translation, chatbots, and text analytics.

I worked with a dataset containing around 22,000 text samples across 22 different languages. Since languages differ not only by words but also by character patterns, I chose a character-level TF-IDF vectorization approach using 2 to 4 character n-grams. This helped the model capture language-specific patterns such as scripts, accents, and letter combinations.

After preprocessing the text, I trained a Multinomial Naive Bayes classifier, which is well-suited for text classification tasks. The dataset was split into training and testing sets, and the model achieved approximately 97.5% accuracy on unseen data.

I evaluated the model using precision, recall, and F1-score, and observed strong performance across most languages, including non-Latin scripts like Arabic and Tamil.
Finally, I created a prediction function that allows users to input any text and instantly get the detected language.
