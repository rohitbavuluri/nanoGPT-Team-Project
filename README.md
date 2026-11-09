# nanoGPT Team Project

## Project Overview
This project investigates the effects of different hyperparameter configurations on nanoGPT, a small implementation of a Generative Pre-trained Transformer (GPT).

The experiments use the Shakespeare character-level dataset to train and evaluate language models.

## Member 3 and Member 4 — Experimental Work

A total of **64 experiments** were completed using Google Colab with GPU acceleration.

- Member 3: 32 experiments
- Member 4: 32 experiments

### Hyperparameters Investigated

| Hyperparameter | Values |
|---|---|
| Block size | 128 |
| Number of layers | 4, 6 |
| Attention heads | 4, 8 |
| Embedding dimensions | 128, 256 |
| Batch size | 8, 16 |
| Training iterations | 1,000, 2,000 |
| Dropout | 0.1, 0.2 |

## Best Model Configuration

The best-performing configuration was **Member 4, Experiment 31**.

| Parameter | Value |
|---|---|
| Block size | 128 |
| Layers | 6 |
| Attention heads | 8 |
| Embedding dimensions | 256 |
| Batch size | 16 |
| Training iterations | 2,000 |
| Dropout | 0.1 |
| Training loss | 1.6346 |
| Validation loss | 1.8013 |
| Training time | 45.99 seconds |

The best model was selected based on the lowest recorded validation loss.

## Results and Analysis

The project includes comparisons of validation loss, training time, and hyperparameter effects, along with generated Shakespeare-style text.

The complete experiment summary contains 64 records. Some original training artifacts are unavailable, but the missing summary measurements were recovered from saved notebook outputs.

## Repository Files

- `nanoGPT_Member3_Member4 (2).ipynb` — Google Colab experiment notebook
- `nanoGPT_Final_Results_Members3_4.zip` — Experiment results, available training logs, and graphs
- `nanoGPT_Members_3_4_Detailed_Report.docx` — Detailed documentation and analysis

## Tools and Technologies

- Python
- PyTorch
- nanoGPT
- Google Colab
- NVIDIA GPU
- Pandas
- Matplotlib

## Conclusion

The experiments demonstrate how transformer architecture, embedding dimensions, batch size, training duration, and dropout influence language-model performance. The lowest validation loss was achieved using six transformer layers, eight attention heads, 256 embedding dimensions, batch size 16, 2,000 training iterations, and dropout 0.1.

## Team Contributions

Members 3 and 4: Hyperparameter experiments, evaluation, visualization, and documentation.

Members 1 and 2: Contributions to be added after team integration.
