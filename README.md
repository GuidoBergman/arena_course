# ARENA Course material

## Chapter 1: Transformer Interpretability  
- I built and trained a Transformer model from scratch, following the GPT-2 architecture. Most of my implementation was done in PyTorch and using einsum ([Colab notebook](https://colab.research.google.com/drive/1xf9cE96pB8fIZccKYmnZ_qJrUUSv2vJy))
- I created a hook using TransformerLens to detect induction heads and another hook to perform ablation. Additionally, I implemented a function for calculating logit attribution ([Colab notebook](https://colab.research.google.com/drive/1KUWQRFUy1BO1WfOhwn7U06M5jEjOsjX1))  
- I built and trained the model from Anthropic's "Toy Models of Superposition" paper, in order to replicate some of the results. Additionally, I wrote the code for the architecture and loss function of a SAE, which I trained on the toy model ([Colab notebook](https://colab.research.google.com/drive/1vv2QjXePpUyywUEuSm6IKRxwGWb2_OLm))
- I built and replicated components of a SAE dashboard using SAELens. Additionally, I implemented a hook to perform steering with SAE latents in Gemma ([Colab notebook](https://colab.research.google.com/drive/1QEA77tbLXHYkRhHzLRIg6yxfLj_c49Sp))

## Chapter 3: LLM Evaluations  
- I designed a threat model and specifications for evaluating sycophancy in LLMs ([Colab notebook](https://colab.research.google.com/drive/1TKqaCjkZ9Eyax_LzO5acdsIYe8DZeKfS))  
- I also designed and generated a multiple-choice evaluation for sycophancy using LLMs. This was done implementing Anthropic’s model-written evaluation method ([Colab notebook](https://colab.research.google.com/drive/1CcnnGug-bu--wrB-xbYOUwwnPjlZJkHq))
- I run an evalautions in Inspect ([Colab notebook](https://colab.research.google.com/drive/1koJSAFtR13wkwOUreaVPjcuzNG9ke1RD)) 
- I Implemented multiple AI agents including one that played the Wikipedia Game. Additionally, I explored the implications of multiple elicitation protocols ([Colab notebook](https://colab.research.google.com/drive/1oWOY6oP8T5Qp3TOepCcNi8_4FCI-AG5s)) 
