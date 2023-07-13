# NER-using-Bi-LSTM
• Developed deep learning-based Named Entity Recognition (NER) system to analyze political memes for the US election.

• Applied data preprocessing, contextual information, and ensemble methods. Demonstrated expertise in deep learning,
NER, OCR, and data analysis for political discourse analysis

## Data
We have the OCR data of the memes which can be categorized into two groups, covid related memes and US politics related memes.
Their are two types of data available images and Text data which have OCR text from the memes and tags.
### The OCR text data
<img width="742" alt="image" src="https://github.com/Yoge-sh/NER-using-Bi-LSTM-Analyzing-Political-Memes/assets/93325653/8f99c337-0556-4179-b27b-02a171555627">

### Original Memes
<img width="767" alt="image" src="https://github.com/Yoge-sh/NER-using-Bi-LSTM-Analyzing-Political-Memes/assets/93325653/14c576c6-a069-417e-b1a5-d54cdd51a1c6">

But it is noticed that its hard to labeled the hero, villain, victim just by seeing the image, you should know the context behind it
For example, China is being mentioned in covid related memes because Covid was spread from China, one should know the context behind the meme to labelled China as a villain in the meme
But already we have labelled data with hero, villain, victim and other tag along with the OCR of the images as you can see above

Hence we continued with the textual data

## Results
The dataset we have contains OCR image names and tags assigned to specific entities, such as heroes, villains, victims, and others.

The OCR text has been extracted from the images, but the challenge lies in the fact that the tags provided may or may not be present in the OCR text. As a result, the overall accuracy of your predictions is low.

1. For word-to-word predictions as done in the section 5 got about **92%** accuracy and F1-score of about 46% which is not that good but considering the text data and memes dissimilarity it is pretty descent
2. For propar whole sentence wise predictions we got 50 % accuracy whereas F1-score is irrelevant considering the number of unique sentence and their unique tags
