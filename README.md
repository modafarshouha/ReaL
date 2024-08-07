# ReaL
This is a code implementation for **ReaL** (Reassessing Softmax Score by Logits Distillation for Foundation Model Based Intent Classification) paper, presented in [ISPR 2024]([https://doi.org/10.1109/SACI58269.2023.10158563](https://ispr2024.sciencesconf.org/) conference. <br>

## Abstract
With the extensive employment of large Foundation Models, the traditional classification concepts are challenged. In this work, we target a crucial task in natural language processing (NLP) and understanding (NLU); i.e. intent classification. We first debate the applicability of classical out-of-distribution definition and introduce a more realistic type; i.e. non-semantic OOD (NS-OOD). The results of our experiments asserted our claim and demonstrated that NS-OOD data poses a challenge for even powerful classifiers. Additionally, we support the criticism of relying only on the classifier's last layer logits to evaluate its correctness. Consequently, we propose a method (ReaL) to regain the trust of softmax score as a confidence indicator. This is performed by distilling the logits using the temperature parameter. We show that ReaL provides better separation between correct and wrong predictions' scores. To achieve a proper temperature estimation, we perform a mathematical derivation. Our approach calculates an adequate temperature value for a given model and a dataset. <br>

Please refer to this repository and cite our publication when using this work.

## Cite
```
citation will be added son.
```
