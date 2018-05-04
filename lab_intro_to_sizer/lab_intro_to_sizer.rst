.. _intro_to_sizer:

--------------------
Lab - Intro to Sizer
--------------------

Overview
++++++++

Learn how Nutanix engineers and partners can leverage the Sizer tool to select the right combination of hardware.

In this exercise you will log into Sizer, and work through a basic sizing. This will allow you to get comfortable in the Sizer tool.

Basic Sizing
++++++++++++

Open http://sizer.nutanix.com

.. figure:: images/intro_to_sizer_01.png

Login with your **My Nutanix Login** credentials.

Click **+ Create New Scenario**, and create a demo Scenario.

.. figure:: images/intro_to_sizer_02.png

Enter a **Scenario Name**.

Highlight the different vendor hardware models that support Nutanix software.

.. figure:: images/intro_to_sizer_03.png

Highlight the scenario objective fields, and why it is important to put as much info in as possible.

.. figure:: images/intro_to_sizer_04.png

Click **+ Add Workload**.

.. figure:: images/intro_to_sizer_05.png

Enter a **Workload Name**.

Highlight the different workload types.

.. figure:: images/intro_to_sizer_06.png

Select **Server Virtualization**, and click **Next**.

Fill out the following fields and click **Save**:

- **Server Profile Size** - Large
- **Number of VM's** - 100
- **Container Replication Factor** - RF2
- **Disable Compression for Pre-Compressed Data** - No
- **Erasure Coding** - Unchecked
- **Block Awareness** - Unchecked
- **Encrypt Storage for VM** - Unchecked
- **Data Protection** - No

.. figure:: images/intro_to_sizer_07.png

Click **Modify** in the **Sizing Options** section.

.. figure:: images/intro_to_sizer_08.png

Highlight the different **Sizing Options** under **Automatic**.

.. figure:: images/intro_to_sizer_09.png

Highlight the different changes you can make under **Manual**.

.. figure:: images/intro_to_sizer_10.png

.. figure:: images/intro_to_sizer_11.png

Highlight and explain **Sizing Details**.

.. figure:: images/intro_to_sizer_12.png

Highlight and explain **Sizing Charts**.

.. figure:: images/intro_to_sizer_13.png

Highlight and explain **Financial Analysis**.

.. figure:: images/intro_to_sizer_14.png

Highlight and explain **Rack View**.

.. figure:: images/intro_to_sizer_15.png

Click the :fa:`ellipsis-v`, and then click **Download BOM**.

.. figure:: images/intro_to_sizer_16.png

Ensure that all options are checked, and click **Download**.

.. figure:: images/intro_to_sizer_17.png

Download and Review the BOM.

:download:`BOM-Workshop_Demo.pdf <./BOM-Workshop_Demo.pdf>`

Takeaways
+++++++++

- Sizer is an excellent tool to ensure a coorectly sized Nutanix Software solution.
-	Sizer is available for customers and prospects here: \http://go.nutanix.com/size-your-data-center.html
- Demo Video on YouTube: \https://www.youtube.com/watch?v=uS8C5bzYr_s
