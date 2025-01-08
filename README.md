# Search Engine Project

## Overview
This project implements a basic search engine using various technologies and file types including `.r`, `.html`, `.sh`, `.cpp`, and `.h`. The goal is to create an efficient and simple search engine that can process and search through a collection of documents.

## Technologies Used
- **.r**: Scripts for data analysis and text processing, using the R programming language.
- **.html**: Frontend files to display search results and provide a user interface for interacting with the search engine.
- **.sh**: Shell scripts for automating tasks like indexing documents or running the search engine.
- **.cpp**: C++ code for the backend of the search engine, implementing the core search logic.
- **.h**: C++ header files to define functions and data structures used in the `.cpp` files.

## File Descriptions
### 1. `indexer.sh`
- **Purpose**: Automates the process of indexing documents and preparing them for search.
- **Functionality**: Collects documents, parses them, and creates an index for quick lookups.

### 2. `searchEngine.cpp`
- **Purpose**: Implements the main search engine algorithm.
- **Functionality**: Takes user queries and matches them with indexed data to return relevant results.

### 3. `searchEngine.h`
- **Purpose**: Header file that defines key data structures and function prototypes used in the `searchEngine.cpp` file.
- **Functionality**: Contains declarations for classes and functions that form the core of the search engine.

### 4. `userInterface.html`
- **Purpose**: Provides the frontend interface for users to input search queries and view results.
- **Functionality**: A simple web page with an input form for users to enter search terms and a results section to display the findings.

### 5. `dataProcessing.r`
- **Purpose**: Processes text data and performs any necessary analysis or filtering before indexing.
- **Functionality**: Uses R scripts for tasks like removing stopwords or stemming words to improve search accuracy.

## Setup Instructions

### Prerequisites
1. **C++ Compiler** (e.g., GCC or Clang) for compiling C++ files.
2. **R** for running the `dataProcessing.r` script.
3. **Web Browser** for interacting with the `userInterface.html`.
4. **Bash** for running the shell scripts.

### Steps to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/search-engine.git
   cd search-engine

Contributing
Feel free to fork this repository, submit issues, and open pull requests if you would like to contribute to improving the search engine.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The project was inspired by various search engine algorithms and data processing techniques.
