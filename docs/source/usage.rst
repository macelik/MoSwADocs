Usage
=====

.. _webservice:

Installation
------------

All you need to do is upload your aligned fasta file to `MoSwA WebService <http://moswa.bioinfo.perdanauniversity.edu.my/>`_

.. code-block:: console

   (.venv) $ pip install lumache

Stand Alone Installation and Usage
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

