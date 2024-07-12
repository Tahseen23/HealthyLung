# Healthy Lungs

Healthy Lungs is a Streamlit-based application designed to assist in diagnosing and providing a treatment roadmap for lung cancer patients. The application uses machine learning models trained on custom datasets to classify the stage of lung cancer from X-ray images and generates a comprehensive PDF report with treatment suggestions, surgery plans, and lifestyle changes.

## Features

- **Lung Cancer Stage Classification**: Uses a YOLO model trained on a custom dataset for accurate lung cancer stage classification.
- **LLM Integration**: Utilizes Mistral AI as a large language model to generate detailed and personalized treatment roadmaps.
- **Embedding and Vector Database**: Employs a Sentence Transformer for embedding and Pinecone for storing the vector database.
- **Data Storage**: Stores patient data using Firebase.
- **PDF Report Generation**: Generates a detailed PDF report using ReportLab.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/healthy-lungs.git
    cd healthy-lungs
    ```

2. **Install Dependencies**:
    Make sure you have `pip` installed. Then, run:
    ```sh
    pip install -r requirements.txt
    ```

3. **Set Environment Variables**:
    Set up the required environment variables for Pinecone, Firebase, and other services. You can do this by creating a `.env` file in the root directory with the following content:
    ```env
    PINECONE_API_KEY=your_pinecone_api_key
    FIREBASE_API_KEY=your_firebase_api_key
    ```

4. **Run the Application**:
    Start the Streamlit application:
    ```sh
    streamlit run app.py
    ```

## Usage

1. **Upload X-ray Image**: Upload the X-ray image of the patient's lungs.
2. **Enter Patient Details**: Provide patient information including name, ID, symptoms, and duration of symptoms.
3. **Generate Report**: The application will classify the stage of lung cancer, and generate a detailed PDF report with the treatment roadmap.



## Technologies Used

- **Machine Learning**: YOLO model trained on custom dataset for lung cancer stage classification.
- **Large Language Model**: Mistral AI for generating treatment roadmaps.
- **Embedding**: Sentence Transformer for generating embeddings.
- **Vector Database**: Pinecone for storing and retrieving embeddings.
- **Data Storage**: Firebase for storing patient data.
- **PDF Generation**: ReportLab for creating PDF reports.
- **Web Framework**: Streamlit for building the web application.



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



---

Feel free to reach out if you have any questions or need further assistance!

