# ReaL
This is a code implementation for **ReaL** (Reassessing Softmax Score by Logits Distillation for Foundation Model Based Intent Classification) paper, presented in [ISPR 2024](https://link.springer.com/chapter/10.1007/978-3-031-82150-9_1) conference. <br>

## Abstract
With the extensive employment of large Foundation Models, the traditional classification concepts are challenged. In this work, we target a crucial task in natural language processing (NLP) and understanding (NLU); i.e. intent classification. We first debate the applicability of classical out-of-distribution definition and introduce a more realistic type; i.e. non-semantic OOD (NS-OOD). The results of our experiments asserted our claim and demonstrated that NS-OOD data poses a challenge for even powerful classifiers. Additionally, we support the criticism of relying only on the classifier's last layer logits to evaluate its correctness. Consequently, we propose a method (ReaL) to regain the trust of softmax score as a confidence indicator. This is performed by distilling the logits using the temperature parameter. We show that ReaL provides better separation between correct and wrong predictions' scores. To achieve a proper temperature estimation, we perform a mathematical derivation. Our approach calculates an adequate temperature value for a given model and a dataset. <br>

## Cite
Please refer to this repository and cite our publication when using this work. <br>
```
@InProceedings{10.1007/978-3-031-82150-9_1,
	author="Sz{\H{u}}cs, G{\'a}bor and Al-Shouha, Modafar",
	editor="Bennour, Akram and Bouridane, Ahmed and Almaadeed, Somaya and Bouaziz, Bassem and Edirisinghe, Eran",
	title="ReaL: Reassessing Softmax Score by Logits Distillation for Foundation Model Based Intent Classification",
	booktitle="Intelligent Systems and Pattern Recognition",
	year="2025",
	publisher="Springer Nature Switzerland",
	address="Cham",
	pages="1--12",
	abstract="With the extensive employment of large Foundation Models, the traditional classification concepts are challenged. In this work, we target a crucial task in natural language processing (NLP) and understanding (NLU); i.e. intent classification. We first debate the applicability of classical out-of-distribution definition and introduce a more realistic type; i.e. non-semantic OOD (NS-OOD). The results of our experiments asserted our claim and demonstrated that NS-OOD data poses a challenge for even powerful classifiers. Additionally, we support the criticism of relying only on the classifier's last layer logits to evaluate its correctness. Consequently, we propose a method (ReaL) to regain the trust of softmax score as a confidence indicator. This is performed by distilling the logits using the temperature parameter. We show that ReaL provides better separation between correct and wrong predictions' scores. To achieve a proper temperature estimation, we perform a mathematical derivation. Our approach calculates an adequate temperature value for a given model and a dataset (Our code is available at https://github.com/modafarshouha/ReaL.).",
  isbn="978-3-031-82150-9"
}
```
