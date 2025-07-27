# p7_web_compare

[P7: Custom Final Project: Web Mining & NLP](https://github.com/Data-Git-Hub/p7_web_compare)

## Introduction
In this project, I explore the fundamentals of web scraping and natural language processing (NLP) using Python within a Jupyter Notebook environment. The primary objective is to extract textual data from web sources and perform basic NLP tasks to analyze and interpret that data. This includes using libraries such as `requests` to fetch web content, `BeautifulSoup` to parse HTML, and `spaCy` with `spacytextblob` to process and analyze text for sentiment, subjectivity, and linguistic patterns.

Web scraping is an essential skill in data analytics and business intelligence, enabling analysts to gather real-time or hard-to-find data from public web pages. NLP extends this capability by allowing us to interpret the collected text, uncover hidden insights, and support data-driven decision-making. Together, these skills allow for scalable and automated information extraction that can inform strategy, research, and communication analysis.

This project also demonstrates effective use of Python virtual environments, version control with GitHub, and professional documentation practices. All code has been executed prior to submission, and final versions have been exported to HTML to ensure accessibility and review readiness. The final submission includes code, outputs, visualizations, and reflections on the process.

/// Add text about comparing two different webpages ///

## Tasks

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

---

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

### spaCy and textblob Model Installation Note for Windows

```shell
python -m spacy download en_core_web_sm
python -m textblob.download_corpora
```
---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### spaCy and textblob Model Installation Note for macOS/Linux

```shell
python3 -m spacy download en_core_web_sm
python3 -m textblob.download_corpora
```
---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

### Introduction

### Imports

### Tasks

### Section 1. Extract and Save Article HTML

### Section 2. Load and Display Article Text

### Section 3. Analyze Most Frequent Tokens with spaCy

### Section 4. Analyze Most Frequent Lemmas with spaCy

#### Section 4.1. Comparison Between Tokens and Lemmas

### Section 5. Score Sentences by Token and Lemma Frequency

#### Section 5.1. Interpretation of Sentence Scoring

### Section 6. Sentence Token Scores Histogram

### Section 7. Sentence Lemma Scores Histogram

#### Section 7.1. Token vs Lemma Score Comparison Plot

#### Section 7.1.1: Interpretation of Token vs Lemma Score Distributions

### Section 8. Filtering for Nouns Only

#### Section 8.1. Comparison Between Noun Tokens and Lemmas

#### Section 8.2. Score Sentences by Noun Token and Lemma Frequency

#### Section 8.3. Sentence Noun Token Scores Histogram

#### Section 8.4 Sentence Noun Lemma Scores Histogram

#### Section 8.4.1. Noun Token vs Lemma Score Comparison Plot

#### Section 8.4.2. Interpretation of Noun Token vs Lemma Score Comparison Plot

### Conclusion

---

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- 
- P7 Sect - 1.0 - Modify web_compare.ipynb
- P7 Init - 0.3 - Modify README.md
- P7 Init - 0.2
- P7 Init - 0.1 - Create web_compare.ipynb; Modify README.md, requirements.txt
- P7 Init - 0.0 - Create requirements.txt; Modify README.md
## Test History