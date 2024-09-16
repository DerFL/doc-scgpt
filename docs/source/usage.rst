Usage
=====

.. _installation:

Installation
------------

scGPT is available on PyPI. To install scGPT, run the following command:

.. code-block:: console

   (.venv) $ pip install scgpt


[Optional] We recommend using wandb for logging and visualization.

.. code-block:: console

   (.venv) $ pip install wandb

For developing, we are using the Poetry package manager. To install Poetry, follow the instructions here.

.. code-block:: console

   (.venv) $ git clone https://github.com/bowang-lab/scGPT
   (.venv) $ cd scGPT
   (.venv) $ poetry install

.. note::

   The flash-attn dependency usually requires specific GPU and CUDA version. 
   If you encounter any issues, please refer to the flash-attn repository for 
   installation instructions. For now, May 2023, we recommend using CUDA 11.7 
   and flash-attn<1.0.5 due to various issues reported about installing new versions 
   of flash-attn.

.. Creating recipes
.. ----------------

.. To retrieve a list of random ingredients,
.. you can use the ``lumache.get_random_ingredients()`` function:

.. .. autofunction:: lumache.get_random_ingredients

.. The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
.. or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
.. will raise an exception.

.. .. autoexception:: lumache.InvalidKindError

.. For example:

.. >>> import lumache
.. >>> lumache.get_random_ingredients()
.. ['shells', 'gorgonzola', 'parsley']

