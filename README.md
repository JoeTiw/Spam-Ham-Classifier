# Spam-Ham-Classifier
This is a simple web app that uses machine learning to classify text messages as spam or ham (non-spam). The app is built using the Streamlit library and is based on a model trained on a dataset of SMS messages.

**How to use the app**

To use the app, simply enter a text message in the input field and click the "Predict" button. The app will then classify the message as either spam or ham and display the prediction.

**How the model works**

The model uses a combination of natural language processing techniques and machine learning algorithms to identify spam messages. It starts by preprocessing the input text, which includes steps such as lowercasing, tokenization, and stemming. The processed text is then vectorized using a count vectorizer, and the resulting vector is fed into the model for prediction.

**Resources**

The code for this app is based on the SMS Spam Collection Dataset available on Kaggle. The model was trained using machine learning techniques and the pickle library was used to save and load the trained model. The app is built using the Streamlit library.
