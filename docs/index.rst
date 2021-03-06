soundata
=======

.. toctree::
   :maxdepth: 1
   :titlesonly:



``soundata`` is an open-source Python library that provides tools for working with common Music Information Retrieval (MIR) datasets, including tools for:

 * downloading datasets to a common location and format
 * validating that the files for a dataset are all present
 * loading annotation files to a common format, consistent with ``mir_eval``
 * parsing track level metadata for detailed evaluations.


.. code-block::

    pip install soundata


For more details on how to use the library see the :ref:`tutorial`.


Citing soundata
--------------

If you are using the library for your work, please cite the version you used as indexed at Zenodo:

Coming soon...

If you refer to soundata's design principles, motivation etc., please cite the following paper:

Coming soon...

When working with datasets, please cite the version of ``soundata`` that you are using (given by the ``DOI`` above)
**AND** include the reference of the dataset, which can be found in the respective dataset loader using the ``cite()`` method.


Contributing to soundata
-----------------------

We welcome contributions to this library, especially new datasets.
Please see :ref:`contributing` for guidelines.

- `Issue Tracker <https://github.com/mir-dataset-loaders/soundata/issues>`_
- `Source Code <https://github.com/mir-dataset-loaders/soundata>`_


.. toctree::
   :caption: Get Started
   :maxdepth: 1


   source/overview
   source/quick_reference
   source/tutorial

.. toctree::
   :caption: API documentation
   :maxdepth: 1

   source/soundata

.. toctree::
   :caption: Further Information
   :maxdepth: 1

   source/contributing
   source/faq


 
