# Chatbot with NLP and Deep Learning

This is a text-based chatbot that uses Natural Language Processing (NLP) and Deep Learning (Neural Networks) to understand user input and respond accordingly. The chatbot can recognize multiple intents and generate context-appropriate responses.

## 📌 Features

* Text-based chatbot with real-time user interaction.
* Natural Language Processing (NLP) using NLTK for text preprocessing (tokenization, lemmatization).
* Deep Learning model with TensorFlow/Keras for intent classification.
* Supports multiple conversation intents, loaded from a JSON file.
* Example prompts and responses included for easy testing.

## ⚙️ Prerequisites

* Python 3.8 or above.
* pip (Python package installer).

## 🚀 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ruxith/ChatBot-AI.git
   cd ChatBot-AI
   ```

2. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Download NLTK packages:**

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

## 📝 Usage

1. Ensure that the `intents.json` file is in the same directory as the main script.
2. Run the chatbot script:

   ```bash
   python main.py
   ```
3. Type your message and receive a response from the chatbot.
4. Type `0` to end the chat.

### 💬 Example Interactions

* User: *Hello*

  * Bot: *Hi!*

* User: *How are you?*

  * Bot: *I am feeling good, you?*

* User: *What can you do?*

  * Bot: *I can tell you the capital of a country, calculate math operations, or generate a random number.*

* User: *Are you still there?*

  * Bot: *Of course! Always at your service.*

## 📂 Project Structure

```
├── main.py             # Main chatbot script
├── intents.json        # JSON file with conversation intents
├── requirements.txt
└── README.md           # Project documentation
```

## 📌 How It Works

* The chatbot uses NLTK for text preprocessing (tokenization, lemmatization).
* The processed text is transformed into a Bag of Words (BoW) representation.
* A Neural Network (Sequential Model with Dense and Dropout layers) classifies the user’s input based on trained intents.
* The model is trained using TensorFlow/Keras and can recognize multiple intents.

## ✅ Future Improvements

* Add more intents and responses to cover a wider range of topics.
* Enhance conversation continuity with context management.
* Implement a graphical user interface (GUI) for easier interaction.
* Optimize the model for faster response times.

## 🤝 Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

