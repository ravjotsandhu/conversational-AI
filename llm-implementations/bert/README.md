implements the BERT architecture as described in the paper
"BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"
(Devlin et al., 2018). The implementation includes:

1. BERT Embeddings (Token, Position, Segment)
2. Multi-Head Self-Attention
3. Feed-Forward Networks
4. Layer Normalization
5. BERT Encoder Stack
6. Pre-training Heads (MLM and NSP)
7. Fine-tuning for Classification
8. Optimizer and learning rate schdeule

... all of this on toy dataset

Key architectural highlights of BERT:

- Bidirectional self-attention, allowing the model to learn context from both directions
- Pre-training with masked language modeling and next sentence prediction
- Fine-tuning the same architecture for various downstream tasks
