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
| Accuracy  | 0.608 | 
| F1 Score  | 0.609 | 
| Eval Loss | 2.207 | 


## Project Links
- **Training Platform (Kaggle Notebook):** https://www.kaggle.com/code/rahulsolankijodhpur/mlops-assignment2
- **Experiment Tracking (W&B Dashboard):** https://wandb.ai/rahul_solanki-prom-iit-rajasthan/mlops-assignment2/reports/Untitled-Report--VmlldzoxNzAzMjMxNg?accessToken=9mupvcl2m1pv1880ermqah87zpq3p55almasuc3eii1bca2msfmla4p463x2gbz8
- **Deployed Model (Hugging Face):** https://huggingface.co/rahul-solanki/distilbert-goodreads-genres
