# ML with graph representation

 * CS224W (Jure Leskovec): http://web.stanford.edu/class/cs224w/
 * Types of prediction problems: node, link, graph property
 * Early research on embeddings then GNN

## Advantage of graph representation

 * Challege of feature engineering: how to preserve the relationship between entities
 * Graph embeddings: automate feature engineering while keeping the topological and semantic information (relation) between entities
 * [Classic methods](https://towardsdatascience.com/overview-of-deep-learning-on-graph-embeddings-4305c10ad4a4): DeepWalk, node2vec, LINE
 * Classic methods are inspired by word3vec, [skip-gram](https://towardsdatascience.com/word2vec-skip-gram-model-part-1-intuition-78614e4d6e0b)

## Heterogeneous bipartite graphs

 * Transactions can be represented like [bipartite graphs](https://www.capitalone.com/tech/machine-learning/learning-embeddings-of-financial-graphs/)
 * DeepTrax (Capital One): https://arxiv.org/pdf/1907.07225.pdf (link prediction)
 * Heterogeneous graph embeddings with [metapath2vec](https://ericdongyx.github.io/papers/KDD17-dong-chawla-swami-metapath2vec.pdf)


