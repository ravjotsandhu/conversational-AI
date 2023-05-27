Implements the GPT (Generative Pre-trained Transformer) architecture,
inspired by paper like "Improving Language Understanding by Generative Pre-Training"
(Radford et al., 2018)

Key components of the implementation:

1. Token embeddings and positional encoding
2. Multi-head self-attention with causal masking
3. Feed-forward networks with GELU activation
4. Pre-LayerNorm architecture for stability
5. Text generation with various sampling strategies

The architecture follows these key principles:

- Decoder-only transformer architecture
- Autoregressive language modeling objective
- Causal attention masking to prevent seeing future tokens
- Parameter sharing between embedding and output layers

Its a simplified implementation that focuses on architectural clarity with :

- decoder-only architecture with causal attention
- implementation uses standard approaches like GELU activations and layer normalization
- mulitple text generation methods (temperature, top-k, top-p sampling)
- AdamW optimizer for warmup and cosine decay
