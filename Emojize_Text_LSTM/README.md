# Emoji Prediction with LSTM

This repository contains code for a text classification model using LSTM (Long Short-Term Memory) neural networks to predict emojis based on input text. The model utilizes pre-trained word embeddings from GloVe (Global Vectors for Word Representation).

## Dataset

The dataset (`emoji_data.csv`) used for training consists of two columns:
- Column 1: Textual data (sentences or phrases)
- Column 2: Corresponding numerical labels representing different emojis

The labels are mapped to emojis using the following dictionary:
```python
emoji_dict = {
    0: ":red_heart:",
    1: ":baseball:",
    2: ":grinning_face_with_big_eyes:",
    3: ":disappointed_face:",
    4: ":fork_and_knife_with_plate:"
}
