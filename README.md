  #SpamGuard 
  
  ## Live Link
[Access the live site here]( https://spamdetectorx.streamlit.app )

# Spam Detector

This project implements a spam detection tool using a Multinomial Naive Bayes (MNB) model. The application classifies messages as "Spam" or "Not Spam" based on user input.

## Features

- **Text Preprocessing**: The tool converts text to lowercase, removes punctuation, and filters out stopwords. It also uses stemming for better feature extraction.
- **Model Training**: Utilizes a trained MNB model for classification, with TF-IDF vectorization.
- **User-Friendly Interface**: Built with Gradio for easy interaction.

## Usage

1. **Install Dependencies**: Ensure you have the required libraries:

   ```bash
   pip install gradio nltk scikit-learn
   ```

2. **Run the Application**: Execute the script to launch the Gradio interface:

   ```python
   python streamlit_app.py
   ```

3. **Input**: Enter the message you want to classify in the input field.

4. **Output**: The model will return whether the message is "Spam" or "Not Spam".
