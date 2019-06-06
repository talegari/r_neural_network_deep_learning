# Neural network and Deep learning libraries for R

This is a curated list of libraries and frameworks for Neural network and deep learning in `R`. Please feel free to contribute.

| package | description |
|---------|-------------|
| [NeuralSens](https://cran.r-project.org/web/packages/NeuralSens/index.html) | Analysis functions to quantify inputs importance in neural network models. Functions are available for calculating and plotting the inputs importance and obtaining the activation function of each neuron layer and its derivatives. The importance of a given input is defined as the distribution of the derivatives of the output with respect to that input in each training data point. |
| [deepNN](https://CRAN.R-project.org/package=deepNN)  | Implementation of some Deep Learning methods. Includes multilayer perceptron, different activation functions, regularisation strategies, stochastic gradient descent and dropout |
| [ruta](https://github.com/fdavidcl/ruta) | unsupervised deep neural networks, from building their architecture to their training and evaluation built on top of keras and tensorflow |
| [kerasformula](https://cran.r-project.org/web/packages/kerasformula/index.html) | Adds a high-level interface for 'keras' neural nets. kms() fits neural net and accepts R formulas to aid data munging and hyperparameter selection. kms() can optionally accept a compiled keras_sequential_model() from 'keras'. kms() accepts a number of parameters (like loss and optimizer) and splits the data into sparse test and training matrices. kms() returns a single object with predictions, a confusion matrix, and function call details |
| [BoltzMM](https://cran.r-project.org/web/packages/BoltzMM/index.html) | Provides probability computation, data generation, and model estimation for fully-visible Boltzmann machines. It follows the methods described in Nguyen and Wood (2016a) <doi:10.1162/NECO_a_00813> and Nguyen and Wood (2016b) <doi:10.1109/TNNLS.2015.2425898> |
| [monmlp](https://cran.r-project.org/web/packages/monmlp/index.html) | Train and make predictions from a multi-layer perceptron neural network with optional partial monotonicity constraints |
| [keras](https://rstudio.github.io/keras) | Rstudio's R keras interface |
| [kerasR](https://github.com/statsmaths/kerasR) | R interface to the keras library by Taylor Arnold |
| [tensorflow](https://tensorflow.rstudio.com/) | Interface to tensorflow |
| [nnet](https://cran.r-project.org/web/packages/nnet/index.html) | Software for feed-forward neural networks with a single hidden layer, and for multinomial log-linear models | 
| [neuralnet](https://cran.r-project.org/web/packages/neuralnet/) | Training of neural networks using backpropagation, resilient backpropagation with (Riedmiller, 1994) or without weight backtracking (Riedmiller and Braun, 1993) or the modified globally convergent version by Anastasiadis et al. (2005). The package allows flexible settings through custom-choice of error and activation function. Furthermore, the calculation of generalized weights (Intrator O & Intrator N, 1993) is implemented |
| [NeuralNetTools](https://cran.r-project.org/web/packages/NeuralNetTools/index.html) | Visualization and analysis tools to aid in the interpretation of neural network models. Functions are available for plotting, quantifying variable importance, conducting a sensitivity analysis, and obtaining a simple list of model weights |
| [RSNNS](https://cran.r-project.org/web/packages/RSNNS/index.html) | The Stuttgart Neural Network Simulator (SNNS) is a library containing many standard implementations of neural networks. This package wraps the SNNS functionality to make it available from within R. Using the RSNNS low-level interface, all of the algorithmic functionality and flexibility of SNNS can be accessed. Furthermore, the package contains a convenient high-level interface, so that the most common neural network topologies and learning algorithms integrate seamlessly into R | 
| [FCNN4R](https://cran.r-project.org/web/packages/FCNN4R/index.html) | Provides an interface to kernel routines from the FCNN C++ library. FCNN is based on a completely new Artificial Neural Network representation that offers unmatched efficiency, modularity, and extensibility. FCNN4R provides standard teaching (backpropagation, Rprop, simulated annealing, stochastic gradient) and pruning algorithms (minimum magnitude, Optimal Brain Surgeon), but it is first and foremost an efficient computational engine. Users can easily implement their algorithms by taking advantage of fast gradient computing routines, as well as network reconstruction functionality (removing weights and redundant neurons, reordering inputs, merging networks). Networks can be exported to C functions in order to integrate them into virtually any software solution. |
| [softmaxreg](https://cran.r-project.org/web/packages/softmaxreg/) | Implementation of 'softmax' regression and classification models with multiple layer neural network. It can be used for many tasks like word embedding based document classification, 'MNIST' dataset handwritten digit recognition and so on. Multiple optimization algorithm including 'SGD', 'Adagrad', 'RMSprop', 'Moment', 'NAG', etc are also provided. |
| [DARCH](https://cran.r-project.org/web/packages/darch/index.html) | The darch package is built on the basis of the code from G. E. Hinton and R. R. Salakhutdinov (available under Matlab Code for deep belief nets). This package is for generating neural networks with many layers (deep architectures) and train them with the method introduced by the publications "A fast learning algorithm for deep belief nets" (G. E. Hinton, S. Osindero, Y. W. Teh 2006) and "Reducing the dimensionality of data with neural networks" (G. E. Hinton, R. R. Salakhutdinov (2006). This method includes a pre training with the contrastive divergence method published by G.E Hinton (2002) and a fine tuning with common known training algorithms like backpropagation or conjugate gradients. Additionally, supervised fine-tuning can be enhanced with maxout and dropout, two recently developed techniques to improve fine-tuning for deep learning. |
| [deeplearning](https://cran.r-project.org/web/packages/deeplearning/index.html) | An implementation of deep neural network with rectifier linear units trained with stochastic gradient descent method and batch normalization. A combination of these methods have achieved state-of-the-art performance in ImageNet classification by overcoming the gradient saturation problem experienced by many deep architecture neural network models in the past. In addition, batch normalization and dropout are implemented as a means of regularization. The deeplearning package is inspired by the darch package and uses its class DArch. |
| [deepnet](https://cran.r-project.org/web/packages/deepnet/index.html) | Implement some deep learning architectures and neural network algorithms, including BP,RBM,DBN,Deep autoencoder and so on |
| [rnn](https://cran.r-project.org/web/packages/rnn/index.html) | Implementation of a Recurrent Neural Network in R including GRU, LSTM |
| [rbm](https://github.com/zachmayer/rbm) | Restricted Boltzmann Machines in R(also see [Landgraf's implementaion](http://andland.github.io/blog/2013/01/14/restricted-boltzmann-machines-in-r/)) |
| [RcppDL](https://cran.r-project.org/web/packages/RcppDL/index.html) | This package is based on the C++ code from Yusuke Sugomori, which implements basic machine learning methods with many layers (deep learning), including dA (Denoising Autoencoder), SdA (Stacked Denoising Autoencoder), RBM (Restricted Boltzmann machine) and DBN (Deep Belief Nets). |
| [h20 DeepLearning](http://docs.h2o.ai/h2o-tutorials/latest-stable/tutorials/deeplearning/index.html) | Deep Learning: Model high-level abstractions in data by using non-linear transformations in a layer-by-layer method. Deep learning is an example of unsupervised learning and can make use of unlabeled data that other algorithms cannot. Also see, [deepwater](https://github.com/h2oai/deepwater) |
| [mxnet](https://github.com/dmlc/mxnet) | Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler |
| [TensorFlow](https://rstudio.github.io/tensorflow/) | TensorFlow is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. TensorFlow was originally developed by researchers and engineers working on the Google Brain Team within Google’s Machine Intelligence research organization for the purposes of conducting machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well. |
| [autoencoder](https://cran.r-project.org/web/packages/autoencoder/index.html) | Implementation of the sparse autoencoder in R environment, following the notes of [Andrew Ng](http://www.stanford.edu/class/archive/cs/cs294a/cs294a.1104/sparseAutoencoder.pdf). The features learned by the hidden layer of the autoencoder (through unsupervised learning of unlabeled data) can be used in constructing deep belief neural networks |
| [SAENET](https://cran.r-project.org/web/packages/SAENET/index.html) | An implementation of a stacked sparse autoencoder for dimension reduction of features and pre-training of feed-forward neural networks with the 'neuralnet' package is contained within this package. The package also includes a predict function for the stacked autoencoder object to generate the compressed representation of new data if required. For the purposes of this package, 'stacked' is defined in line with http://ufldl.stanford.edu/wiki/index.php/Stacked_Autoencoders . The underlying sparse autoencoder is defined in the documentation of 'autoencoder'. |
| [nnetpredint](https://cran.r-project.org/web/packages/nnetpredint/index.html) | Computing prediction intervals of neural network models (e.g.backpropagation) at certain confidence level. It can take the output from models trained by other packages like 'nnet', 'neuralnet', 'RSNNS', etc |
| [deepr](https://github.com/woobe/deepr) | An R package to streamline the training, fine-tuning and predicting processes for deep learning based on `darch` and `deepnet` |
| [pnn](https://cran.r-project.org/web/packages/pnn/index.html) | Probabilistic neural networks: The program pnn implements the algorithm proposed by Specht (1990). It is written in the R statistical language. It solves a common problem in automatic learning. Knowing a set of observations described by a vector of quantitative variables, we classify them in a given number of groups. Then, the algorithm is trained with this datasets and should guess afterwards the group of any new observation. This neural network has the main advantage to begin generalization instantaneously even with a small set of known observations. It is delivered with four functions (learn, smooth, perf and guess) and a dataset. The functions are documented with examples and provided with unit tests. |
| [qrnn](https://cran.r-project.org/web/packages/qrnn/index.html) | Quantile Regression Neural Network: Fit a quantile regression neural network with optional left censoring using a variant of the finite smoothing algorithm. |
| [validann](https://cran.r-project.org/web/packages/validann/index.html) | Validation Tools for Artificial Neural Networks. Methods and tools for analysing and validating the outputs and modelled functions of artificial neural networks (ANNs) in terms of predictive, replicative and structural validity. Also provides a method for fitting feed-forward ANNs with a single hidden layer. |
| [TeachNet](https://cran.r-project.org/web/packages/TeachNet/index.html) | Fits neural networks to learn about back propagation. Can fit neural networks with up to two hidden layer and two different error functions. Also able to handle a weight decay. But just able to compute one output neuron and very slow |
| [neural](https://cran.r-project.org/web/packages/neural/index.html) | RBF and MLP neural networks with graphical user interface |
| [monmlp](https://cran.r-project.org/web/packages/monmlp/index.html) | Monotone Multi-Layer Perceptron Neural Network. Train and make predictions from a multi-layer perceptron neural network with partial monotonicity constraints. |
| [learNN](https://cran.r-project.org/web/packages/learNN/index.html) | Examples of Neural Networks. Implementations of several basic neural network concepts in R, as based on posts on http://qua.st/ |
| [grnn](https://cran.r-project.org/web/packages/grnn/index.html) | The program GRNN implements the algorithm proposed by Specht (1991) |
| [GMDH](https://cran.r-project.org/web/packages/GMDH/index.html) | Short Term Forecasting via GMDH-Type Neural Network Algorithms. Group method of data handling (GMDH) - type neural network algorithm is the heuristic self-organization method for modelling the complex systems. In this package, GMDH-type neural network algorithms are applied to make short term forecasting for a univariate time series |
| [elmNNRcpp](https://CRAN.R-project.org/package=elmNNRcpp) | Training and predict functions for Single Hidden-layer Feedforward Neural Networks (SLFN) using the Extreme Learning Machine (ELM) algorithm. The ELM algorithm differs from the traditional gradient-based algorithms for very short training times (it doesn't need any iterative tuning, this makes learning time very fast) and there is no need to set any other parameters like learning rate, momentum, epochs, etc. This is a reimplementation of the 'elmNN' package using 'RcppArmadillo' after the 'elmNN' package was archived. For more information, see "Extreme learning machine: Theory and applications" by Guang-Bin Huang, Qin-Yu Zhu, Chee-Kheong Siew (2006), Elsevier B.V, <doi:10.1016/j.neucom.2005.12.126> |
| [brnn](https://cran.r-project.org/web/packages/brnn/index.html) | Bayesian Regularization for Feed-Forward Neural Networks |
| [AMORE](https://cran.r-project.org/web/packages/AMORE/index.html) | This package was born to release the TAO robust neural network algorithm to the R users. It has grown and I think it can be of interest for the users wanting to implement their own training algorithms as well as for those others whose needs lye only in the "user space" |
| [simpleNeural](https://cran.r-project.org/web/packages/simpleNeural/index.html) | An Easy to Use Multilayer Perceptron. Trains neural networks (multilayer perceptrons with one hidden layer) for bi- or multi-class classification |
