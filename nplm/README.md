Implementation of the [Neural Probabilistic Language Model](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) (Bengio et al., 2003).

This paper was one of the first papers to propose learning dense continuous-valued representations of words using a neural network. This was significant because word sequence data suffer from the curse of dimensionality--the possible number of sequences grows exponentially with respect to sequence length. With dense representations, each sequence in the training data can inform the model about exponentially many semantically similar sequences.
