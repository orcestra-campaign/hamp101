.. _getstart:

Getting Started
===============

Clone hamp101's GitHub repository:

.. code-block:: console

  $ git clone https://github.com/orcestra-campaign/hamp101.git

and then create an environment with the necessary dependencies installed (e.g. using micromamba,
or conda as listed in the environment.yaml):

.. code-block:: console

  $ micromamba env create -f environment.yaml
  $ micromamba activate hamp101env

Finally install the pre-commit hooks:

.. code-block:: console

  $ pre-commit install

which will be used when you try to commit something or you execute ``pre-commit run``. You can learn
more about the powers of pre-commit from `their documentation: <https://pre-commit.com>`_.

That's it, you're done! But maybe now you want to customise the project and push it to your own
GitHub repo...
