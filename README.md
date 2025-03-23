# Ai-vs.-Human-Text-Classifier-LSTM
This project builds an AI vs Human Text Classifier using LSTM to tell the difference between text written by humans and AI. Using NLP techniques, the model learns to classify text into two categories: human or AI-generated, showcasing how deep learning can help us spot machine-created content in a natural way.

📖 More About LSTM

LSTM (Long Short-Term Memory) is a type of Recurrent Neural Network (RNN) that is well-suited for processing sequential data, such as text. Unlike standard RNNs, LSTMs can learn long-range dependencies, making them effective for natural language processing (NLP) tasks.

💡 Why LSTM for Text Classification?
✅ Memory Cell Mechanism: LSTM networks have a built-in memory cell that retains useful information from earlier inputs while filtering out irrelevant details.
✅ Gated Structure: LSTMs use forget, input, and output gates to control the flow of information, preventing the issue of vanishing gradients common in traditional RNNs.
✅ Context Awareness: Unlike traditional machine learning models, LSTMs understand the context of words in a sequence, making them powerful for text-based tasks.
✅ Better Performance on Text Data: LSTMs outperform simple RNNs in language modeling, text classification, sentiment analysis, and AI-generated content detection.

🛠️ How We Used LSTM in This Project

In this classifier, we:

Embedded the text into dense vector representations using an Embedding layer.

Used an LSTM layer to process sequential word representations and capture long-term dependencies.

Added Dropout to prevent overfitting and improve generalization.

Used a Dense layer with a Sigmoid activation for binary classification (human or AI-generated text). 


📌 Summary of Key Techniques Used in this project

✅ Natural Language Processing (NLP)
✅ Hugging Face Dataset Integration
✅ Text Preprocessing (Tokenization & Padding)
✅ LSTM-based Recurrent Neural Network (RNN)
✅ Binary Classification with Sigmoid Activation
✅ Loss and Accuracy Visualization
✅ Deployment via Streamlit

📩 Contributing
Feel free to fork the repo, create a pull request, or report issues : ghanemi.zinaddine@euruni.edu
