# AI-Powered-Document-Management-System
<p align="center">
  <img width="460" height="300" src="https://github.com/user-attachments/assets/a3b1543e-0eb5-4fd2-8280-9fd3342d650b"
>
</p>
This project aims to create an intelligent document management system leveraging cutting-edge technologies in AI and blockchain. Developed for HACKNDORE, developed by INNOVATORSHUB TEAM.
Here is a professional README file for the project:
The system includes the following key components:

1. **AI-Powered Document Classification**: Automatically classifies and tags documents based on their content using Natural Language Processing (NLP).
2. **Blockchain for Document Integrity**: Ensures document authenticity and integrity by leveraging blockchain technology.
3. **Smart Document Search**: Implements an AI-driven search engine that understands context and synonyms, providing more accurate search results.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
The AI-Powered Document Management System is designed to enhance the efficiency, security, and accuracy of document handling in various applications, such as municipal services, legal departments, and business operations. By integrating machine learning, blockchain, and advanced search capabilities, this system provides a robust solution for modern document management needs.

## Features
### AI-Powered Document Classification
- Uses a pre-trained BERT model to automatically classify documents such as NoCs, birth certificates, and death certificates into appropriate categories.
- Facilitates the organization of documents into relevant folders or tags for easy retrieval.

### Blockchain for Document Integrity
- Leverages blockchain technology to ensure the authenticity and integrity of documents.
- Stores document hashes in a blockchain ledger, making it tamper-evident and providing a secure audit trail.

### Smart Document Search
- Implements a context-aware search engine using Word2Vec embeddings.
- Provides accurate search results by understanding the context and synonyms of search queries, surpassing traditional keyword-based search methods.

## Installation
To install and run the project, follow these steps:

### Prerequisites
- Python 3.7+
- Google Colab account
- Required Python libraries: `transformers`, `torch`, `pycryptodome`, `gensim`, `sklearn`

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/sid1018/AI-Powered-Document-Management-System.git
   cd AI-Powered-Document-Management-System
   ```

2. Open each notebook in Google Colab:
   - `Document_Classification.ipynb`
   - `Blockchain_Integrity.ipynb`
   - `Smart_Search.ipynb`

3. Install the required libraries within each notebook:
   ```python
   !pip install transformers torch pycryptodome gensim scikit-learn
   ```

4. Run each cell in the notebooks to execute the code.

## Usage
### Document Classification
1. Load the `Document_classification.ipynb` notebook in Google Colab.
2. Run the cells to train the BERT model and classify sample documents.
3. Save the trained model for future use.

### Blockchain for Document Integrity
1. Load the `Blockchain_Integrity.ipynb` notebook in Google Colab.
2. Run the cells to create a simple blockchain and add document hashes to it.
3. Verify the integrity of documents using the blockchain ledger.

### Smart Document Search
1. Load the `Smart_Search.ipynb` notebook in Google Colab.
2. Run the cells to train the Word2Vec model on sample documents.
3. Perform context-aware searches and retrieve accurate search results.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes relevant tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
