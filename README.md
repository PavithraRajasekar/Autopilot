# Autopilot

Maintainer: Pavithra | Patcharin

This project is part of the course IFT-6289 Modern NLP, Winter 2022. We demonstrate the training of GPT-2 / GPT-Neo models on python code for code generation. This is done on colab. There are 2 notebooks - One using the trainer from the Huggingface Hub and the other one using Madgrad optimizer and custom training. You can find the models, tokenizers and dataset in the hub using the following paths.

|   **Pretrained Model Used**  |               **Model Path in the Hub**              | **Epochs** | **Validation Loss** | **Perplexity** |
|:----------------------------:|:----------------------------------------------------:|------------|---------------------|----------------|
| GPT-2                        | [mimicheng/codeparrot-ds-sample-2ep-14apr](https://huggingface.co/mimicheng/codeparrot-ds-sample-2ep-14apr)             | 2          |                1.63 |          5.102 |
| GPT-Neo                      | [Pavithra/codeparrot-ds-500sample-gpt-neo-2ep](https://huggingface.co/Pavithra/codeparrot-ds-500sample-gpt-neo-2ep) | 2          |               1.547 |          4.696 |
| GPT-2 with MADGRAD optimizer | Tokenizer - [Pavithra/Autopilot-madgrad-training-version-1](https://huggingface.co/Pavithra/Autopilot-madgrad-training-version-1/tree/main) <br /> Model - [Pavithra/madgrad-best-version](https://huggingface.co/Pavithra/madgrad-best-version)| 2          |       1.94     |          11.332      |

A sampled dataset of the original codeparrot cleaned dataset can be found in the following paths.<br />
Training dataset in [Pavithra/autopilot-sampled50k-train](https://huggingface.co/datasets/Pavithra/autopilot-sampled50k-train) <br />
Validation dataset in [Pavithra/autopilot-sampled50k-valid](https://huggingface.co/datasets/Pavithra/autopilot-sampled50k-train) <br />

Please go to section Inference in the notebook, where you can load the fine-tuned tokenizers and models for retrieving code generation results with the given prompts.
