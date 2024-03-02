# Vision Transformer from Scratch

This repository presents an in-depth implementation of the Vision Transformer (ViT) model, following the seminal work titled ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929) by Alexey Dosovitskiy et.al. ViT represents a paradigm shift in image recognition by leveraging the transformer architecture, originally designed for natural language processing, to process image directly.

## Vision Transformer(ViT)

The ViT model breaks away from the conventional convolutional neural network (CNN) approach to image analysis. It replaces the traditional convolutional layers with self-attention mechanisms, allowing it to capture global dependencies among image patches effectively. Key components of the ViT model include:

* **Patch Embedding**: Breaking down the input image into smaller patches and linearly projecting them into smaller patches and linearly projecting them into a lower-dimensional space, which serves as the input to the transformer encoder.
* **Positional Encoding**: Incorporating positional information into the input embeddings to provide the model with spatial context, crucial for understanding the relationships between different patches.
* **Transformer Encoder**: A stack of transformer encoder layers processes the patch embeddings, enabling the model to capture both local and global image features through self-attention mechanisms and feed-forward neural networks.
* **Classification Head**: Following the transformer encoder, a simple classification head (usually a linear layer) is attached to predict the class labels for the input image.

## (Code)[https://kunal-kumar-sahoo.github.io/ViT-from-Scratch/main.html]

## References

* Dosovitskiy, A., et al. "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale." arXiv preprint arXiv:2010.11929 (2020).

## Acknowledgements

This implementation draws heavily from the original ViT paper and the contributions of the PyTorch community to the transformer-based models. Special thanks to the authors and developers for making their code and research openly available.

## Contributing

Contributing to this repository are welcome. Feel free to submit issues, feature requests, or pull requests to improve the implementation and documentations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
