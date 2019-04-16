# Recommender-System-Project
Resources for Deep Recommender System

### Tools

- deep learning frame: 
  - tensorflow/keras
    - [tutorial](https://jacobbuckman.com/post/tensorflow-the-confusing-parts-1/)
    - [tutorial](https://github.com/aymericdamien/TensorFlow-Examples)
  - pytorch 
    - [tutorial](https://pytorch.org/tutorials/)
- data preprocess (python library):
  - pandas
  - scipy  

### Overview/Backgroud - (must know)

- [matrix factorization techniques for recommender systems](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)
- SVD++ ([paper](https://www.cs.rochester.edu/twiki/pub/Main/HarpSeminar/Factorization_Meets_the_Neighborhood-_a_Multifaceted_Collaborative_Filtering_Model.pdf))
- implicit ALS ([paper](http://yifanhu.net/PUB/cf.pdf))



### Evaluation Method/ Metric - (must know)

- HR ([blog](https://towardsdatascience.com/evaluating-a-real-life-recommender-system-error-based-and-ranking-based-84708e3285b))

- nDCG ([wiki](https://en.wikipedia.org/wiki/Discounted_cumulative_gain))

  

### Models

- SVD++ ([paper](https://www.cs.rochester.edu/twiki/pub/Main/HarpSeminar/Factorization_Meets_the_Neighborhood-_a_Multifaceted_Collaborative_Filtering_Model.pdf))

- Factorization Machine ([paper](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Rendle2010FM.pdf))

- BPR ([paper](https://arxiv.org/pdf/1205.2618.pdf))

- implicit ALS ([paper](http://yifanhu.net/PUB/cf.pdf))

- NCF  ([paper](https://www.comp.nus.edu.sg/~xiangnan/papers/ncf.pdf))
  - code
    - offical ([theano](https://github.com/hexiangnan/neural_collaborative_filtering))
    - [pytorch](https://github.com/guoyang9/NCF)

### More Models

- RBM for CF ([paper](https://www.cs.toronto.edu/~rsalakhu/papers/rbmcf.pdf))
- Probabilistic MF ([paper](https://papers.nips.cc/paper/3208-probabilistic-matrix-factorization.pdf))