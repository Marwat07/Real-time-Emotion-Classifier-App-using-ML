This is a web-based application that uses a machine learning model to classify emotions from text. You can type in a sentence, and the application will predict the emotion conveyed by the text.

## Features

- **Real-time Emotion Detection:** Instantly analyze the emotions expressed in any given text.
- **Confidence Score:** Provides a confidence score, indicating the model's certainty in its predictions.
- **User-friendly Interface:** The intuitive user interface allows you to effortlessly input text, view the results, and interpret the emotions detected.
- **Application Monitoring:** The "Monitor" section displays metrics about the application's usage, including page visits and emotion predictions.

## How It Works

1.  **Input:** You enter text into a text area on the web page.
2.  **Prediction:** The application uses a pre-trained machine learning model (`emotion_classifier_pipe_lr.pkl`) to analyze the text and predict the corresponding emotion.
3.  **Output:** The application displays the predicted emotion along with a confidence score and an emoji. It also shows a bar chart with the probabilities for all possible emotions.

## Setup and Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the application:**

    ```bash
    streamlit run app.py
    ```

2.  **Access the application:**

    Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).

3.  **Use the application:**

    -   **Home:** In the "Home" section, you can type or paste text into the text box and click "Submit" to see the emotion prediction.
    -   **Monitor:** The "Monitor" section displays metrics about the application's usage, including page visits and emotion predictions.
    -   **About:** The "About" section provides more information about the application.

## Dependencies

-   streamlit
-   altair
-   plotly
-   pandas
-   numpy
-   joblib
-   scikit-learn
