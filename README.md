# Autopilot

This project is part of the course IFT-6289 Modern NLP. We demonstrate the training of GPT-2 / GPT-Neo models on python code for code generation. This is done on colab. There are 2 notebooks - One using the trainer from the Huggingface Hub and the other one using Madgrad optimizer and custom training. You can find the models, tokenizers and dataset in the hub using the following paths.

|   **Pretrained Model Used**  |               **Model Path in the Hub**              | **Epochs** | **Validation Loss** | **Perplexity** |
|:----------------------------:|:----------------------------------------------------:|------------|---------------------|----------------|
| GPT-2                        | mimicheng/codeparrot-ds-sample-2ep-14apr             | 2          |                1.63 |          5.102 |
| GPT-Neo                      | Pavithra/codeparrot-ds-sample-gpt-small-neo-10epoch1 | 2          |               1.547 |          4.696 |
| GPT-2 with MADGRAD optimizer | Tokenizer - Pavithra/Autopilot-madgrad-training-version-1 <br />| 2          |       1.94     |          11.332      |
