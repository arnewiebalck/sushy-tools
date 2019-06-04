
============
Contributing
============

.. include:: ../../../CONTRIBUTING.rst


Cloning the sushy-tools repository
++++++++++++++++++++++++++++++++++

If you haven't already, sushy-tools source code should be pulled directly
from git.

.. code-block:: bash

    # from your home or source directory
    cd ~
    git clone https://opendev.org/openstack/sushy-tools


Running the emulators locally
+++++++++++++++++++++++++++++

Run the unit tests and activate the virtual environment:

.. code-block:: bash

    tox -e py3
    source .tox/py3/bin/activate

Now, you can run your choice of emulator. For instance, to run the dynamic
emulator:

.. code-block:: bash

    sushy-emulator

More information on running the emulators, refer to the user docs for the
dynamic-emulator and the static-emulator.