# LORA Finetuning text generation

**Problem Statement:**
Develop a Google Colab notebook to fine-tune LORA adapters for text generation task with either a 3B model or a smaller model that accommodates the available GPU RAM. Utilise Hugging Face and PyTorch for implementation, and incorporate WandB for logging purposes. Provide the notebook link, wandb project link and include a screenshot of the convergence graph. You can pick any dataset for a creative text generation task and you should report the perplexity metric

**Model Selected:** bigscience/bloomz-560m

**Dataset Selected:** Amazon Polarity

[![WandB Link](https://img.shields.io/badge/WandB-Text%20Generation%20using%20LORA-blue?style=flat&logo=wandb)](https://wandb.ai/aravindan/Text%20generation%20using%20LORA/runs/shw325rv?workspace=user-aravindsriraj)
[![Colab Link](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OiCgqkO0QKhn79xEs5QfnB02VW732vxW?usp=sharing)

**Train Loss:**

![Train Loss](https://github.com/aravindsriraj/LORA-Finetuning-text-generation/assets/60252521/34911bce-e717-481f-bc45-40173ed4226d)

**Validation Loss**

![Validation loss](https://github.com/aravindsriraj/LORA-Finetuning-text-generation/assets/60252521/82a0eae1-e257-4502-b35a-ff8264e0f118)
