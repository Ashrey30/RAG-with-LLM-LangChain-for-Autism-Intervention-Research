# LangChain Integration for Multimodal AI Approach to Streamline Autism Diagnosis

## Overview:
This repository showcases the integration of LangChain, a natural language processing toolkit, to streamline the process of autism diagnosis in young children. By leveraging LangChain's functionalities, including document loading, text processing, embedding generation, and document retrieval, we aim to provide a comprehensive solution for querying relevant research documents related to multimodal AI approaches for autism diagnosis.

## Dependencies:
- Python 3.x
- LangChain (version X.X.X)
- PyPDF2
- FAISS
- HuggingFace Transformers
- Other dependencies as specified in the code

## Usage:
1. **Setup Environment**:
   - Make sure you have Python installed on your system.
   - Install necessary dependencies using pip:
     ```
     pip install langchain pyPDF2 faiss huggingface-transformers
     ```

2. **Clone Repository**:
   - Clone this repository to your local machine:
     ```
     git clone <repository_url>
     ```

3. **Run the Code**:
   - Navigate to the cloned repository directory:
     ```
     cd <repository_directory>
     ```
   - Run the Python script containing the code:
     ```
     python main_script.py
     ```

4. **Input Question**:
   - Provide a question related to multimodal AI approaches for autism diagnosis when prompted.

5. **View Results**:
   - The script will output relevant research documents based on the provided question.

## Code Structure:
- **main_script.py**: Contains the main code implementing LangChain integration for document loading, text processing, embedding generation, and document retrieval.
- **papers/**: Directory containing PDF documents related to autism diagnosis research.
- **InstructorEmbedding.py**: Module defining an instructor embedding for contextual document embeddings.
- **README.md**: This file providing an overview of the repository and usage instructions.

## Contributors:
- [Ashrey] (@Ashrey30) (IIT Madras BS Data Science and Applications)

## License:
This project is licensed under the [License Name] License - see the [LICENSE](LICENSE) file for details.
