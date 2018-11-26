# This is a natural language processing course-based project. The project is to designed an RNN-based encoder and decoder with self-attention mechanism to translate Chinese/Vietnamese to English

## Completed
:white_check_mark: Add dataloader

:white_check_mark: Train Unknown word representation

:white_check_mark: Mask

:white_check_mark: Minibatch

:white_check_mark: Bleu score

## To do list

* Save model
* Self-attention
* Multiple layers in encoder and decoder
* Without Attention
* Bean Search
* BPE
* Revtok to detokenize
* Play around the original data with respect to tokenization
* Hierarchy softmax
* randomgridsearch

## Issues

:question: Including EOS token but I also used the mask to force the sentence stop learning, so EOS will not be updated.

:question: the most frequent word in Chinese vocabulary is " ", not sure if this will be an issue.

:question: Used max_length = 100 from source sentence in both encoder and decoder?
