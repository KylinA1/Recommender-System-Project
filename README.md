# Recommender-System-Project
Resources for Deep Recommender System

### Dataset

- [Retailrocket](<https://www.kaggle.com/retailrocket/ecommerce-dataset>)

### Tools

- deep learning frameworks: 
  - tensorflow/keras
    - [tutorial](https://jacobbuckman.com/post/tensorflow-the-confusing-parts-1/)
    - [tutorial](https://github.com/aymericdamien/TensorFlow-Examples)
  - pytorch 
    - [tutorial](https://pytorch.org/tutorials/)
- data preprocess (python library):
  - pandas

### Overview/Backgroud - (must know)

- [matrix factorization techniques for recommender systems](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)
- SVD++ ([paper](https://www.cs.rochester.edu/twiki/pub/Main/HarpSeminar/Factorization_Meets_the_Neighborhood-_a_Multifaceted_Collaborative_Filtering_Model.pdf))
- implicit ALS ([paper](http://yifanhu.net/PUB/cf.pdf))



### Evaluation Method/ Metric - (must know)

- HR ([blog](https://towardsdatascience.com/evaluating-a-real-life-recommender-system-error-based-and-ranking-based-84708e3285b))

- nDCG ([wiki](https://en.wikipedia.org/wiki/Discounted_cumulative_gain))

  

### Models

- Matrix factorization
  - code
    - [pytorch](https://www.ethanrosenthal.com/2017/06/20/matrix-factorization-in-pytorch/)

- SVD++ ([paper](https://www.cs.rochester.edu/twiki/pub/Main/HarpSeminar/Factorization_Meets_the_Neighborhood-_a_Multifaceted_Collaborative_Filtering_Model.pdf))
- Factorization Machine ([paper](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Rendle2010FM.pdf))
  - code
    - [pytorch](https://github.com/jmhessel/fmpytorch)
    - [sklearn](https://github.com/coreylynch/pyFM)
    - 
- BPR ([paper](https://arxiv.org/pdf/1205.2618.pdf))
  - code
    - [tensorflow](https://medium.com/radon-dev/implicit-bayesian-personalized-ranking-in-tensorflow-b4dfa733c478)
    - [Theano](https://github.com/bbc/theano-bpr/tree/master/theano_bpr)
- implicit ALS ([paper](http://yifanhu.net/PUB/cf.pdf))
  - more reading materials
    - [A Gentle Introduction to Recommender Systems with Implicit Feedback](https://jessesw.com/Rec-System/)
  - code
    - [implicit](https://github.com/benfred/implicit)
- NCF  ([paper](https://www.comp.nus.edu.sg/~xiangnan/papers/ncf.pdf))
  - code
    - offical ([theano](https://github.com/hexiangnan/neural_collaborative_filtering))
    - [tensorflow/keras](https://github.com/enningxie/Neural-Collaborative-Filtering)
    - [pytorch](https://github.com/guoyang9/NCF)

### More Models

- RBM for CF ([paper](https://www.cs.toronto.edu/~rsalakhu/papers/rbmcf.pdf))
  - code
    - [tensorflow](https://github.com/srp98/Movie-Recommender-using-RBM)
- Probabilistic MF ([paper](https://papers.nips.cc/paper/3208-probabilistic-matrix-factorization.pdf))
  - code
    - [sklearn](https://github.com/fuhailin/Probabilistic-Matrix-Factorization)
