# 🌟 DocuMerge for LLMs 🌟 ~ By Jesse Ellis with CloudPotions.com - Director of Corporate Development - BPO Seats, the largest seat leasing and office Provider in the Phillipines - Message hello@bposeats.com if you are interested in outsourcing, AI Consultancy by yours truly, or any Tech Stacks

In summary, this Python script  consolidates a Github repository into one text file to train an LLM model, and also generates a comprehensive analysis of the codebase in a structured insights file. This allows training an LLM on the contents and high-level structure/characteristics of the repository.

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

## 📜 Example Output Files

### 1. **LLM-DocuMerge_<RepoName>.txt**
This file contains all the files in the repository, separated by their names. For example:


### 2. **LLM-DocuMerge-Insights_<RepoName>.txt**
This file provides a detailed overview of the repository. For example:


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

1. Clone this repository or download the script.
2. Save it in the same directory as the repository you want to analyze.
3. Run the script using Python:
   ```bash
   python documerge_for_llms.py
