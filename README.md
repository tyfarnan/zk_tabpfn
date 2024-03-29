# Towards Scalable ZKML "training" via Prior Fitted Networks

### What if we could prove what training data was used to make predictions, in the same way we prove inference?

## Overview
- [giza_tabpfn_demo.ipynb](https://github.com/tyfarnan/zk_tabpfn/blob/main/zk_tabpfn/TabPFN/tabpfn/giza_tabfn_demo.ipynb): Contains end-end example using Giza Actions and Giza Model to perform perform end-end supervised classification on a tabular datset from OpenML.
- Within the `zk_tabpfn` directory, the [TabPFN REPO](https://github.com/automl/TabPFN/tree/main) has been ported in :
- `transformer_prediction_interface.py`: Has been slightly modified to work with Giza Actions.


## Requirements
- Python 3.11
- Conda, pip (or Poetry)

## Get Started
```bash
$ conda activate env
$ pip install -e .
```
or with poetry
```bash
$ poetry shell
$ poetry install
```

## Learn More

*Note: This project worked from the Giza's [MNIST tutorial](https://actions.gizatech.xyz/tutorials/build-a-verifiable-neural-network-with-giza-actions). Please be aware that certain steps, such as transpiling the model and deploying the generated model on Giza Plateform, are required between action executions. For a more comprehensive understanding, refer to the tutorial.*

Explore more about the Giza Actions SDK [here](https://actions.gizatech.xyz/welcome/giza-actions-sdk).

