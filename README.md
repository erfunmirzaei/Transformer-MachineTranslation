# Overview
In this assignment, we implemented a Transformer model from the Attention is All You Need paper[1]. A Sequence-to-Sequence model can be used for machine translation, speech recognition, and many other purposes. The Transformer does not use any recurrence, like the Convolutional Sequence-to-Sequence model. It also does not use any convolutional layers. The model is instead entirely composed of linear layers, attention mechanisms, and normalization.

In this assignment, we used the Transformer Network to translate English sentences into Persian and evaluated the translation by the BLEU and NIST scores. We used the AFEC Dataset, which the NLP lab prepared at Tehran University. 

[1] Vaswani, A., Shazeer, N.M., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A.N., Kaiser, L., & Polosukhin, I. (2017). Attention is All You Need. ArXiv, abs/1706.03762. 

