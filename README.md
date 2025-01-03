# Emotion-Detection-using-text
Emotion Detection Using Hybrid Techniques


Emotion detection from text using PyTorch and LSTM
For this project, we are going to implement an NLP task of creating a model to detect the emotion from text. We will develop this using the PyTorch library and the Federated Learning framework for decentralized training.

We will create an emotion detection for the following 5 emotions:

Emotion	Emoji	Label
Loving	❤️	0
Playful	⚽️	1
Happy	😄	2
Annoyed	😞	3
Foodie	🍽	4
Dataset
We will work with a dataset (X, Y) where we have:

X contains 132 sentences
Y contains a label between [0, 4] corresponding to the five emotions.
For example:

Sentence	Emotion
food is life	🍽 Foodie
I love you mum	❤️ Loving
Stop saying bullshit	😞 Annoyed
congratulations on your acceptance	😄 Happy
The assignment is too long	😞 Annoyed
I want to go play	⚽️ Playful
she did not answer my text	😞 Annoyed
Your stupidity has no limit	😞 Annoyed
how many points did he score	⚽️ Playful
my algorithm performs poorly	😞 Annoyed
I got approved	😄 Happy



The Model
We will build an LSTM model that takes as input word sequences that will take word ordering into account. We will use 50-dimensional GloVe pre-trained word embeddings to represent words. We will then feed those as an input into an LSTM that will predict the most appropiate emotion for the text.

[image](https://github.com/user-attachments/assets/7ca34c12-df9b-4d7a-bde7-a2905e9cc5f2)


The proposed model enhances emotion detection accuracy in text by utilizing advanced machine learning techniques, specifically BERT and LSTM. BERT is employed to extract context and sentiment from the text, enabling the model to understand the nuances of language more effectively. LSTM is used to capture long-term dependencies in the text, allowing the model to recognize the flow of emotions over time. By integrating these approaches, the model gains a deeper understanding of user emotions, enabling more accurate emotional classification.

This enhancement has significant implications. In mental health, it can help therapists identify emotional triggers and respond more effectively. For businesses, it can enable empathetic customer service by recognizing emotions in customer interactions, leading to better satisfaction and engagement. In human-computer interaction, the model can drive adaptive interfaces that adjust based on the user's emotional state, creating a more intuitive and engaging experience.

Overall, this approach represents a significant advancement in emotion detection, leveraging machine learning to improve the emotional sensitivity of AI systems and setting the stage for more human-centered technology

