# Customer Segmentation and Movie Recommendation using KG Embeddings
### Dependencies
1. `conda create -n <env_name> python=3.12.4`
2. `pip install scikit-learn` works on v1.5.1
3. `pip install neo4j` works on v5.24.0
4. `pip install pandas` works on v2.2.2
5. `pip install networkx` works on v3.3
6. `pip install node2vec` works on v0.5.0
7. A running neo4j graph database

Additionally a requirements.txt files is available with a working environment.  
It can be installed with the following command `pip install -r requirements.txt`

### Usage
1. Create and run a neo4j database.
2. Insert credentials of database in the first cell of all notebooks
3. To populate the database run `kg_construction/populate_db.ipynb`
4. For the customer segmentation run `kg_embeddings/customer_segmentation.ipynb`

### Dataset
The dataset used for this project is **MovieLense Small** and can be downloaded [here](https://grouplens.org/datasets/movielens/latest/.).