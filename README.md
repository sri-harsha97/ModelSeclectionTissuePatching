This case study deals with performing model selection using clustering algorithm for 5000 colorectal tissue patches. It consists of 9 tissue types which are:
• Adipose (ADI)
• background (BACK)
• debris (DEB)
• lymphocytes (LYM)
• mucus (MUC)
• smooth muscle (MUS)
• normal colon mucosa (NORM)
• cancer-associated stroma (STR)
• colorectal adenocarcinoma epithelium (TUM)

Clustering is a form of unsupervised learning algorithm which groups data objects in a way that the objects in a group are similar to each other. Clustering can be achieved using different algorithms like:
• K-means
• Gaussian Mixture Model
• Hierarchical Clustering
• Louvain Clustering
Processing of data:
Two reduction methods – PCA and UMAP, have been applied to the 5000 images. The four different representations are – PathologyGAN, ResNet50, InceptionV3, VGG16.
This case study is about finding the optimal clustering algorithm based on the number of clusters each clustering methods produce.
The optimal number of clusters can be found using:
1. Silhouette 
2. V-measure
