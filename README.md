# README

## Assignment: Motivational Text Generation using GPT-2 and BERTScore Evaluation

### Description
This assignment explores prompt engineering by generating motivational text using the GPT-2 language model. The goal is to design diverse prompts, generate motivational outputs from GPT-2, collect a human-written motivational reference, and evaluate the quality of GPT-2 outputs against this reference using BERTScore.

### Contents
- **Prompt Design:** Five distinct prompt types were created to instruct GPT-2 to generate motivational quotes or content.
- **Text Generation:** For each prompt, three different motivational outputs were generated using GPT-2.
- **Human Reference:** A human-written motivational quote was collected as a reference for evaluation.
- **Evaluation:** BERTScore was used to compute semantic similarity between GPT-2 outputs and the human-written reference.
- **Results:** BERTScore scores were tabulated and analyzed to compare the effectiveness of different prompt styles.

### Files
- `notebook.ipynb`: Jupyter notebook containing code for prompt design, text generation, and BERTScore evaluation.
- `prompts.txt`: List of the five designed prompts.
- `outputs.txt`: All 15 GPT-2 generated outputs (3 per prompt).
- `human_reference.txt`: The human-written motivational quote used as reference.
- `bert_score_results.txt`: Table with BERTScore F1 scores for each generated output.
- `README.md`: This file, providing an overview of the assignment and contents.

### How to Run
1. Install required packages:


2. Run the notebook `notebook.ipynb` to:
- Load GPT-2 model.
- Generate outputs using the designed prompts.
- Calculate BERTScore against the human-written reference.
3. Review the outputs and evaluation scores in the notebook or in the respective text files.

### Notes
- Ensure you have an internet connection to download the GPT-2 model initially.
- BERTScore requires a GPU for faster computation but can run on CPU as well.
- The prompts are designed to test different styles such as direct instruction, scenario-based, persona-based, keyword-based, and conversational.
