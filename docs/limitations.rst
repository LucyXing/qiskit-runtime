.. _limitations:

===================
Runtime limitations
===================

- **Currently in private beta**
   
   The Qiskit runtime is currently in private beta testing with members of the
   IBM Quantum Network.  A general release will follow after this testing is
   completed. 

- **Limited quantum systems available for qiskit runtime**
   
   Currently only the *ibmq_montreal* and *ibmq_qasm_simulator* are accessible
   via the Qiskit runtime architecture.

- **Five circuit limit per circuit runner job**

   The current Qiskit runtime was designed for executing program scripts   
   and is not tailored to large batches of quantum circuits.  As such, there
   is a size limitation that translates into roughly a five circuit maximum
   per job.

.. Hiding - Indices and tables
   :ref:`genindex`
   :ref:`modindex`
   :ref:`search`
