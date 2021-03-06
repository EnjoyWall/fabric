Getting Started
===============

.. toctree::
   :maxdepth: 1

   prereqs
   samples

Install Prerequisites
^^^^^^^^^^^^^^^^^^^^^

Before we begin, if you haven't already done so, you may wish to check that
you have all the :doc:`prereqs` installed on the platform(s)
on which you'll be developing blockchain applications and/or operating
Hyperledger Fabric.

Install Binaries and Docker Images
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

While we work on developing real installers for the Hyperledger Fabric
binaries, we provide a script that will :ref:`binaries` to your system.
The script also will download the Docker images to your local registry.

Hyperledger Fabric Samples
^^^^^^^^^^^^^^^^^^^^^^^^^^

We offer a set of sample applications that you may wish to install these
:doc:`samples` before starting with the tutorials as the tutorials leverage
the sample code.

API Documentation
^^^^^^^^^^^^^^^^^

The API documentation for Hyperledger Fabric's Golang APIs can be found on
the godoc site for `Fabric <http://godoc.org/github.com/hyperledger/fabric>`_.
If you plan on doing any development using these APIs, you may want to
bookmark those links now.

Hyperledger Fabric SDKs
^^^^^^^^^^^^^^^^^^^^^^^

Hyperledger Fabric offers a number of SDKs to support various programming
languages. There are two officially released SDKs for Node.js and Java:

  * `Hyperledger Fabric Node SDK <https://github.com/hyperledger/fabric-sdk-node>`__ and `Node SDK documentation <https://fabric-sdk-node.github.io/>`__.
  * `Hyperledger Fabric Java SDK <https://github.com/hyperledger/fabric-sdk-java>`__.

In addition, there are three more SDKs that have not yet been officially released
(for Python, Go and REST), but they are still available for downloading and testing:

  * `Hyperledger Fabric Python SDK <https://github.com/hyperledger/fabric-sdk-py>`__.
  * `Hyperledger Fabric Go SDK <https://github.com/hyperledger/fabric-sdk-go>`__.
  * `Hyperledger Fabric REST SDK <https://github.com/hyperledger/fabric-sdk-rest>`__.

Hyperledger Fabric CA
^^^^^^^^^^^^^^^^^^^^^

Hyperledger Fabric provides an optional
`certificate authority service <http://hyperledger-fabric-ca.readthedocs.io/en/latest>`_
that you may choose to use to generate the certificates and key material
to configure and manage identity in your blockchain network. However, any CA
that can generate ECDSA certificates may be used.

.. Licensed under Creative Commons Attribution 4.0 International License
   https://creativecommons.org/licenses/by/4.0/
