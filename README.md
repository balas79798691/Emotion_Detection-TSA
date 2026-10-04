[Emotion_Detection_README.md](https://github.com/user-attachments/files/33029731/Emotion_Detection_README.md)
# Emotion_Detection-TSA# Text Emotion Detection Application

A Python-based Text & Speech Analysis project that identifies the dominant emotion expressed in written text.

## Objective

The objective of this project is to analyze emotional words in text and classify the text into categories such as Joy, Sadness, Anger, Fear, Surprise, Love, or Neutral.

## Features

- Accepts user text
- Cleans and preprocesses input
- Detects emotion-related words
- Calculates scores for different emotions
- Identifies the dominant emotion
- Includes multiple test cases
- Visualizes emotion distribution

## Technologies Used

- Python
- Pandas
- Matplotlib
- Regular Expressions
- Rule-based NLP

## Emotion Categories

The application detects:

- Joy
- Sadness
- Anger
- Fear
- Surprise
- Love
- Neutral

## NLP Technique

The project uses a **rule-based emotion detection approach**.

A predefined emotion vocabulary is used. The words in the user's text are compared against these vocabularies, and the emotion with the highest matching score is selected.

## How It Works

1. User enters a sentence.
2. The text is converted to lowercase.
3. Punctuation is removed.
4. The text is tokenized into words.
5. Words are compared with emotion vocabularies.
6. Each emotion receives a score.
7. The emotion with the highest score becomes the dominant emotion.

## Example

**Input:**

```text
I am extremely happy and excited about our success.
```

**Output:**

```text
Dominant Emotion: Joy

Joy: 3
Sadness: 0
Anger: 0
Fear: 0
Surprise: 0
Love: 0
```

## Requirements

```bash
pip install pandas matplotlib
```

## Running the Project

Open `Emotion_Detection.ipynb` in Google Colab, Jupyter Notebook, or VS Code.

Run the cells sequentially and uncomment the application function to interact with the analyzer.

## Project Structure

```text
Emotion-Detection/
│
├── Emotion_Detection.ipynb
└── README.md
```

## Applications

- Social media analysis
- Customer feedback analysis
- Chat analysis
- Opinion mining
- Educational text analysis
- Basic emotional-content classification

## Future Enhancement

The rule-based approach can be extended using a labeled dataset and machine-learning or deep-learning models for more accurate emotion classification.

## Conclusion

This project demonstrates a simple and interpretable approach to identifying emotions in written language using Natural Language Processing concepts.
