# Job Interview Guide Workshop

## Overview

This team exercise uses an AI-assisted interview to review core machine learning concepts and identify areas for further practice. Each participant completes an individual interview and uses the feedback to generate a personalized Jupyter Notebook with explanations, coding exercises, and reflection prompts.

## Team Contributions

This repository brings together the work created by our teammates for the Job Interview Guide Workshop. Each team member completed their own AI-assisted interview session and uploaded their generated notebook to the repository. The notebooks reflect each member’s individual quiz results and learning needs, while contributing to our shared review of machine learning concepts.

The personalized notebooks were generated with LLM assistance as required by the exercise. Team members contributed their interview responses, individual notebooks, and learning reflections.

## Learning Objectives

- Explain supervised and unsupervised learning, features, and target variables.
- Use training, validation, and test sets appropriately and recognize data leakage.
- Interpret linear and logistic regression models and their evaluation metrics.
- Compare KNN hyperparameters and understand decision tree predictions.
- Discuss model selection, overfitting, class imbalance, and practical trade-offs.
- Use interview feedback to guide further study and document learning through reflection.

## Exercise Workflow

1. Collect the course workshop notebooks in `StudyMaterials.zip` and prepare `StudyGuide.txt`.
2. Provide both files to an LLM acting as an ML Specialist interviewer.
3. Generate a 500-word workshop summary, a 100-word study guide summary, and a topic coverage and gaps table.
4. Complete 15 multiple-choice questions, presented one at a time, covering technical and scenario-based topics.
5. Receive a score and generate a personalized study notebook focused on incorrect answers.
6. Record results, review the generated explanations, complete targeted exercises, and write a reflection.
7. Save the full LLM conversation in `JobInterviewLLMSession.ipynb` and submit the required notebooks to the repository.

## Notebook Content

The workshop notebook provides the interview instructions, coverage review, reflection, and targeted practice in three areas:

| Practice area | Main activities |
|---|---|
| Data splitting and leakage | Create stratified train/validation/test splits, compare scaling approaches, and evaluate accuracy and cross-entropy. |
| Linear and logistic regression | Fit models to synthetic datasets, inspect residuals, interpret coefficients, and calculate regression and classification metrics. |
| KNN and decision trees | Compare neighbor counts and distance metrics, visualize validation performance and tree structure, and examine model complexity. |

Each member’s generated study notebook supplements this common exercise with practice tailored to their interview results. Individual scores and weak topics may differ.

## Files Used in the Exercise

| File | Purpose |
|---|---|
| `JobInterviewGuide_Workshop.ipynb` | Workshop instructions, recorded results, reflection, and coding practice. |
| Team members’ generated notebooks | Personalized explanations and exercises based on individual interview feedback. |
| `JobInterviewLLMSession.ipynb` | Required record of the complete LLM interview session. |
| `StudyGuide.txt` | Course topics used to guide the interview. |
| `StudyMaterials.zip` | Reference workshop notebooks used for the content review. |

The table describes the exercise files and deliverables; individual notebook filenames may vary across team submissions.

## Running the Exercises

Use Python 3 with Jupyter Notebook or VS Code with the Python and Jupyter extensions. Install the packages used by the supplied workshop notebook in your selected environment:

```bash
python -m pip install numpy pandas matplotlib scikit-learn jupyter ipykernel
```

Open the notebook, select the Python environment containing these packages, and run the cells from top to bottom. Complete any TODOs and written responses, then save the notebook with its outputs. Review each personalized notebook for any additional requirements.

The supplied coding exercises use scikit-learn datasets and synthetic data. `StudyGuide.txt` and `StudyMaterials.zip` are needed for the material-review workflow and optional local checks. The notebook’s header image uses the relative path `images/OnlineJobInterview.png`; a missing image does not prevent the Python exercises from running.

## Assessment

| Component | Weight |
|---|---:|
| Quiz performance | 40% |
| Generated study notebook quality | 40% |
| Reflection | 20% |

The reflection addresses challenging concepts, overlooked assumptions or trade-offs, and a practical improvement plan. Generated explanations and code should be checked for correctness before being used as study material or submitted.
