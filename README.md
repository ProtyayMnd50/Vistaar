# **Vistaar**: A Semantic Search-Based  E-commerce Product Search

## Project Overview

This project aims to solve two key challenges using **Elasticsearch** and **vector embeddings** for semantic search:

1. **Efficient Project Assignment**: In a college setting, assigning government-sanctioned projects to the most suitable students based on their technical skills and experience is often inefficient. By using semantic search with vector embeddings, this project automates the assignment process, ensuring that projects are allocated to the best-fit students by analyzing their skills and previous work.

2. **Enhanced E-commerce Product Search**: Traditional search engines in e-commerce platforms often rely on exact keyword matches, which limits the search results. For instance, searching for "footwear" might miss relevant items like "shoes." By integrating semantic search, this project improves the user experience by understanding the context of search terms and providing more relevant results.

## Tech Stack

- **Elasticsearch**: The core search engine used to perform fast and scalable full-text and vector-based searches. It supports both structured and unstructured data indexing.
- **Python**: Used to build the backend that integrates with Elasticsearch and processes the data.
- **Vector Embeddings**: Representations of text and data that allow for semantic similarity search rather than just keyword-based matching.
- **Streamlit** (for Travel Itinerary Generator): Used for developing the front-end interface for applications, including real-time data visualization and search interactions.

## Advantages of Using Semantic Search

- **Improved Accuracy**: By leveraging vector embeddings, the search engine can understand the intent behind a query rather than just matching exact keywords, leading to more accurate results.
  
- **Contextual Understanding**: Semantic search can identify and retrieve relevant documents or products even when different terms are used (e.g., "footwear" and "shoes"), ensuring a better user experience in e-commerce platforms.

- **Automated Project Matching**: For academic purposes, the system ensures that government-sanctioned projects are assigned to the most suitable students, reducing manual effort and increasing precision in student-project matching.

- **Scalability**: Elasticsearch is designed to scale with data, making it ideal for large datasets like a catalog of student profiles or e-commerce products.

## Installation and Setup

1. **Install Python and Pip**:
   Make sure Python is installed, and Pip is available for package management.
   
   ```bash
   sudo apt-get install python3
   sudo apt-get install python3-pip

2. **Configure Elasticsearch**:
- Download and Install Elasticsearch

    Download Elasticsearch from the official website: Elasticsearch Download

    Install Elasticsearch on your local machine or server by following the installation guide for your OS.

- Ensure Elasticsearch is Running

Once installed, ensure Elasticsearch is running by executing the following command:
```bash
# On Linux / MacOS
./bin/elasticsearch

# On Windows
bin\elasticsearch.bat
```

After starting, you can verify it's running by visiting http://localhost:9200 in your web browser. You should see a response with information about your Elasticsearch node.

3. **Running the Project**:

   - Activate Virtual Environment

    Before starting the project, make sure you  have a virtual environment activated. You can do this using the following commands:

# On Linux / MacOS
```bash source venv/bin/activate```

# On Windows
```bash venv\Scripts\activate```

If you don't have a virtual environment set up, you can create one by running:

```python python -m venv venv```
