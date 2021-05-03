# OffensEval 2020

Este repositório contém o código que foi utilizado para gerar o modelo de classificação para a competição [OffensEval 2020](https://sites.google.com/site/offensevalsharedtask/results-and-paper-submission).

Foi utilizado o pipeline TextCategorizer da biblioteca [spaCy](https://spacy.io/) juntamente com o modelo de linguagem [en_core_web_lg](https://spacy.io/models/en#en_core_web_lg).

O paper gerado para a competição se encontra no site da [ACL Anthology](https://www.aclweb.org/anthology/2020.semeval-1.297/).

Os datasets utiizados no projeto estão disponíveis tanto no site oficial da [competição](https://sites.google.com/site/offensevalsharedtask/results-and-paper-submission) quanto neste [link](https://drive.google.com/file/d/1XoTfqfxz8JXer5MPLz99vWlGXwRExtiF/view?usp=sharing).

Especificações:

- Linguagem: Python
- Machine Learning Lib: spaCy v2.3.2
- Modelo de Linguage: en_core_web_lg v2.3.1
- Training/test set: [SOLID](https://sites.google.com/site/offensevalsharedtask/solid)
- Validation set: [OLID](https://sites.google.com/site/offensevalsharedtask/olid)