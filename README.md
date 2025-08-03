# Text Summarization Project ✨

This project explores and compares various transformer models for text summarization.

## Models Used 🤖

*   **GPT-2 Medium**
*   **T5 Base**
*   **BART Large CNN**
*   **PEGASUS CNN/DailyMail**

## Datasets 📁

*   **CNN/DailyMail:** News articles for initial exploration.
*   **Samsum:** Conversational dialogues for fine-tuning.

## Project Steps 🚀

1.  Load & explore CNN/DailyMail.
2.  Generate initial summaries.
3.  Analyze Samsum dataset.
4.  Prepare Samsum data for training.
5.  Fine-tune BART-Large-CNN on Samsum (1 epoch).
6.  Summarize a custom dialogue.

## Results 📈

*   Compared summarization by different models.
*   Fine-tuned BART model summarizes dialogues.
*   Presented example summaries.
*   Summarized a custom dialogue.

## How to Run ▶️

1.  Clone the repository.
2.  Install libraries: `pip install -U accelerate bertviz umap-learn sentencepiece py7zr datasets transformers torch`
3.  Run the notebook cells.

## Future Work

*   Evaluate with metrics (ROUGE).
*   Experiment with fine-tuning.
*   Explore other models.
*   Build a summarization UI.
