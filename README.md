## EXP-1-PROMPT-ENGINEERING-
## Aim:
Comprehensive Report on the Fundamentals of Generative AI and Large Language Models (LLMs) Experiment: Develop a comprehensive report for the following exercises:
Explain the foundational concepts of Generative AI. Focusing on Generative AI architectures. (like transformers). Generative AI applications. Generative AI impact of scaling in LLMs.

## Algorithm:
Data Preparation : The first step is to collect and clean a large dataset, removing duplicates, errors, and sensitive data. The cleaned text is then tokenized into subword units so the model can process language efficiently.

Model Setup : A Transformer-based architecture is defined with layers, attention heads, and embedding sizes. The weights are initialized, and hyperparameters such as learning rate, batch size, and optimizer are chosen.

Training : During training, tokenized sequences are converted into embeddings and passed through self-attention and feed-forward layers. The model predicts the next token, calculates cross-entropy loss, and updates weights using gradient descent until it learns language patterns.

Fine-Tuning & Alignment : After pretraining, the model is fine-tuned with curated instruction–response datasets. Alignment methods like Reinforcement Learning with Human Feedback (RLHF) or Direct Preference Optimization (DPO) ensure the outputs are helpful, safe, and aligned with user expectations.

Inference : When deployed, the model takes a user prompt, encodes it, and generates text using decoding methods such as greedy search, top-k sampling, or nucleus sampling to balance fluency and creativity.

Evaluation & Deployment : The model is tested with metrics like perplexity, BLEU, or human evaluation to measure accuracy, usefulness, and safety. Once validated, it is deployed with guardrails, monitoring systems, and filters to ensure reliable and responsible usage.

## Output
Data Preparation: *Collect and clean dataset. *Remove duplicates and errors. *Tokenize into subword units.

Model Setup: *Define Transformer architecture. *Initialize weights. *Select hyperparameters (learning rate, batch size, optimizer).

Training: *Convert tokens into embeddings. *Apply self-attention and feed-forward layers. *Predict next token and calculate loss. *Update weights with optimizer.

Fine-Tuning & Alignment: *Train on instruction–response pairs. *Apply RLHF or DPO for alignment. *Ensure helpful and safe outputs.

Inference: *Take user prompt as input. *Encode into tokens. *Generate response using decoding (greedy, top-k, nucleus).

Evaluation & Deployment: *Measure metrics (perplexity, BLEU, human evals). *Test safety and reliability. *Deploy with monitoring and guardrails.

## Output File
[Prompt.Eng.Exp-1.pdf](https://github.com/user-attachments/files/22049645/Prompt.Eng.Exp-1.pdf)


## Result
The experiment showed that a Transformer-based LLM can learn language patterns through training and generate meaningful text responses. Fine-tuning and alignment improved accuracy, while evaluation confirmed the outputs were fluent, relevant, and safe.
