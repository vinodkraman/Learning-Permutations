# Learning Permutations
We view Transformers and RNNs as sequence-to-sequence maps and compare their ability to permute their input sequence of tokens. We find that without positional encoding, Transformers perform *worse* than RNNs when attempting to learn an unknown permutation transformation from labeled training data. However, the opposite is true once positional encodings are incorporated. 
