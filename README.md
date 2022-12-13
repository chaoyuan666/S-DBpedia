# S-DBpedia: A benchmark dataset for spatial knowledge graph completion

- A benchmark for Spatial Knowledge Graph Completion (**SKGC**) extracted from **DBpedia**.
- It can be used to evaluate Knowledge Graph Embedding methods or to evaluate Knowledge Graph Embedding methods with **attributes**.
- The S-DBpedia baseline dataset contains two types of datasets. 
  - Data scale: S-DBpedia_small, S-DBpedia_medium, S-DBpedia_large, S-DBpedia.
  - Data Sparsity: S-DBpedia_GT5E, S-DBpedia_GT10E, S-DBpedia_GT20E, S-DBpedia_GT50E.

## Dataset Statstics and Analysis

|     Dataset      | Relation | Entity  | Training Set | Validation Set | Test Set |
| :--------------: | :------: | :-----: | :----------: | :------------: | :------: |
| S-DBpedia_small  |   221    | 241,869 |   227,574    |     6,026      |  6,107   |
| S-DBpedia_medium |   247    | 413,157 |   455,148    |     21,108     |  21,439  |
| S-DBpedia_large  |   278    | 650,120 |   910,296    |     69,577     |  69,603  |
|    S-DBpedia     |   305    | 879,610 |   1820,591   |    195,104     | 195,106  |
|  S-DBpedia_GT5E  |   169    | 44,187  |   128,823    |     15,393     |  15,339  |
| S-DBpedia_GT10E  |   229    | 90,523  |   267,585    |     32,375     |  32,381  |
| S-DBpedia_GT20E  |   253    | 183,706 |   542,141    |     66,260     |  66,355  |
| S-DBpedia_GT50E  |   281    | 461,516 |   1221,639   |    148,239     | 148,475  |

- Data scale: S-DBpedia_small, S-DBpedia_medium, S-DBpedia_large, S-DBpedia.
- Data Sparsity: S-DBpedia_GT5E, S-DBpedia_GT10E, S-DBpedia_GT20E, S-DBpedia_GT50E.



## Attributes

We extracted all attributes of entities in the dataset from **DBpedia**. It contains **text**, **numerical**, and **image** information.

The full dataset with attribute information is available in [Zenodo](https://doi.org/10.5281/zenodo.7431612).



## Benchmarking

- Link predection experiments are conducted with three models **TransE**, **DistMult**, and **ConvE** on all datasets using [**OpenKE**](https://github.com/thunlp/OpenKE).
- the configurations for each of the models are given in the Code diectory.

