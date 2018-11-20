# Neural-Machine-Translation
## This is a natural language processing course-based project. The project is to designed an RNN-based encoder and decoder with fancy architecture to translate Chinese/Vietnamese to English.

## Completed
:white_check_mark: Add dataloader

:white_check_mark: Train Unknown word representation

:white_check_mark: Mask

:white_check_mark: Minibatch

## To do list

* Bleu score
* Save model
* Self-attention
* Multiple layers in encoder and decoder
* Without Attention
* Bean Search
* BPE
* Revtok to detokenize
* Play around the original data with respect to tokenization


## Issue 

:question: Does Unknown token learn?
:question: Including EOS token but I also used the mask to force the sentence stop learning, so EOS will not be updated.
:question: the most frequent word in Chinese vocabulary is " ", not sure if this will be an issue.
