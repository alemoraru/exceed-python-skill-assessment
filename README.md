# EXCEED Python Skill Level Assessment

This repository holds **everything** needed to reproduce the analyses for the 2025 Qualtrics Python proficiency
assessment survey: the raw Qualtrics questionnaire, anonymised response data, Jupyter notebooks for cleaning / scoring,
and several miscellaneous files that were useful during the project.
It is one of several companion repositories for the upcoming paper within the EXCEED framework:
*"Learning-Enhanced Variable Error expLanations."*

The research that this repository supports is part of the EXCEED Master's thesis project by **Alexandru-Radu Moraru**
at Delft University of Technology, part of the **Web Information Systems** research group.

> **Note**: The goal of the Qualtrics survey was to find a better way to objectively assess Python proficiency, while
> centering questions around common errors, identification, resolution, and understanding, rather than general
> programming knowledge.

---

## Folder structure

```
├── data/
│   ├── processed/
│   ├── survey_answers.csv
│   └── survey_results.csv
├── notebooks/
│   ├── 00_high_level_analysis.ipynb
│   ├── 01_detailed_analysis.ipynb
│   ├── 02_visualisation.ipynb
│   └── requirements.txt
├── survey/
│   ├── old_md_versions/
│   ├── qualtrics_final_survey.qsf
│   ├── qualtrics_final_survey.pdf
│   └── ConsentFormPythonQualtricsEXCEED.pdf
└── misc/
```

* **data/** – Raw and cleaned survey data files. The `survey_results.csv` file contains the anonymised responses,
  while `survey_answers.csv` includes the raw answers with question IDs (the actual answers are label-encoded).
  Additionally, the `processed/` subfolder contains some intermediate data files used during the analysis, which are 
  also used for visualisation and scoring in the notebooks.
* **notebooks/** – Fully runnable notebooks that replicate every table, figure, and metric pertaining to the Qualtrics
  Python skill level assessment. The `requirements.txt` file lists the Python dependencies needed to run them.
* **survey/** – The exact question text (\*.qsf + printable PDF) plus the consent form used in the actual survey.
  The `old_md_versions/` folder contains previous Markdown versions of the survey text, which may be useful for
  historical reference.
* **misc/** – Some miscellaneous files that were useful during the project. These ought to be ignored.

---

## Qualtrics survey block composition

| Block ID     | Question IDs | Theme / purpose                                                                                                                           |
|--------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| **Block 1**  | Q1.1         | Welcome, consent & study briefing                                                                                                         |
| **Block 2**  | Q2.1–Q2.3    | Background & experience (Python experience using Dreyfus model, Python YoE, general programming YoE)                                      |
| **Block 3**  | Q3.1–Q3.7    | **General Programming Error Understanding** (i.e., not necessarily Python-specific questions)                                             |
| **Block 4**  | Q4.1–Q4.7    | **Python-specific General Error Understanding** (i.e., covering high-level Python error aspects)                                          |
| **Block 5**  | Q5.1–Q5.7    | **Error Identification** (i.e., given a snippet of code, identify the error)                                                              |
| **Block 6**  | Q6.1–Q6.7    | **Error Resolution** (i.e., given a problematic code snippet, find the right fix)                                                         |
| **Block 7**  | Q7.1–Q7.7    | **Code Reading/Understanding** (i.e., given some code, attempt to understand whether it does what it's intended to do)                    |
| **Block 8**  | Q8.1–Q8.7    | **Error Message Comprehension** (i.e., given an error message and no code, try to understand the underlying issue)                        |
| **Block 9**  | Q9.1–Q9.7    | **Natural Language Scenarios** (i.e., given a hypothetic scenario with no code or error message, try to understand the most likely issue) |
| **Block 10** | Q10.1–Q10.7  | **Various Complexity & Scope** (i.e, a mix of several aspects of potentially higher difficulty)                                           |
| **Block 11** | Q11.1        | Self‑assessment – "How many survey questions do you think you answered correctly?" (0-16)                                                 |

> **Notes:**
> * Only Blocks 3–10 are scored; Blocks 2 and 11 feed the experience/confidence covariates used in the analysis.
> * The questions within blocks 3-10 are randomised for each participant (2 questions per block, 8 blocks total).
> * The answer choices to each question are also randomised to avoid choice bias, guessing, or cheating.

---

## Running the notebooks

1. **Clone or fork** the repo

   ```bash
   git clone https://github.com/alemoraru/exceed-python-skill-assessment.git
   cd exceed-python-skill-assessment
   ```
2. **Create a fresh Python ≥3.12 environment** (virtualenv or conda)

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   cd notebooks
   ```
3. **Install dependencies (Optional)**

   ```bash
   pip install -r requirements.txt
   ```

   This step is optional, since each notebook will run `pip install -r requirements.txt` as the first step.

4. **Launch Jupyter** and run the notebooks top‑to‑bottom

   ```bash
   jupyter lab 00_high_level_analysis.ipynb
   jupyter lab 01_detailed_analysis.ipynb
   jupyter lab 02_visualisation.ipynb
   ```
   Alternatively, you can of course run the notebooks within VS Code or any other Jupyter-compatible IDE
   (e.g., PyCharm).

---

## Licensing

| Component                                                       | License                     |
|-----------------------------------------------------------------|-----------------------------|
| Jupyter notebooks (`/notebooks`) & derived data files (`/data`) | **MIT**                     |
| Original Qualtrics survey text (`/survey`)                      | **Creative Commons BY 4.0** |

You are free to reuse/modify the code and anonymised data with attribution. If you quote or adapt the survey items,
please credit the original authors as per the CC‑BY 4.0 terms.
