.. _provider_rust:

QRMI Provider - Examples in Rust
================================

.. container:: buttons

   `GitHub`_

.. _GitHub: https://github.com/qiskit-community/qrmi/tree/main/examples/qrmi/rust/resource_providers

--------------

Prerequisites
-------------

-  Python 3.11 or 3.12
-  Build the :ref:`QRMI Rust library <install_source>`


How to build `this example`_
----------------------------

.. _this example: https://github.com/qiskit-community/qrmi/tree/main/examples/qrmi/rust/resource_providers

<<<<<<< HEAD
.. code-block:: bash
=======
.. code-block:: shell-session
>>>>>>> 5cc446c (Merge sphinx integration (#5))

   cargo clean
   cargo build --release


How to run `this example`_
--------------------------

<<<<<<< HEAD
.. code-block:: bash
=======
.. code-block:: shell-session
>>>>>>> 5cc446c (Merge sphinx integration (#5))

   QRMI Provider Example

   Usage: qrmi-example-provider [OPTIONS] <CONFIG_FILE> <RESOURCE_NAME>

   Arguments:
     <CONFIG_FILE>    Path to qrmi_config.json
     <RESOURCE_NAME>  Name of the dynamic resource definition (is_dynamic=true)

   Options:
     -f, --filters <FILTERS>  Optional filter string e.g. "num_qubits=127&name=ibm_*"
     -h, --help               Print help
     -V, --version            Print version

For example:

<<<<<<< HEAD
.. code-block:: bash
=======
.. code-block:: shell-session
>>>>>>> 5cc446c (Merge sphinx integration (#5))

   ../target/release/qrmi-example-provider /etc/slurm/qrmi_config.json ibm_inst1 -f "num_qubits=127&max_shots=10000"
   Filters: num_qubits=127&max_shots=10000

   Available resources (3 found):
   ----------------------------------------
     ibm_fez                        type=ibm-quantum-compute-service    accessible=true
     ibm_marrakesh                  type=ibm-quantum-compute-service    accessible=true
     ibm_kingston                   type=ibm-quantum-compute-service    accessible=true

   Least busy resource:
     ibm_fez
