.. _what_is_sizer:

--------------
What is Sizer
--------------

Accessing Sizer
+++++++++++++++

\http://sizer.nutanix.com or \http://my.nutanix.com, then choose: **Sizer**

What is Sizer
+++++++++++++

Sizer is a web based tool developed to take complex workloads, and recommend Nutanix nodes to meet the workload requirements.

Sizer has the following Hardware Support:

- Nutanix
- Dell/EMC
- Lenovo
- IBM Power
- Cisco
- HPE
- Fujitsu

Sizer also has the following Workload Support:

- VDI
- RDSH/XenApp
- Server Virtualization
- MS SQL Server
- Splunk
- RAW Input
- File Services

Other key benefits include:

- RV Tools Import
- Sizing for Mixed Workloads within a cluster
- Homogeneous and Heterogeneous node mix
- Automatic recommended sizing, as well as Manual override option

What Information Do You Need to do a Sizing
+++++++++++++++++++++++++++++++++++++++++++

When doing a sizing, there is some basic information you need. Depending on the workloads you are sizing for, there may be some additional information you need to collect from the customer or prospect.

Basic Information Needed
........................

To properly size a Nutanix platform, you need to know the profile of each workload that is going to run on the platform:

- Hypervisor
- Type of workload: Server, VDI, DB (SQL Server, Oracle), File Services, Etc.
- Number of VMs and/or VDI
- Per VM Specs (vCPU | Mem | Disk)
- Space optimization services: deduplication, compression, Etc.
- Protection mechanisms needed to guarantee SLAs (DR, Replication, etc.)
- RVTools or Dell Live Optics (formerly DPACK).

What to ask for? Workload: Servers
..................................

The following are some additional things you will want to ask for when doing a Server Virtualization sizing:

- Categorize VM’s into workloads.. Test/Dev, BCA etc.
- What are the applications ? Find out as much as possible about them.
- CPU Requirements - CPU – Speed/Cores of current CPU, vCPUs allocated to VMs.
- vCPU|Core ratio Ratio - start with:
  - BCA’s 1:1 (sometimes 2:1)
  - General Server 4:1
- RAM - How much physical memory they currently have, Amount of Mem assigned to VMs, How much of that is actually used (don’t overcommit).
- Storage – How much Storage to currently have, Storage allocated to VMs, How much of that is actually used, and amount of useable Storage does prospect want after account for workloads.
- OS Drive Size?
- Data Drive Size?
- IOPS, mbps?
- RPO’s, RTO’s, Availability, DR requirements?

What to ask for? Workload: VDI
..............................

The following are some additional things you will want to ask for when doing a VID/EUC sizing:

- VDI Broker (Citrix XenDesktop or VMware Horizon View).
- What types of users, and how many of each type.
- Provisioning type (MCS, PVS, Linked Clone, Full Clone, Non-Persistent, Persistent).
- vCPU | Core ratio (If Known).
- Per VM Specs:
  - vCPU
  - MEM
  - Disk size (OS Image & App Size)
- IOPS (If known).
- GPU Needs – what profile type do they need for vGPU.
- Anti-Virus/Security software overhead.
- User/VDI growth expectations.

What to ask for? Workload: Databases
....................................

The following are some additional things you will want to ask for when doing a Database sizing:

- Number of Database VMs, DB’s, Schemas etc.
- Profile of each Database VM (vCPUs/MEM/Number of Disks and Size of Each).
- Database type – OLTP, Batch, DSS.
- How many of each database profile?
- Database VM IOPs.
- Database VM working set size/Change rate.
- Size of the largest Database?
- Are they using Failover clustering?
- How are they licensed?
- What is the RPO/RTO/Availability and DR Requirements?

What to ask for? Workload: Exchange
...................................

The following are some additional things you will want to ask for when doing a Exchange sizing:

- Version of Exchange (2010, 2013).
- Number of Mailboxes.
- Messages/Day averages for mailboxes  (if unknown, can assume 100 or 150 msgs/day).
- Average email size (if unknown, can assume 75Kb).
- Average mailbox size.
- Availability and DAG design (Active/Passive Multi-site, Active/Active Multi-site and then DAG=2 or DAG=2+LAG).
- External devices – iphones, activesync, blackberry etc.
- Utilize the exchange role requirements calculator.
- Utilize the Processor Query tool to determine megacycle requirements.
