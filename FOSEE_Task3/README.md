TITLE:

Evaluating Open Source Models for Student Competence Analysis

RESEARCH PLAN:

In this task, I planned to explore how AI models support students’ competency in Python learning. My approach towards the given task will begin by identifying the freely available language models and analytical frameworks. I will briefly go through them and shortlist the models that are apt to proceed for the problem statement.

To ensure the suitability of the model, I will work temporarily with a sample dataset of Python code with common errors and will use it with the chosen model to check the ability of the model in analyzing the student’s code, generating prompts or feedback that add value for the reasoning gaps, and whether the model provides reflective questions instead of direct fixes.

REASONING:

A model is selected for high-level competence analysis if it can perform well in detecting syntax errors and actually uncover conceptual misunderstandings. To ensure this, I will compare the model-generated prompts with teacher-provided hints. Other factors which are worthy to consider while choosing a model are interpretability, cost, and accuracy.

Keeping all the aspects in consideration, I chose CodeBERT because it is trained on large code datasets and is freely available. The strength of CodeBERT lies in code understanding, but it has limitations too: it might not naturally generate prompts, which may require fine-tuning or prompt engineering.
