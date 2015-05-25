# sketch
Use RNN to model handwriting using Theano blocks.
I am trying to reproduce handwritting model given by
[Alex Graves](http://arxiv.org/abs/1308.0850),
see also his [demo](http://www.cs.toronto.edu/~graves/handwriting.html)

Dependencies
------------
* [Blocks](https://github.com/bartvm/blocks) follow
  the [install instructions](http://blocks.readthedocs.org/en/latest/setup.html).
  This will install all the other dependencies for you (Theano, Fuel, etc.).
* Download handwritting dataset using [this notebook](./handwriting-to-hdf5.ipynb)
 
Running code
------------

    python sketch.py
Generates a directory where the model is saved and
after every epoch it generate random samples of handwritting generated by the
model in `samples-sketch.png` for each example, a diagram showing where the pen
was raised is shown in `samples-pen.png`

Notes
-----
* This is a work in progress
