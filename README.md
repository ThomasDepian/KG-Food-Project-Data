# Data Files for "Knowledge Graph-based Nutrition, Food and Recipes (Inference) System"

## Purpose of the Project
The _Knowledge Graph-based Nutrition, Food and Recipes (Inference) System_ is a knowledge graph (KG) storing recipes together with their ingredients and nutritions.
Given this KG, the task is to derive recipe suggestions based on nutrition values or time constraints and predict, for example, missing nutrition values.

## Purpose of this Repository
The KG is stored in an online [neo4j](https://neo4j.com/) instance and is populated from _.csv_ files.
However, for security reasons, neo4j forbids to upload the files directly to the server, but must load them from a puplicy available online storage, such as GitHub [2].
This repository should serve as this online storage service.

## Where does the Data come from
This data contains crawled data from _Food.com_.
We did not create this dataset, but used it from Kaggle [1]
Our _.csv_-files contain the unmodified data, i.e. we only changed the structure to ease the import to neo4j.

## References
- [1] Shuyang Li. (2019). <i>Food.com Recipes and Interactions</i> [Data set]. Kaggle. Last accessed: 2023-05-11
  - Doi: [https://doi.org/10.34740/KAGGLE/DSV/783630](https://doi.org/10.34740/KAGGLE/DSV/783630)
  - Url: [https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)

- [2] Neo4j. _Importing Data_. Neo4j Last accessed: 2023-05-11
  - Url: [https://neo4j.com/docs/aura/auradb/importing/importing-data/](https://neo4j.com/docs/aura/auradb/importing/importing-data/)