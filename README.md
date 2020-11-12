# The path of Seq2seq 

## Environment
- Python 3.6
- Pytorch 1.4
- Torchtext 0.6
- Spacy

## Introduction

### 1 - Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation
This file implement the encoder-decoder model.  And I use GRU in both encoder and decoder.

 - Paper: [Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/abs/1406.1078)
 - Code:  [Encoder-Decoder](https://github.com/codingmakesmehappy/seq2seq_path/blob/main/Learning%20Phrase%20Representations%20using%20RNN%20Encoder-Decoder%20for%20Statistical%20Machine%20Translation.ipynb)

### 2 - Sequence to Sequence Learning with Neural Networks
This file utilise two-layer LSTMs in both encoder and decoder.

- Paper: [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)
- Code: [Seq2seq](https://github.com/codingmakesmehappy/seq2seq_path/blob/main/Sequence%20to%20Sequence%20Learning%20with%20Neural%20Networks.ipynb)

### 3 - Neural Machine Translation by Jointly Learning to Align and Translate
This file add attention mechanism, packed padded sequences and masking based on Seq2seq model. These are common method used in NLP. The attention mechanism allows the decoder to pay attention on the relevant words in the input sentence. Packed padded sequences allows us to only process the non-padded input sentence using RNN. Masking alows the model to ignore certain elements we do not want it to look at.
 - Paper: [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)
 - Code: [Seq2seq with attention](https://github.com/codingmakesmehappy/seq2seq_path/blob/main/better_seq2seq.ipynb)


## Reference

 - https://pytorch.org/tutorials/beginner/torchtext_translation_tutorial.html
