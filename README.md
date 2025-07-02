# Caesar_cipher_AI

This repository contains a Python-based implementation of a Caesar Cipher decryption system enhanced with a neural network. The project, located at VesAnit/Caesar_cipher_AI, uses an LSTM-based model to decrypt text encrypted with a Caesar Cipher without requiring the shift key, achieving high accuracy on varied text inputs.
Features

Caesar Cipher Implementation: Encrypts text by shifting characters by a random number of positions in the alphabet.
AI-Powered Decryption: Employs an LSTM neural network to decrypt Caesar Cipher text without knowing the shift key, leveraging sequence learning to predict original text.
Data Preprocessing: Processes text data (e.g., Nietzsche texts from Project Gutenberg) into 60-character chunks, generating ~10,000 training examples.
High Accuracy: Achieves ~95.88% accuracy on a test dataset (Frankenstein text from Project Gutenberg) after training for 50 epochs.
Efficient Data Handling: Uses PyTorch's DataLoader and custom CaesarDataset for streamlined training and evaluation.




