### Reference

[(2024 May) Nearest Neighbor Speculative Decoding for LLM Generation and Attribution](https://arxiv.org/abs/2405.19325)

- Could be related to CD-LM (pointed by reviewers), but it is less sophisticated
- https://openreview.net/forum?id=Ni9kebsSTt&noteId=SFE8WT1fd7

[(2024 Dec) Byte Latent Transformer: Patches Scale Better Than Tokens](https://arxiv.org/pdf/2412.09871)

- Group bytes into patches
- This is similar to chunks

[(2025 Mar) SuperBPE: Space Travel for Language Models](https://arxiv.org/abs/2503.13423)

- Change BPE tokenization to respect the phrase boundaries/white space
- https://superbpe.github.io/

[(2025 July) Dynamic Chunking for End-to-End Hierarchical Sequence Modeling](https://arxiv.org/pdf/2507.07955)

- Dynamically merge input tokens (or segment tokens into chunks, with each chunk one representation), based on adjacent token similarities
- Keep track of the token chunk segmentation "probabilities", used for passing gradients through the operations
- Expand the number of tokens back in the final layer, by copying the tokens over to fill in positions
