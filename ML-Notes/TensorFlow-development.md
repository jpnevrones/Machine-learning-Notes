
- Technical Requirement to start with tensorflow
  - Anaconda and python- 3.6.2 or higher (my perfrence), please free to check the [link](https://www.tensorflow.org/install/) to explore more option
  - IDE - Pycharm 
  - python packages : numpy, pandas, scikit-learn, scipy
- [Installing tensorflow](https://www.tensorflow.org/install/)

### Understanding TensorFlow  
- Tensorflow is software framework for developipng machine elarning algorithm developed by google. TF has all the basic building block required 
to build machine learning algorithm (simple to complex deep learning model). TF is not the only option avaliable, we have theanos, 
keras(wrapper for tensorflow and theanos - good for prototyping), caffe, pythorch
- `Tensor` - Basically are Multidimensional array 
- At the core we TF enable us to define a mathematical operation as graph of smaller operation. Which ideally mean we can use tensorflow to design 
anything which takes inoput data and computes an outcome based on some mathematical formula. Here we go machine is bunch of mathematical formulas.
- TF core execution engine is written in C++, TF allow other languages like python to control the core execution written in C++
- `Session` is an object of TF responsible for running the operation on the graph and track satre of each node in the graph. For tranining we craete a session and call all train operation. ach time the training operation runs, we'll pass a new training data that will 
be used for that training pass. And then we'll check the current accuracy by calling the loss function. While the training process 
is running, we can watch the results graphically using a separate tool called `TensorBoard`. 
- 
