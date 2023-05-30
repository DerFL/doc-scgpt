Welcome to scGPT's documentation!
===================================

Generative pre-trained models have achieved remarkable success 
in various domains such as natural language processing and computer vision. 
Specifically, the combination of large-scale diverse datasets and pre-trained 
transformers has emerged as a promising approach for developing foundation models. 
While texts are made up of words, cells can be characterized by genes. 
This analogy inspires us to explore the potential of foundation models for 
cell and gene biology. By leveraging the exponentially growing single-cell sequencing 
data, we present the first attempt to construct a single-cell foundation model through 
generative pre-training on over 10 million cells. We demonstrate that the generative 
pre-trained transformer, scGPT, effectively captures meaningful biological insights 
into genes and cells. Furthermore, the model can be readily finetuned to achieve 
state-of-the-art performance across a variety of downstream tasks, including multi-batch 
integration, multi-omic integration, cell-type annotation, genetic perturbation prediction, 
and gene network inference.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
