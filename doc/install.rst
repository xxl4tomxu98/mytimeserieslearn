########################
Install and contribution
########################

Dependencies
============

Seglearn is tested to work under Python 3.5.
The dependency requirements are based on the last scikit-learn release:

* scipy(>=0.17.0)
* numpy(>=1.11.0)
* scikit-learn(>=0.21.3)

Additionally, to run the examples, you need:

* matplotlib(>=2.0.0)
* keras (>=2.1.4) for the neural network examples
* pandas

In order to run the test cases, you need:

* pytest

The neural network examples were tested on keras using the tensorflow-gpu backend, which is recommended.

Installation
============

seglearn-learn is currently available on the PyPi's repository and you can
install it via `pip`::

  pip install -U seglearn

If you prefer, you can clone it and run the setup.py file. Use the following
commands to get a copy from GitHub and install all dependencies::

  git clone https://github.com/dmbee/seglearn.git
  cd seglearn
  pip install .

Or install using pip and GitHub::

  pip install -U git+https://github.com/dmbee/seglearn.git

Testing
=======

After installation, you can use `pytest` to run the test suite from seglearn's root directory::

  pytest

Contribute
==========

You can contribute to this code through Pull Request on GitHub_. Please, make
sure that your code is coming with unit tests to ensure full coverage and
continuous integration in the API.

.. _GitHub: https://github.com/dmbee/seglearn/pulls
