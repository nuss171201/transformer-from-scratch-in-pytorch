 Transformer from Scratch(PyTorch)


Built a small language model step by step, starting from the simplest possible thing and adding one piece at a time, the goal was to actually understand why each part of a transformer exists and how it works




The steps...

Random guessing - pick letters at random, terrible, but it's the baseline
Bigram - count which letter usually follows which, slightly less terrible
MLP - a small neural net that looks at the whole prefix
Attention - the model learns which earlier characters matter
Transformer - multi-head attention, layer norm, residual connections, positional embeddings, 6 blocks stacked
