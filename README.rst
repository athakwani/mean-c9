This dupper template repository is for `Mean Stack <https://github.com/linnovate/mean>`_ + `Cloud 9 SDK <https://github.com/c9/core>`_ (c9).

Mean stack + C9
===============

This template install `Mean stack <https://github.com/linnovate/mean>`_ and `Cloud 9 SDK <https://github.com/c9/core>`_. You can start mean stack with c9 sdk using below commands:

.. code-block:: bash

  dupper dup --template-from=https://github.com/athakwani/mean-c9 https://github.com/linnovate/mean
  dupper exec mean c9
  
    
Commands
========

* start - Starts mean stack

.. code-block:: bash

    Usage:
    dupper exec mean start

* stop - Stops mean stack

.. code-block:: bash

    Usage:
    dupper exec mean stop

* debug - Start node debugger

.. code-block:: bash

    Usage:
    dupper exec mean debug

* logs - Display gulp output

.. code-block:: bash

    Usage:
    dupper exec mean logs
* c9 - Start Cloud 9 SDK
    
.. code-block:: bash

    Usage:
    dupper exec mean c9
