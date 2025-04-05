# 🌟 DocuMerge for LLMs 🌟

 ~ By Jesse Ellis - Director of Corporate Development - BPOSeats.com, the largest seat leasing and office Provider in the Phillipines - Message hello@bposeats.com if you are interested in outsourcing, AI Consultancy by yours truly, or any Tech Stacks

This Python script transforms an entire GitHub repository into a single text file optimized for AI LLM training, while simultaneously generating a compact "insights" file containing structured analysis of the codebase. The dual-output approach ensures you can train your LLM model on complete code contents (when possible), but still leverage the smaller summary file when token limits are exceeded. This elegant solution allows LLMs to understand both the detailed implementation and high-level architecture of complex repositories.

------------
AI CONSULTANCY - Programming the LLM for a Github Repo Analysis

Code Repository Consolidation Framework for Advanced LLM Training
This Python implementation provides a sophisticated approach to transforming disparate repository components into optimal LLM training artifacts. The solution operates on a dual-output paradigm:

Comprehensive Repository Amalgamation: The script synthesizes an entire codebase (GitHub or alternative version control platforms) into a unified text corpus, creating a holistic representation for thorough model comprehension.
Token-Optimized Intelligence Layer: Recognizing the computational constraints of context windows, the framework simultaneously generates a condensed "insights" artifact that captures the essential architectural patterns, dependency relationships, and structural characteristics of the source material.This methodology ensures maximum knowledge transfer while maintaining token efficiency. The secondary artifact serves as a fallback intelligence source when token limitations prevent full corpus ingestion, allowing models to maintain high-level understanding of the codebase's architecture even when detail resolution must be sacrificed.
The implementation is particularly valuable for fine-tuning specialized models on proprietary codebases or creating domain-specific agents with deep understanding of technical ecosystems without the computational overhead of token-saturated contexts.
--------------

# 🌟 DocuMerge for LLMs 🌟

🚀 **Easily prepare GitHub repositories for AI LLM analysis!**

Are you trying to train an LLM to analyze a GitHub repository or similar? Instead of manually extracting every single file and organizing it into a document, let **DocuMerge for LLMs** do the heavy lifting for you! This Python script consolidates all files in a repository into **two output files** that are perfect for LLM analysis.

---

## 🧠 What Does It Do?

The **DocuMerge for LLMs** script performs the following tasks:

1. **Merges All Files**: Combines all files in the repository (including subfolders) into a single `.txt` file, with each file separated by its name as a section header.
2. **Generates Insights**: Creates a second, smaller `.txt` file that provides a detailed overview of the repository, including:
   - **Technologies and Dependencies**: Lists libraries and frameworks used in the codebase.
   - **Directory Structure**: Provides a tree-like view of the repository's organization.
   - **Key Files and Their Roles**: Summarizes important files and their comments or docstrings.
   - **Code Statistics**: Counts lines of code and file sizes for each file.
   - **Largest Files by Lines of Code**: Identifies the largest files in the repository.
   - **Functions and Classes**: Extracts all functions and classes from Python files.
   - **Keywords**: Highlights frequently used terms in the codebase.
   - **Language Distribution**: Breaks down the repository by programming language and shows the contribution of each language.
   - **README Summary**: Summarizes the content of the `README.md` file (if available).
   - **Issues**: Logs any errors encountered during processing.

---

## ✨ Why Use DocuMerge for LLMs?

- **Save Time**: No need to manually extract and organize files.
- **Simplify Analysis**: Provide LLMs with a single, well-organized `.txt` file and a concise insights file.
- **Improve Workflow**: Focus on training and analyzing, not file management.
- **Comprehensive Insights**: The second file provides a detailed breakdown of the repository, making it easier for LLMs to understand the codebase.

---

## 🛠️ How to Use It (Step-by-Step)

1. **Download the Repository**:
   - Clone or download the GitHub repository you want to analyze.
   - Unzip the folder if it’s a `.zip` file.

2. **Download the Script**:
   - Save the `documerge_for_llms.py` script into the root folder of the repository you just downloaded.

3. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the folder where the repository and script are located.
   - Run the script using Python:
     ```bash
     python documerge_for_llms.py
     ```

4. **Wait for the Magic**:
   - The script will process the repository and generate **two output files**:
     - `LLM-DocuMerge_<RepoName>.txt`: A large file containing all the repository files.
     - `LLM-DocuMerge-Insights_<RepoName>.txt`: A smaller file with detailed insights about the repository.

5. **Use the Output Files**:
   - Use the output files to train an LLM to understand, modify, or improve the repository.

---

## 📜 Output Files

### 1. **LLM-DocuMerge_<RepoName>.txt**
This file contains all the files in the repository, separated by their names. 


### 2. **LLM-DocuMerge-Insights_<RepoName>.txt**
This file provides a detailed overview of the repository. 


---

## 🎉 Features of the Script

1. **Handles Folders and Subfolders**: Automatically traverses the entire directory structure.
2. **Organized Output**: Each file's content is labeled with its name for clarity.
3. **Technologies and Dependencies**: Extracts `import` and `require` statements to identify libraries and frameworks used.
4. **Directory Structure**: Generates a tree-like view of the repository.
5. **Key Files and Comments**: Extracts comments and docstrings from Python files.
6. **Code Statistics**: Counts lines of code and file sizes for each file.
7. **Largest Files**: Identifies the largest files by lines of code.
8. **Functions and Classes**: Extracts all functions and classes from Python files.
9. **Keywords**: Highlights frequently used terms in the codebase.
10. **Language Distribution**: Breaks down the repository by programming language.
11. **README Summary**: Summarizes the content of the `README.md` file (if available).
12. **Error Handling**: Logs any issues encountered during processing.

---

## 📥 Installation and Usage

1. Clone this repository or download the python script (DocuMerge-for-LLMs.py)
2. Save it in the same directory as the repository you want to analyze.
3. Run the script by opening the python script in the same folder as the Github Repo or on command line using Python:
   ```bash
   python documerge_for_llms.py
