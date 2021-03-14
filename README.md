# De-identification-of-medical-information

A conversation between a doctor and a patient contains private information. However, the amount of data is huge. Therefore, in this project, use "Named Entity Recognition" to extract them.

## Environment
1. Torch 1.8.0
2. Numpy 1.19.2
3. Pandas 0.24.2
4. Pickle 0.7.5


## Experiments
| Model number | Architecture | Embedding dimension | Hidden layer dimension | F1 score |
|:-:|:-:|:-:|:-:|:-:|
| 1 | CRF | 512 | X | 0.434 |
| 2 | BiLSTM + CRF | 512 | 512 | 0.58 |
| 3 | BiLSTM + CRF | 128 | 128 | 0.67 |
| 4 | BiLSTM + CRF | 256 | 256 | 0.71 |


## Acknowledgment
1. [named entity recognition](https://github.com/luopeixiang/named_entity_recognition)
