# Task

The task is to classify word sense definitions into coarse semantic categories named "hypersenses".

In this project, the objective is to explore several ways of using LLMs for this task.

# Data

We will use a dataset of manually labeled word senses, adapted from (Barque et al., 2020).

These word senses were labeled with a "supersense", each supersense corresponding to a broader "hypersense".


# Classifiers

Comparing:

- a small LLM fine-tuned for instructions with in-context learning
- parameter-efficient fine-tuning of LoRA on the full training set


