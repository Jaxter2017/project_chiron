# Project Chiron
Mission to see true active teaching made available to all students.

## Previous Experiments

I've collected 350 year 11 maths mock exams (UK based) and conducted a series of investigations to better understand how large language models can be utilised in an education setting. Please see the [dataset page](https://github.com/Jaxter2017/project_chiron/wiki/Dataset) for the details on the data.

### BERT-based classifiers

The end model here simply consists of a pretrained transformer model (which produces a layer of embeddings) with a multilayer perceptron classifier head. The classifier head is trained on the specific maths problem.

#### Sentence embeddings

A multitude of different pretrained transformers have been used to extract sentence level embeddings from the processed student problem attempts. Please see the [embeddings page](https://github.com/Jaxter2017/project_chiron/wiki/Embeddings) for more info on these models.

#### classifier head

### GPT-based inference

#### fine-tuning base GPT-3.0

#### zero/few-shot prompting GPT-3.5

## Future Plan
