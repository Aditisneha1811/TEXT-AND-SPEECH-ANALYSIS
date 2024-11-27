**Emotion Detection and Quote Recommendation**
This project is a mini-project developed as part of the Text and Speech Analysis course. The system detects emotions from textual input and provides relevant quotes to match the identified emotional state.

**Features**
Emotion Prediction:

Identifies emotions such as happiness, sadness, anger, fear, etc., from a given text.
Returns "invalid" for meaningless or unclear input.
Quote Recommendation:

Suggests motivational or contextually relevant quotes based on the detected emotion.
JSON Generation:

Generates a structured JSON file containing quotes categorized by emotions.
Interactive User Interface:

Powered by Gradio, enabling easy input and response visualization.
Displays the predicted emotion and a suitable quote in real-time.

**Requirements**
Python (>=3.7)
**Libraries**:
Gradio
Pandas
Numpy
TensorFlow/PyTorch (for emotion detection model)
NLTK or similar library (for text preprocessing)
**How It Works**
Users input a text phrase through the GUI.
The system preprocesses the text and predicts the emotion using a trained model.
Based on the predicted emotion, a suitable quote is retrieved and displayed.
Invalid inputs are flagged to ensure meaningful interaction.
