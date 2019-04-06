# Why Neural Networks

This repository contains all the supporting material for the talk made at [Apache Spark and More Milano](https://www.meetup.com/Spark-More-Milano/)
The slides are interactive and can be run during the presentation.

## Setup

1. setup [anaconda](https://www.anaconda.com/download/#linux) or [miniconda](https://conda.io/miniconda.html)
2. create a virtual environment
  ```
  # please use python 3 :)
  $conda create --name dl python=3.6

  #activate the environment
  source activate dl
  ```
3. install the needed libraries
  ```
  $pip install -r requirements.txt
  ```

4. Install RISE from conda forge
  ```
  $conda install -c conda-forge rise
  ```

4. run the [jupyter](http://jupyter.org/) notebook service
  ```
  $ jupyter notebook
  ```

If you want to get more information about anaconda and jupyter check the [presentation + tutorials](https://github.com/fabiofumarola/anaconda_jupyter_tutorial) made for the [School of Artificial Intelligence at PiCampus](http://picampus-school.com/).

## Reference and Interesting Links

### Suggested Books

1. [Manning: Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python): really good for a high level introduction of arguments and ideas
2. [Deep Learning](http://www.deeplearningbook.org/): very good for a deep down
3. [Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
4. [Machine Learning: A Probabilistic Perspective](https://doc.lagout.org/science/Artificial%20Intelligence/Machine%20learning/Machine%20Learning_%20A%20Probabilistic%20Perspective%20%5BMurphy%202012-08-24%5D.pdf)

### MOOC

1. [coursera deep learning specialization](https://www.coursera.org/specializations/deep-learning)
2. [MIT intro to deep learning](http://introtodeeplearning.com/index.html)

### Pretrained Models

1. [model zoo](https://modelzoo.co/)
2. [tensorflow-hub](https://www.tensorflow.org/hub/)
3. [tensorflow models](https://github.com/tensorflow/models)
4. [papers with code](https://paperswithcode.com/)

### libraries

1. [keras](https://keras.io/)
1. [tensorflow](https://www.tensorflow.org/)
2. [pytorch](https://pytorch.org/)

## Bonus

In the data folder there is a dataset that you can use as exercise ;)
