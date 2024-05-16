# pretrained-transformer-spr24
Implementation of a Transformer model trained on Wiki data to attempt to answer simple questions of the form “Where was person [x] born?” without providing any input text from which to draw the answer. Pretrained and finetuned two models, one with positional embeddings from the vanilla Transformer model, one with RoPE (Rotary Positional Embedding) [^1] Part of assignment 4 CS224n Spring 2024.

[^1]: Su, J., Ahmed, M., Lu, Y., Pan, S., Bo, W., and Liu, Y. Roformer: Enhanced transformer with rotary position embedding. *Neurocomputing 568* (2024), 127063. [https://arxiv.org/abs/2104.09864](https://arxiv.org/abs/2104.09864).
