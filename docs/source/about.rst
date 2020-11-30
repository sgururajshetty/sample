.. _about:

About HarmonyOS
================

System Positioning
+++++++++++++++++++ * **For consumers**, HarmonyOS integrates various smart devices to implement fast connection, capability collaboration, and resource sharing between different devices… * *For application developers*, HarmonyOS adopts distributed technologies to make application development possible on different device forms... * For device developers, HarmonyOS uses a component-based software design to tailor itself to particular device…Technical Architecture
++++++++++++++++++++++HarmonyOS is designed with a layered architecture, which from bottom to top consists of the kernel layer, system service layer, framework layer, and application layer.*Figure 1 Technical architecture*
.. figure:: /images/archi.png
   :alt: rest configuration
   :align: centerKernel Layer*************HarmonyOS uses a multi-kernel design (Linux kernel, HarmonyOS microkernel, or LiteOS) so that appropriate OS kernels can be selected for devices with different resource limitations. For details, see :ref:`HarmonyOS Device <main>`System Service Layer
*********************The system service layer provides a complete set of capabilities essential for HarmonyOS to offer services for applications through the framework layer.
