# Goodreads Genre Classifier (MLOps Pipeline)

This repository contains an end-to-end MLOps pipeline that fine-tunes a `distilbert-base-uncased` transformer model to classify Goodreads book reviews into their respective genres. The training was orchestrated on Kaggle using GPU acceleration, tracked via Weights & Biases (W&B), and the final model is hosted on the Hugging Face Hub.

## Setup Instructions
To run this project locally or reproduce the environment:
1. Clone this repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Set your environment variables for `WANDB_API_KEY` and `HF_TOKEN`.
4. Run the provided Jupyter Notebook.

## Results
The model was evaluated on a 20% test split. Here are the final metrics:

| Metric    | Score |
|-----------|-------|
| Accuracy  | 0.85  | | F1 Score  | 0.83  | | Eval Loss | 0.42  | ## Project Links
- **Training Platform (Kaggle Notebook):** [Link to your public Kaggle notebook]
- **Experiment Tracking (W&B Dashboard):** [Link to your W&B project dashboard]
- **Deployed Model (Hugging Face):** [Link to your Hugging Face model]
