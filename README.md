# Visualizing Vector Embeddings



## Solution Overview


- Prepare a sample dataset with product categories.
- Generate vector embedding of product description using Amazon Bedrock's foundation model 'amazon.titan-embed-text-v1'.  
- Store product data including vector embeddings into Amazon PostgreSQL vector store.
- Import libraries for PCA (Principal Component Analysis).
- Convert high dimensional vector embeddings into 3 dimensional embeddings using PCA.
- Generate scattered graph for this 3-dimensional embeddings and visualize semantic similarities in the data.

## Step by Step implementation

Refer [Visualizing_vector_embeddings.ipynb](Visualizing_vector_embeddings.ipynb)


## License
- This library is licensed under the MIT-0 License. See the LICENSE file.


