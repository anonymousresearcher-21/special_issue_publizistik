# Snapshot of Experiment Results – 14 August 2025

This repository contains a frozen snapshot of experiment outputs from 14 August 2025, submitted alongside the abstract for the Special Issue of "Publizistik".
It serves as a record of the state of the experiments at that date.

Important notes:

- This repository does not include data preprocessing steps or the extensive setup work required to make the data processable.

- It is not updated regularly and may not reflect the latest results.

- The contents are intended for reference and verification purposes only.


## Experiments Directory Overview

This directory contains a systematic evaluation of Large Language Models (LLMs) for automated abstract screening in systematic literature reviews. The research investigates how well GPT-4o can replicate human screening decisions across different prompt configurations and output formats.


### 📁 Directory Structure

/notebooks/ - Contains the Jupyter notebooks executing the actual systematic LLM experiments with different prompting strategies and output formats for abstract screening.

/results/ - Stores the master experiment summary CSV with performance metrics and individual result files for each experiment run.

/data/ - Contains the two manually labeled datasets with ground truth classifications for systematic review screening.

/prompts/ - Houses the inclusion/exclusion criteria definitions and few-shot example abstracts used across different experimental conditions.

/preperation/ - Contains 5 preprocessing notebooks for data cleaning, criteria standardization, and example selection before running experiments.
