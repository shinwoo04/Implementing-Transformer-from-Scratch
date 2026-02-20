Transformer-from-Scratch: Mastering Attention Mechanisms
This repository contains a from-scratch implementation of the Transformer architecture, as introduced in the seminal paper, "Attention Is All You Need" (Vaswani et al., 2017).

The goal of this project was to move beyond high-level APIs and gain a granular understanding of the internal mechanisms of self-attention and sequence-to-sequence modeling using PyTorch.

✨ Key Features
Full Architecture Implementation: Built the entire Transformer stack (Encoder and Decoder) without relying on pre-built layers like nn.Transformer.

Advanced Tensor Operations: Utilized einops (Einstein Operations) for clear and intuitive tensor reshaping and multi-head attention logic.

Component-Level Modularization:

Multi-Head Attention: Scaled dot-product attention with learnable projections.

Positional Encoding: Sinusoidal encoding to inject sequence order.

Layer Normalization & Residual Connections: Essential components for training stability.

Attention Visualization: Integrated matplotlib to visualize attention maps, providing insights into how the model focuses on different tokens.

🛠 Tech Stack
Language: Python 3.x

Framework: PyTorch

Key Libraries:

einops: For elegant tensor manipulation.

transformers: Used specifically for tokenization (MarianMT).

matplotlib: For visualizing attention weights.

🧠 Learning Journey: Why this project?
This project was a cornerstone of my self-directed AI study during my military service.

Operating in a constrained environment with limited resources, I focused on "learning by doing." Implementing the Transformer from scratch allowed me to bridge the gap between abstract mathematical formulas and practical, executable code. It taught me the importance of internal model dynamics, tensor flow, and the elegance of attention-based architectures.

📜 References
Vaswani, A., et al. (2017). Attention Is All You Need.

PyTorch Documentation: pytorch.org
