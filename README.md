# QuantizationDNN


| TITLE |DESCRIPTION| YEAR | CODE | PAPER LINK |
|-------|------|------|------|--------|
| COAT: COMPRESSING OPTIMIZER STATES AND ACTIVATION FOR MEMORY-EFFICIENT FP8 TRAINING|          | 2024 | [code](https://github.com/NVlabs/COAT)                                   | [paper](https://arxiv.org/abs/2410.19313) |
| Compressing Large Language Models using Low Rank and Low Precision Decomposition    |         | 2024 | [code](https://github.com/pilancilab/caldera)                            | [paper](https://arxiv.org/abs/2405.18886) |
| A Survey on Transformer Compression                                                  |        | 2024 |  -                                                                       | [paper](https://arxiv.org/abs/2402.05964) |
| Model Quantization and Hardware Acceleration for Vision Transformers: A Comprehensive Survey | | 2024 |[code](https://github.com/DD-DuDa/awesome-vit-quantization-acceleration)  | [paper](https://arxiv.org/abs/2405.00314) |
|A Comprehensive Survey on Model Quantization for Deep Neural Networks in Image Classification | | 2023 | [code](https://github.com/NVIDIA/FasterTransformer)                      | [paper](https://dl.acm.org/doi/10.1145/3623402) |
|  A Survey of Quantization Methods for Efficient Neural Network Inference                     || 2021 |  -                                                                       | [paper](https://arxiv.org/abs/2103.13630) |
| Quantization and Deployment of Deep Neural Networks on Microcontrollers                      | |2021 | -                                                                        | [paper](https://arxiv.org/abs/2105.13331) |
| DEEP COMPRESSION: COMPRESSING DEEP NEURAL NETWORKS WITH PRUNING, TRAINED QUANTIZATION AND HUFFMAN CODING  | Pruning + Trained Quantization + Huffman coding  |  2016 |  | [paper](https://arxiv.org/abs/1510.00149)  |
|     |     |     |  ||


# Other links of codes and theory

|Models| Description | Link |
|-----|------|------|https://www.mdpi.com/2079-9292/13/10/1923?utm_source=chatgpt.com
|K-means, Linear, Binary/Ternary quantization | Detail theory and codes available| [code](https://www.coditation.com/blog/how-to-optimize-large-deep-learning-models-using-quantization#:~:text=K%2DMeans%2Dbased%20quantization%20is,the%20K%2DMeans%20clustering%20algorithm.)|


# K-means based non-uniform quantization
| TITLE | YEAR | DESCRIPTION |LINK |
|------|-------|------|-------|
| Efficient Weights Quantization of Convolutional Neural Networks Using Kernel Density Estimation based Non-uniform Quantizer |  2019  | Proposed a kernel density estimation-based non-uniform quantizer that efficiently quantizes weights using a smaller subset of sampled data, comparable performance to traditional methods with reduced computational costs. | [Paper](https://mdpi.com/2076-3417/9/12/2559?utm_source=chatgpt.com)  |
|  Flexible Quantization for Efficient Convolutional Neural Networks | 2024  | combines the benefits of non-uniform quantization with the implementation efficiency of uniform quantization. This method, termed non-uniform uniform quantization (NUUQ), decouples quantization levels from bit-width, allowing for flexible trade-offs between spatial and temporal complexity in hardware implementations. | [Paper](https://www.mdpi.com/2079-9292/13/10/1923?utm_source=chatgpt.com) |
| IDKM: Memory Efficient Neural Network Quantization via Implicit, Differentiable k-Means |  2023  |  differentiable k-means algorithm (IDKM) that reduces memory complexity, enabling the quantization of large neural networks like ResNet-18 on hardware where traditional k-means methods are impractical  |  [Paper](https://arxiv.org/abs/2312.07759?utm_source=chatgpt.com)  |
| Distributional Quantization of Large Language Models | 2023 | novel method for quantization of LLMs, which stores their parameters in 4 bits while maintaining a performance level comparable to full-precision models. The weight matrices are split into blocks, and for each block, quantization bins are computed as quantiles of a probability distribution. We analyze blocks following Gaussian, Beta, and Student’s t distributions and provide intuition about the parametric assumptions made for each of them. | [Paper](https://www.google.com/search?q=Distributional+Quantization+of+Large+Language+Models&rlz=1C1GCEU_enMY1056MY1057&oq=Distributional+Quantization+of+Large+Language+Models&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIKCAEQABiABBiiBDIHCAIQABjvBTIKCAMQABiABBiiBNIBBzUzMGowajeoAgCwAgA&sourceid=chrome&ie=UTF-8#vhid=zephyr:0&vssid=atritem-https://www.cee.org/sites/default/files/rsi/Papers/Cholakov_Radostin.pdf) |











