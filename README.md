# 💭🧪  DocuMerge for LLMs 

 **Easily prepare GitHub or other Repos for AI LLM training**

Are you trying to train an LLM to analyze a GitHub repository or similar? Instead of manually extracting every single file and organizing it into a document, let **DocuMerge for LLMs** do the heavy lifting for you! This Python script consolidates all files in a repository into **2 neatly organized text files** that are optimized for LLM analysis. 

This Python script transforms an entire GitHub repository into a single text file optimized for LLM training, while simultaneously generating a secondary "insights" text file containing a structured analysis of the codebase. The dual-output approach ensures you can train your LLM model on complete code contents (if within token limitations), but still leverage the smaller summary file when token limits are exceeded for guidance from your LLM during your Vibe Coding session. 

<img src="Insights Wizard.jpg" alt="DocuMerge Wizard" width="400">

---

## 🧙‍♂️ What Does It Do?

## 📜 Features of the Script

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

## ⚗️  Why Use DocuMerge for LLMs?

- **Save Time**: No need to manually extract and organize files.
- **Simplify Analysis**: Provide LLMs with a single, well-organized `.txt` file and a concise insights file.
- **Improve Workflow**: Focus on training and analyzing, not file management.


## 🪄 How to Use It (Step-by-Step)

1. **Download the Repository**:
   - Clone or download the GitHub repository you want to analyze.
   - Unzip the folder if it’s a `.zip` file.

2. **Download the Script**:
   - Save the `documerge_for_llms.py`
     
3. **Run the Script**:
   - Simply double-click the documerge_for_llms.py file to launch a GUI (compatible across Windows, Linux, and macOS). The clean interface guides you through selecting any repository you wish to analyze.

For best organization, I recommend placing your target repository in a dedicated parent folder first, as DocuMerge generates its output files in the same directory where it runs. This keeps your magical AI-ready documentation neatly contained alongside your source code.

4. **Wait for the Magic**: 

   - The script will process the repository and generate **two output files**:
     - `LLM-DocuMerge_<RepoName>.txt`: A large file containing all the repository files.
     - `LLM-DocuMerge-Insights_<RepoName>.txt`: A smaller file with detailed insights about the repository.




 ~ By Jesse Ellis - Director of Corporate Development - BPOSeats.com, the largest seat leasing and office Provider in the Phillipines - Message hello@bposeats.com if you are interested in outsourcing (pay your agents directly, rent the space - reduce costs by 60%+), AI Consultancy by yours truly, or any Tech Stacks

#repository-analyzer #code-merger #llm-context-builder #dependency-extractor #directory-structure-analyzer #code-statistics-generator #repository-insights #file-consolidation #codebase-documentation #function-extractor #class-analyzer #file-size-tracker #keyword-analyzer #language-distribution #code-summarizer #llm-optimization #repository-documentation #codebase-merger #code-documentation-generator #ai-assistant-helper
