# Transformer from Scratch (PyTorch)

Decoder-only transformer built up in stages to show what each component contributes:
uniform sampling → bigram → MLP → single-head attention → multi-head transformer.

Hand-written scaled dot-product causal attention is verified against
`F.scaled_dot_product_attention` with `torch.allclose`.

## Data
Not committed. `odyssey.txt` is Project Gutenberg; see notebook for the path.

## Status
Work in progress — validation split, AdamW, and a pre-LN vs post-LN ablation to follow.
