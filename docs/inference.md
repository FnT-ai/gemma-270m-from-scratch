# Inference

After training, the model performs autoregressive text generation.

Typical workflow:

1. Tokenize prompt
2. Forward pass
3. Sample next token
4. Append token
5. Repeat until stopping criteria
