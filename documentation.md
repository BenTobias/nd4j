---
layout: page
title: "ND4J Syntax"
description: ""
---
{% include JB/setup %}

|Method| Meaning| Type |
|:----------|:-------------:| ----:|
|abs(IComplexNDArray ndarray)| abs(x)|
|applyDerivative(INDArray input)|Applies the derivative of a transform function to the param input|
|cosineSim(INDArray d1, INDArray d2)|Measures the cosine of the angle between two vectors of an inner product space||
|downSample(INDArray d1, int[] stride)|Decreases the sampling rate by integer factor (stride)|Signal processing|
|eigenvalues(INDArray A)|Computes the eigenvalues of a general matrix.|
|eigenvectors(INDArray A)|Computes the eigenvalues and eigenvectors of a general matrix. For matlab users note the following from their documentation: The columns of V present eigenvectors of A. The diagonal matrix D contains eigenvalues. This is in reverse order of Matlab's eig(A) call.|
|exp()|The e^x function|Activation|
|hardTanh|Hard Tanh is tanh constraining input to -1 to 1|Activation|
|identity|||
|linear()|Linear activation function, just returns the input as is|Activation|
|maxout()|Max out activation: max of input(i,j)|Activation|
|rectifiedLinear()|Rectified linear, the output: rounded|Activation|
|roundedlinear()|Rounded linear, the output: rounded|Activation|
|tanh()|Hyperbolic tangent: a sigmoidal function|Activation|
|sigmoid()|An s-shaped function for logistic regression|Activation|
|softmax()|Softmax function used for multinomial classification|Activation|
|softMaxRows()|Softmax with row wise features|Activation|
|symmetricGeneralizedEigenvalues(INDArray A)|Computes generalized eigenvalues of the problem A x = L B x.|
|symmetricGeneralizedEigenvalues(INDArray A, INDArray B)|Compute generalized eigenvalues of the problem A x = L B x.|
|unitVec||
|upSample(INDArray d, INDArray scale)|Upsampling a signal (specifically the first 2 dimensions)|Signal processing|