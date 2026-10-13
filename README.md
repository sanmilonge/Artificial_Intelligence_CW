# AI Coursework: Abstractive Text Summarisation with BART

This project is a university coursework submission for an Artificial Intelligence module. It explores the use of a transformer-based language model for automatic text summarisation using the XSum dataset.

## Project Aim

The goal of this coursework is to build and evaluate a summarisation system that can generate concise, informative summaries from long-form news articles. The project focuses on abstractive summarisation, where the model produces new text that captures the meaning of the source content rather than simply selecting sentences.

## What is Included

This workspace contains:

- `40798397.ipynb` — the main coursework notebook containing the implementation, experiments, and evaluation
- `Assignment_Template.ipynb` — the assignment template provided for the project
- `AI coursework 25-26 final.pdf` — the assignment brief / coursework specification
- `40798397_coversheet.pdf` — coursework submission cover sheet

## Methodology

The notebook uses:

- Hugging Face `transformers`
- `datasets`
- `rouge_score`
- `pandas`
- Facebook BART (`facebook/bart-large-cnn`) for conditional text generation

The workflow is as follows:

1. Load and inspect the XSum dataset
2. Prepare the article-summary pairs
3. Use a pre-trained BART model for zero-shot summarisation
4. Generate summaries for a sample of test articles
5. Evaluate the generated summaries using ROUGE metrics

## Why This Project Matters

This project demonstrates a practical application of modern NLP and deep learning. It shows:

- how transformer models are used for real-world text generation tasks
- how large pre-trained models can be adapted for summarisation
- how model outputs are evaluated against reference summaries
- the strengths and limitations of automatic summarisation systems

## Technical Stack

- Python
- Jupyter Notebook
- Hugging Face Transformers
- XSum dataset
- ROUGE scoring
- Google Colab-compatible notebook workflow

## Setup

To run the project locally, install the required dependencies:

```bash
pip install transformers datasets rouge_score pandas
```

Then open the notebook in Jupyter or VS Code and run the cells in order.

## Running the Coursework

1. Open `40798397.ipynb` in Jupyter or VS Code.
2. Ensure the required libraries are installed.
3. Run the notebook cells sequentially.
4. Review the output summaries and evaluation metrics.

## Evaluation

The project uses ROUGE metrics to assess summarisation quality:

- ROUGE-1
- ROUGE-2
- ROUGE-L

These metrics compare the generated summary against the gold-standard reference summary and measure overlap in words and phrases.

## Notes

This project is intended for academic coursework purposes and is a practical implementation of an AI-driven summarisation pipeline using modern transformer models.

## License

This repository is for educational use as part of a university coursework submission.
