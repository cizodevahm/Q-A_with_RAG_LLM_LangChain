# Q-A_with_RAG_LLM_LangChain
This project utilizes LangChain to process and analyze PDF documents for question-answering tasks. The primary functionality is to split, index, and query the text within PDF files to provide accurate and context-rich answers to user queries.

## LangChain
LangChain is a powerful framework designed to build applications that harness the capabilities of Large Language Models (LLMs) by integrating them with external data sources, APIs, and custom workflows. It provides tools for easy management of prompt engineering, document retrieval, and chain logic, enabling developers to create sophisticated applications like chatbots, question-answering systems, and more, with minimal effort.

## Features
- **Text Splitting**: Efficiently splits text from PDF documents into manageable chunks for better indexing and querying.
- **Indexing**: Creates an index from the split text to optimize search and retrieval.
- **Question-Answering**: Allows users to ask questions about the content of PDF files and receive detailed responses based on the indexed data.

## Prerequisites
- Python
- OpenAI API key
- LangChain
- OpenAI

## Setup
```bash
git clone https://github.com/cizodevahm/Q-A_with_RAG_LLM_LangChain.git
```

## Usage
- **Running the Notebook**: Open the Jupyter notebook Langchain_pdf_Q&A.ipynb and run all cells to process a PDF file and interact with the question-answering functionality.
- **Customization**: Modify the text splitting and querying logic within the notebook to tailor the system to specific needs or document structures.

## Known Issues
- Responses may sometimes be cut off due to text splitting and querying configurations. Adjust the splitting parameters to improve response completeness.

## Future Improvements
- Enhance the splitting logic to better handle different document formats.
- Improve indexing efficiency for faster query responses.
- Add a graphical user interface (GUI) for easier interaction with the system.

## License
- This project is licensed under the GPL-3.0 license.
