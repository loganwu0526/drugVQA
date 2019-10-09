# Predicting Drug Protein Interaction using Quasi-Visual Question Answering System

Supporting Information for the paper "[Predicting Drug Protein Interaction using Quasi-Visual Question Answering System](https://www.baidu.com)"

DrugVQA is a multimodel learning method combining a dynamic attentive convolutional neural network to learn fixed-size represen-tations from the variable-length distance maps and a self-attentional sequential model to automatically extract semantic features from the linear notations.

![DrugVQA](Image/drugVQA.png)


## Dataset
All data used in this paper are publicly available and can be accessed here: [DUD-E](http://dude.docking.org ), [BindingDB-IBM dataset](https://github.com/IBM/InterpretableDTIP), [Human dataset](https://github.com/masashitsubaki/CPI_prediction/tree/master/dataset) and [protein 3D structure](https://www.rcsb.org).


## Demo Instructions
All default arguments for demo are provided in the [trainAndTest.ipynb](./trainAndTest.ipynb).

## Usage
To run the training procedure,

1. Install [requirements.text](./requirements.text) to set up the envirnoment.
2. Run the [trainAndTest.ipynb](./trainAndTest.ipynb) to train and test the model.
