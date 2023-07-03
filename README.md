# FedBERT

## Summary
The rapid advancement of pre-trained models (PTMs) has revolutionized natural language processing (NLP) by offering powerful techniques for various NLP applications. These PTMs allow users to download model weights and fine-tune them for specific tasks locally. However, the pre-training process of these models heavily relies on access to large-scale training data and requires substantial computing resources. These strict requirements make it infeasible for individual clients to pre-train such models independently.

To address this challenge and enable clients with limited computing capabilities to participate in pre-training large models, we introduce a novel learning approach called FedBERT. FedBERT leverages the principles of federated learning and split learning to pre-train BERT in a federated manner. By doing so, FedBERT ensures that raw data information is not shared while achieving excellent performance.

This repository is a proof of concept for the reference [Yua22]. However, the experimental setup and model structure are somewhat different.

## Installation

1. Clone the project:

```
$ git clone https://github.com/karapto/FedBERT.git && cd FedBERT
```

2. Pip-install dependencies. For example using a virtualenv:

```
$ virtualenv env && source env/bin/activate && pip install -r requirements.txt
```

3. Run the notebook:

```
$ jupyter notebook
```

## References
[Yua22] Tian, Yuanyishu, Yao Wan, Lingjuan Lyu, Dezhong Yao, Hai Jin, and Lichao Sun. "FedBERT: when federated learning meets pre-training." ACM Transactions on Intelligent Systems and Technology (TIST) 13, no. 4 (2022): 1-26.
