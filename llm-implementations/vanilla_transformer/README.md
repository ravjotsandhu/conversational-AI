Implements the Transformer architecture as described in the paper
"Attention Is All You Need" (Vaswani et al., 2017). The implementation includes:

1. Positional Encoding
2. Multi-Head Attention
3. Position-wise Feed-Forward Networks
4. Layer Normalization
5. Encoder and Decoder stacks
6. Full Transformer model

Notebook has demo of training and inference on a synthetic sequence-to-sequence task.
The model learns to reverse sequences, showing how the Transformer architecture
can effectively model sequence relationships.

Key architectural highlights:

- The use of self-attention to capture long-range dependencies
- Multi-head attention to jointly attend to different representation spaces
- Residual connections and layer normalization for stable training
- Position-wise feed-forward networks for additional transformation power
- Positional encodings to incorporate sequence order
