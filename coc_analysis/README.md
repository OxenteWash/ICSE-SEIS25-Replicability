# **Replicability Package for Code of Conduct Analysis**

This **Replicability Package** accompanies our study on analyzing **Code of Conduct (CoC)** files across repositories in different programming languages. It provides all the necessary data, scripts, and instructions to replicate the results presented in our research.

---

## **Overview**
This package includes:
- **Scripts**:
  - Detecting and analyzing **CoC presence**, content, and alignment with **Contributor Covenant** (covered in **Table I**).
  - Computing the freshness of CoC files using the `f_coc` metric (analyzed in **Figure 1**).
  - Extracting ethical flags based on predefined patterns (covered in **Table II**).

- **Data**:
  - **`code_of_conduct_files.zip`**: ZIP file with the directories for different programming languages, each with repositories and their corresponding Code of Conduct files (e.g., `CODE_OF_CONDUCT.md`).
  - **`input/last_mod_coc.csv`**: Metadata file storing information such as the last modification date, creation date, and last commit date of repositories.

Each of these analyses is covered in dedicated sections within the Jupyter Notebook, allowing for seamless execution and replication.

---

## **Requirements**
The project is implemented in Python and uses the following libraries:
- **`pandas`**: For data manipulation and analysis.
- **`nltk`**: For Natural Language Processing, including text cleaning and flag detection.

To install dependencies, use the following command:
```bash
pip install -r requirements.txt

```

### **Execution Instructions**
To replicate the analysis, follow these steps:

1. Open the Jupyter Notebook file: **`coc_analysis.ipynb`**.
2. From the Jupyter Notebook menu, click on **"Run All"**.
3. Ensure that:
   - All dependencies are installed using the provided `requirements.txt`.
   - The required data files are located in the `data/` directory.

This process will execute all the cells sequentially, reproducing the entire workflow and generating the expected outputs.

---