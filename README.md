# 🌟 DocuMerge for LLMs 🌟 ~ By Jesse Ellis with CloudPotions.com 

🚀 **Easily prepare GitHub repositories for LLM analysis!**

Are you trying to train an LLM to analyze a GitHub repository or similar? Instead of manually extracting every single file and organizing it into a document, let **DocuMerge for LLMs** do the heavy lifting for you! This Python script consolidates all files in a repository into **two output files** that are perfect for LLM analysis.

---

## 🧠 What Does It Do?

The **DocuMerge for LLMs** script performs the following tasks:
1. **Merges All Files**: Combines all files in the repository (including subfolders) into a single `.txt` file, with each file separated by its name as a section header.
2. **Generates Insights**: Creates a second, smaller `.txt` file that provides a detailed overview of the repository, including:
   - Technologies and dependencies used.
   - Directory structure.
   - Key files and their comments or docstrings.
   - Code statistics (lines of code and file sizes).
   - Largest files by lines of code.
   - Functions and classes in Python files.
   - Frequently used keywords in the codebase.
   - A summary of the `README.md` file (if available).
   - Any issues encountered during processing.

---

## ✨ Why Use DocuMerge for LLMs?

- **Save Time**: No need to manually extract and organize files.
- **Simplify Analysis**: Provide LLMs with a single, well-organized `.txt` file and a concise insights file.
- **Improve Workflow**: Focus on training and analyzing, not file management.
- **Comprehensive Insights**: The second file provides a detailed breakdown of the repository, making it easier for LLMs to understand the codebase.

---

## 🛠️ How to Use It (Step-by-Step for Dummies)

1. **Download the Repository**:
   - Clone or download the GitHub repository you want to analyze.
   - Unzip the folder if it’s a `.zip` file.

2. **Download the Script**:
   - Save the `documerge_for_llms.py` script into the root folder of the repository you just downloaded.

3. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the folder where the repository and script are located.
   - Run the script using Python:
     ```
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
