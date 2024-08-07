# Skincare Guide Chatbot with RAG and Vector Database

## Overview
This project is a specialized chatbot application designed to offer personalized skincare recommendations. By leveraging Large Language Models (LLM) for understanding and processing natural language queries, combined with the efficiency of a vector database for data storage and retrieval, this chatbot provides tailored skincare advice using Retrieval-Augmented Generation (RAG). The application is developed using Flowise and integrates various components to deliver accurate and relevant skincare information to users.

## Features
- **Domain**: Skincare guide, offering personalized skincare tips and advice.
- **RAG-Based Recommendations**: Uses Retrieval-Augmented Generation to generate personalized skincare recommendations.
- **Components Used**:
  - **Recursive Character Text Splitter**: Splits text into manageable chunks for efficient processing.
  - **CSV File**: For uploading and managing skincare data.
  - **OpenAI Embeddings**: Embeds queries and context with OpenAI's text-embedding-3-large model.
  - **Pinecone Upsert Document**: Stores and indexes data in the Pinecone vector database.
  - **Conversational Retrieval QA Chain**: Retrieves relevant skincare information.
  - **ChatOpenAI**: The primary chat interface for user interaction.

## User Base
The application is intended for individuals seeking personalized skincare advice. It provides users with quick and accurate responses to their skincare queries based on their input.

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm
- Flowise

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/manikanta-reddy-thikkavarapu-neu/Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline
    ```

### Running the Application
1. Start Flowise:
    ```sh
    npx flowise start
    ```
2. Open your browser and navigate to `http://localhost:3000` to access the chatbot interface.
3. Ensure your OpenAI API and Pinecone API are correctly set up and running.
4. Run **chatbot.html** using Live Server.

### Usage
- Upload the skincare data CSV file via the provided interface.
- Enter your skincare-related query into the input box.
- The chatbot will process your query and provide a relevant response based on the skincare data and LLM.

## Evaluation and Testing
The application has been tested with a range of skincare queries to ensure its performance, accuracy, and usability. Some example queries include:
- "What are the best treatments for acne?"
- "Recommend a skincare routine for dry skin."
- "How can I protect my skin from sun damage?"

## Video Demonstration
A detailed video walkthrough of the application demonstrating its features and usage can be found [here](https://youtu.be/c9MU4RznusY).

## Documentation
- **Flowise Documentation**: [Flowise Documentation](https://docs.flowiseai.com/)
- **OpenAI Documentation**: [OpenAI Documentation](https://beta.openai.com/docs/)
- **Pinecone Documentation**: [Pinecone Documentation](https://docs.pinecone.io/)

---
