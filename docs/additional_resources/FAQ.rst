.. _faq:

Frequently Asked Questions (FAQ)
================================

.. rst-class:: lead

    Answers to common questions about installing, configuring, using, and developing QRMI.

--------------

.. contents::
   :local:
   :depth: 2

--------------

<<<<<<< HEAD

=======
>>>>>>> 5cc446c (Merge sphinx integration (#5))
General Questions
-----------------

What is QRMI?
~~~~~~~~~~~~~

<<<<<<< HEAD
QRMI (Quantum Resource Management Interface) is an open-source,
vendor-neutral software layer that enables high-performance computing
(HPC) systems to access, manage, and monitor quantum computing
resources through a consistent set of APIs.

Why was QRMI created?
~~~~~~~~~~~~~~~~~~~~~

Quantum computing providers often expose different APIs, resource
models, and operational workflows. QRMI reduces this complexity by
providing a common abstraction layer that allows applications and
workload managers to interact with multiple quantum technologies
through a unified interface.
=======
QRMI (Quantum Resource Management Interface) is a vendor-agnostic software layer that enables HPC systems to access, control, and monitor quantum computing resources through a common set of APIs.

Why do we need QRMI?
~~~~~~~~~~~~~~~~~~~~

Quantum providers use different APIs and workflows, making integration complex. QRMI provides a standard interface that reduces development effort and simplifies access to multiple quantum technologies.
>>>>>>> 5cc446c (Merge sphinx integration (#5))

Is QRMI tied to a specific quantum hardware vendor?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

<<<<<<< HEAD
No. QRMI is designed to be vendor-neutral. It provides a common
interface that can be implemented for different quantum hardware and
service providers, allowing software to interact with multiple
providers without provider-specific integrations.
=======
No. QRMI is designed to be vendor-agnostic, allowing applications and schedulers to interact with different quantum systems through the same interface.
>>>>>>> 5cc446c (Merge sphinx integration (#5))

How does QRMI integrate with HPC systems?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

<<<<<<< HEAD
QRMI enables quantum devices to be represented as schedulable
resources alongside traditional HPC resources such as CPUs, GPUs,
and storage systems. This simplifies the deployment and management
of hybrid quantum-classical workflows.
=======
QRMI allows quantum devices to be managed as schedulable resources alongside traditional HPC resources such as CPUs and GPUs, making hybrid quantum-classical workflows easier to deploy.
>>>>>>> 5cc446c (Merge sphinx integration (#5))

Which workload managers are supported?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

<<<<<<< HEAD
QRMI has been demonstrated with several workload managers,
including Slurm, PBS, LSF, Grid Engine, Kubernetes, and Flux.

Support for a specific workload manager depends on the integration
being used and the capabilities provided by the local deployment.
=======
QRMI has been demonstrated with a range of workload managers, including Slurm, PBS, LSF, Grid Engine, Kubernetes, and Flux.
>>>>>>> 5cc446c (Merge sphinx integration (#5))

What programming languages does QRMI support?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

<<<<<<< HEAD
QRMI is implemented in Rust and provides APIs for Python, C, and Lua.
These interfaces enable integration with existing HPC tools, services,
and applications across a variety of computing environments.
=======
QRMI is written in Rust and provides interfaces for Python, C and Lua, allowing it to be integrated into a variety of existing software ecosystems and HPC environments.
>>>>>>> 5cc446c (Merge sphinx integration (#5))

Is QRMI open source?
~~~~~~~~~~~~~~~~~~~~

<<<<<<< HEAD
Yes. QRMI is an open-source project developed through collaboration
between HPC centres, quantum computing providers, and research
organisations.

Where can I find examples of using QRMI?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Example applications, integration guides, and reference
implementations are available in the QRMI repository and project
documentation.

How can I contribute to QRMI?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Contributions are welcome. You can contribute by reporting issues,
improving documentation, adding tests, developing new features, or
implementing support for additional quantum providers and HPC
environments.
=======
Yes. QRMI is an open-source project developed by a growing community of HPC centres, quantum providers, and research organisations.

>>>>>>> 5cc446c (Merge sphinx integration (#5))
