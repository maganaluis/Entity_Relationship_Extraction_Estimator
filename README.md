# EARC_Estimator
Entity Aware for Relation Classification Estimator Implementation


# <center> Semantic Relation Classification via Bidirectional LSTM Networks w/ Entity-aware Attention using Latent Entity Typing </center>

# <center> Tensorflow Estimator </center>

This repository contains the official TensorFlow implementation of the following paper:

> **Semantic Relation Classification via Bidirectional LSTM Networks with Entity-aware Attention using Latent Entity Typing**<br>
> Joohong Lee, Sangwoo Seo, Yong Suk Choi<br>
> [https://arxiv.org/abs/1901.08163](https://arxiv.org/abs/1901.08163)
> 
> **Abstract:** *Classifying semantic relations between entity pairs in sentences is an important task in Natural Language Processing (NLP). Most previous models for relation classification rely on the high-level lexical and syntactic features obtained by NLP tools such as WordNet, dependency parser, part-of-speech (POS) tagger, and named entity recognizers (NER). In addition, state-of-the-art neural models based on attention mechanisms do not fully utilize information of entity that may be the most crucial features for relation classification. To address these issues, we propose a novel end-to-end recurrent neural model which incorporates an entity-aware attention mechanism with a latent entity typing (LET) method. Our model not only utilizes entities and their latent types as features effectively but also is more interpretable by visualizing attention mechanisms applied to our model and results of LET. Experimental results on the SemEval-2010 Task 8, one of the most popular relation classification task, demonstrate that our model outperforms existing state-of-the-art models without any high-level features.*

![title](https://user-images.githubusercontent.com/15166794/52579582-c7339100-2e69-11e9-9081-711e7576e717.png)

Code was transformed into an estimator format from the following repository:

> **Entity-aware Attention for Relation Classification**<br>    
> [https://github.com/roomylee/entity-aware-relation-classification](https://github.com/roomylee/entity-aware-relation-classification)

Notes: 

I really liked this model due to its simplicity, it is simple to understand and manipulate, the authors do a great job at explaining the details in their paper, so I decided to share the Tensorflow Estimator that I created from the original code. Estimators make it easier to deploy Tensorflow models, and handle most of the training code for you, so I hope researchers use them more often. 

While I was not able to obtain the accuracy highlighted in the paper, it should not stop anyone from trying different things with the model so you can achieve a higher accuracy.
