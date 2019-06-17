.. _howto/providers/azure:

==================================================
Perform common Microsoft Azure configuration tasks
==================================================

This page lists various common tasks you can perform on your
Microsoft Azure virtual machine.

.. _howto/providers/azure/resize:

Deleting or stopping your virtual machine
===========================================

After you have finished using your TLJH you might wanto to either Stop or completely delete the Virtual Machine to avoid incurring in subsequent costs. 
The difference between these two approaches is that **Stop** will keep the VM resources but will effectively stop any compute / runtime activities. 
If you choose to delete the VM then all the resources associated with it will be wiped out.

To do either of this:

* Go to "Virtual Machines"
* Click on your machine name
* Click on "Stop" to stop the machine temporarily, or "Delete" to delete it permanently.

    .. image:: ../../images/providers/azure/delete-vm.png
        :alt: Delete vm

.. note:: It is important to mention that even if you stop the machine you will still be charged for the use of the data disk.
