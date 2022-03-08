# PyTorch-MHA-DifferentialCounting

Multi-Head Attention for counting difference of the number of occurrences of X and Y in XY[0-5]+ pattern.

---

The notebook trains a neural network that solves the following task:

Given an input sequence `XY[0-5]+` where `X` and `Y` are two given digits, the task is to count the number of occurrences of `X` and `Y` in the remaining substring and then calculates the difference `#X - #Y`.

```
Example:
Input: 1213211
Output: 2 (3 - 1)
```

The problem is solved with a multi-head attention network.

# Attention Is All You Need

"[Attention is All You Need](https://arxiv.org/abs/1706.03762)"(Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin, arxiv, 2017) is a transformer model, based solely on attention mechanisms, which has pushed the Natural Language Processing (NLP) world to new frontiers, especially sequence to sequence translation. It achieved the SOTA performance on WMT2014 English-to-German translation.

<p align="center">
<img src="https://user-images.githubusercontent.com/1178221/157217111-d2a417d4-3be0-4406-866a-c183977f8308.png" width=250>
</p>
