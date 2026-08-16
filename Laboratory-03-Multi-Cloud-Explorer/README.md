Laboratory Activity 03: Multi-Cloud Explorer

Mission Overview
As part of the Cloud Evaluation Team at CloudNova Technologies, this mission explores major public cloud platforms (AWS, Azure, and GCP), compares their core services, and evaluates business scenarios to recommend appropriate cloud solutions.

───

Terminal Investigation & Migration Analysis (Checkpoint 7)

Linux System Information
From the KillerCoda terminal session, the system parameters were identified using standard Linux inspection tools:
• Operating System: Ubuntu / Linux Environment (cat /etc/os-release)
• CPU Information: x86_64 Architecture (lscpu)
• Memory (RAM): System Memory Metrics (free -h)
• Disk Space: Root File System Storage (df -h)


───

Migration Analysis: Cloud Hosting Services
If this local Linux server were to be migrated to the cloud, it could be hosted on the following Virtual Machine (IaaS) compute services:

• Amazon Web Services (AWS):Amazon EC2 (Elastic Compute Cloud)
◦ Justification: EC2 provides scalable Linux virtual instances where the existing OS image, CPU, RAM, and disk configuration can be directly replicated.
• Microsoft Azure:Azure Virtual Machines
◦ Justification: Azure Virtual Machines support standard Linux distributions with custom compute sizes and attached managed disks matching the server specifications.
• Google Cloud Platform (GCP):Compute Engine
◦ Justification: Google Compute Engine offers customizable VM instances with high-performance networking to run Linux server workloads efficiently.

