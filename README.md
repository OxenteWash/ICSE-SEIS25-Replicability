# Replicability Package

This repository includes the replicability package of the paper _A Bot-based Approach to Manage Codes of Conduct in Open-Source Projects_, accepted at the ICSE 2025 Software Engineering in Society (SEIS) track.

The repository contains two main folders:
* `coc_analysis`: contains the data and analysis of the codes of conduct of the paper, including the dataset of codes of conduct.
* `proof_of_concept`: contains the comments used in the proof of concept of the tool (see Section V.C of the paper).

## `coc_analysis` folder

This folder contains the data and scripts used to report the results of the study of codes of conduct in open-source projects. Please refer to the file `coc_analysis/README.md` for more information on how to run the scripts and reproduce the results.

The folder contains the following files:

* `data`: This folder contains the code of conduct collected from the 1,000 top-starred repositories for 12 different programming languages (i.e., C, C++, C#, Go, Java, JavaScript, PHP, Python, Ruby, Rust, Scala, and TypeScript). The code of conduct was collected in June 2024 (see Section III.A of the paper)..
* `coc_analysis.ipnb`: This Jupyter notebook contains the code used in the study of codes of conduct in open-source projects (see Section III of the paper).
* `config.json`: This JSON file contains configuration data for the Jupyter notebook, including the keywords used to identify the presence of each ethical flags. (see Section III.B of the paper).
* `requirements.txt`: This Jupyter notebook contains the code used to analyze the flags found in the codes of conduct of our dataset (see Section III.C of the paper).

## `proof_of_concept` folder

This folder contains the comments used in the proof of concept of the tool (see Section V.C of the paper).

* `comments.json`: This JSON file contains the comments used in the proof of concept.

