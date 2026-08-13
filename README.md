 Mission Overview

This laboratory focuses on understanding basic cloud computing concepts and Linux-based cloud infrastructure. The activities involved investigating a Linux cloud server using KillerCoda, identifying infrastructure components, researching major cloud providers, designing a simple cloud infrastructure, and documenting the results.

Objectives

The objectives of this laboratory are:

- Investigate and identify the resources of a Linux cloud server.
- Understand the main components of cloud infrastructure.
- Compare equivalent services offered by AWS, Microsoft Azure, and Google Cloud Platform.
- Design a simple cloud infrastructure for a fictional company.
- Practice using Linux commands to examine system resources.
- Develop technical documentation using Markdown and GitHub.
- Understand how compute, storage, networking, and operating systems work together in cloud environments.

Cloud Infrastructure Components

The major cloud infrastructure components identified during the laboratory are:

Compute Resources

Compute resources provide processing power for running applications and services. In the KillerCoda environment, the CPU and RAM are examples of compute resources used by the Linux virtual server.

Storage Resources

Storage resources are used to store operating system files, applications, documents, and other data. The disk capacity and mounted file systems were investigated using Linux commands such as `df -h`.

Networking Resources

Networking resources allow the cloud server to communicate with users and other systems. The Linux environment has a network interface and an assigned IP address that can be examined using commands such as `hostname -I` and `ip addr`.

Operating System

The Linux operating system manages the server's hardware and software resources. It provides the command-line environment used to investigate and manage the cloud server.

Tools Used

The following tools and platforms were used during the laboratory:

- KillerCoda – Used to access and investigate the Linux cloud server environment.
- Linux Terminal – Used to execute commands and collect system information.
- GitHub – Used to store, manage, and document the laboratory files.
- Markdown – Used to create technical documentation.
- Web Browser – Used to access KillerCoda, GitHub, and official cloud provider documentation.
- AWS Documentation – Used to research Amazon Web Services.
- Microsoft Azure Documentation – Used to research Microsoft Azure services.
- Google Cloud Documentation – Used to research Google Cloud services.

Linux Commands Executed

The following Linux commands were used to investigate the cloud server:

| Command | Purpose |
|---|---|
| `cat /etc/os-release` | Displays information about the operating system. |
| `uname -r` | Displays the Linux kernel version. |
| `lscpu` | Displays CPU architecture and processor information. |
| `nproc` | Displays the number of available CPU processing units. |
| `free -h` | Displays RAM and memory usage information. |
| `df -h` | Displays disk capacity and mounted file systems. |
| `mount` | Displays mounted file systems. |
| `hostname` | Displays the hostname of the server. |
| `hostname -I` | Displays the IP address of the server. |
| `ip addr` | Displays network interface and IP address information. |

Skills Learned

Through this laboratory, the following skills were developed:

- Basic Linux command-line usage.
- Linux server investigation and system monitoring.
- Identifying CPU, RAM, disk, and network resources.
- Understanding basic cloud infrastructure components.
- Comparing cloud services from AWS, Microsoft Azure, and Google Cloud.
- Creating simple cloud infrastructure diagrams.
- Using GitHub for technical documentation and version control.
- Writing documents using Markdown.
- Reading and using official cloud provider documentation.
- Understanding how cloud infrastructure components work together.

Challenges Encountered

Several challenges were encountered during the laboratory. One challenge was locating and accessing the appropriate Linux environment in KillerCoda because the platform contains multiple Linux lessons and scenarios.

Another challenge was organizing the investigation results and screenshots in the GitHub repository. Understanding the difference between a GitHub file and a folder was also necessary when creating the `screenshots` directory.

The cloud provider comparison also required understanding that AWS, Microsoft Azure, and Google Cloud often provide similar infrastructure capabilities under different service names.

Despite these challenges, the laboratory activities provided practical experience with Linux servers, cloud infrastructure, cloud service providers, and technical documentation.
