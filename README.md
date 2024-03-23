# String Similarity Calculation Algorithm

This Python project implements a string similarity calculation algorithm inspired by the research paper:

 - **Title**: Representing character sequences as sets: A simple and intuitive string encoding algorithm for NLP data cleaning

 - **Authors**: Marinov, M., & Efremov, A.

 - **Published**: 2019 IEEE International Conference on Advanced Scientific Computing (ICASC)

The algorithm presented in the paper is utilized to encode character sequences into sparse tables, providing a foundation for string similarity comparisons. Below are some key features and real-world use cases of this algorithm:

## Key Features:

**Sparse Table Creation**: Converts input strings into sparse tables.

**Similarity Score Calculation**: Determines the similarity between two strings based on shared character pairs.

## Real-world Use Cases:

**Data Cleaning in NLP**: The algorithm aids in preprocessing textual data by identifying similar strings, which is crucial for tasks like spell checking, deduplication, and entity resolution.

**Search Operations**: Enhances search functionalities by identifying similar terms or phrases within a corpus, improving search result relevance and recall.

**Record Linkage**: Facilitates record linkage tasks by identifying similar records across different datasets, enabling data integration and consolidation.

## Getting Started:

**Installation**: Clone or download the repository to your local machine.

**Dependencies**: Ensure you have Python 3.x installed along with the required libraries mentioned in the project's requirements file.

**Usage**: Utilize the provided functions encode_string and similarity_score to encode strings and calculate their similarity scores, respectively.
