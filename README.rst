This dupper template repository is for mean stack `linnovate/mean <https://github.com/linnovate/mean>`_ + Cloud 9 development environment SDK (c9).

Mean stack + C9
===============

This template install `mean stack <https://github.com/linnovate/mean>`_ and `Cloud 9 SDK <https://github.com/c9/core>`_. You can start mean stack with c9 sdk using below commands:

.. code-block:: bash

  dupper dup --template-from=https://github.com/athakwani/mean-c9 https://github.com/linnovate/mean
  dupper exec mean c9
  
Dependencies
============

* mongodb
* nodejs
* npm
* bower
* gulp
* npm packages
* bower packages
* build-essential 
* g++
* curl
* libssl-dev
* apache2-utils
* libxml2-dev
* sshfs 
* python2.7 
* python2.7-dev
* `c9-sdk <https://github.com/c9/core>`_
    
Commands
========

* deploy - Start mean stack

.. code-block:: bash

    Usage:
    dupper exec mean deploy

* c9 - Start Cloud 9 SDK
    
.. code-block:: bash

    Usage:
    dupper exec mean c9
