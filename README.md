# RHCSA 9.3
The collection of practice questions for RHCSA EX200

<p align="center">
  <h1 align="center">Red Hat - EX200 (RHCSA)</h1>
  <p align="center">The skills tested in this exam are the foundation for system administration across all Red Hat® products.</p>
  <br />
</p>

---
TIP#1

It is highly recommended to prioritize using a wired connection, such as Ethernet, or a reliable Wi-Fi network for your exam. While a mobile hotspot can be used, it is not considered reliable and may lead to network connectivity issues during your exam.

TIP#2

Begin by thoroughly reading all the important information, including VM details, passwords, and Podman login credentials. Next, review all the exam questions and prioritize those related to partitions and logical volumes. Addressing these tasks first allows you to revert any mistakes and start the exam from scratch if necessary. If errors occur with partitions towards the middle or end of the exam, there will be insufficient time to redo all tasks.

TIP#3

You will be providing two VM's, make sure to configure both vm in the starting as per the given task and then you can move towrds completion of all the questions one by one.

TIP#4
Always use an external terminal to access your VMs via SSH as root. Since the VMs may be slow, using an external terminal ensures better performance. Additionally, this approach facilitates copying and pasting commands from the question paper, which is not possible within the internal VM.

TIP#6

Develop a habit of verifying every step and change you make, ensuring the output is correct before proceeding to the next question. For example:

When adding a user, check the /etc/passwd file.
After making changes to fstab, reboot the machine and ensure the partition is mounted.
This practice will help you move on confidently without worrying about the correctness of previous tasks.

---

[**Red Hat Certified System Administrator (RHCSA)** Exam objective]

(https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam?section=objectives)


**Study points for the exam**

RHCSA exam candidates should be able to accomplish the tasks below without assistance. These have been grouped into several categories.

**Understand and use essential tools**
- Access a shell prompt and issue commands with correct syntax
- Use input-output redirection (>, >>, |, 2>, etc.)
- Use grep and regular expressions to analyze text
- Access remote systems using SSH
- Log in and switch users in multiuser targets
- Archive, compress, unpack, and uncompress files using tar, star, gzip, and bzip2
- Create and edit text files
- Create, delete, copy, and move files and directories
- Create hard and soft links
- List, set, and change standard ugo/rwx permissions
- Locate, read, and use system documentation including man, info, and files in /usr/share/doc

**Operate running systems**
- Boot, reboot, and shut down a system normally
- Boot systems into different targets manually
- Interrupt the boot process in order to gain access to a system
- Identify CPU/memory intensive processes and kill processes
- Adjust process scheduling
- Manage tuning profiles
- Locate and interpret system log files and journals
- Preserve system journals
- Start, stop, and check the status of network services
- Securely transfer files between systems

**Configure local storage**
- List, create, delete partitions on MBR and GPT disks
- Create and remove physical volumes
- Assign physical volumes to volume groups
- Create and delete logical volumes
- Configure systems to mount file systems at boot by universally unique ID (UUID) or label
- Add new partitions and logical volumes, and swap to a system non-destructively

**Create and configure file systems**
- Create, mount, unmount, and use vfat, ext4, and xfs file systems
- Mount and unmount network file systems using NFS
- Configure autofs
- Extend existing logical volumes
- Create and configure set-GID directories for collaboration
- Diagnose and correct file permission problems

**Deploy, configure, and maintain systems**
- Schedule tasks using at and cron
- Start and stop services and configure services to start automatically at boot
- Configure systems to boot into a specific target automatically
- Configure time service clients
- Install and update software packages from Red Hat Network, a remote repository, or from the local file system
- Modify the system bootloader

**Manage basic networking**
- Configure IPv4 and IPv6 addresses
- Configure hostname resolution
- Configure network services to start automatically at boot
- Restrict network access using firewall-cmd/firewall

**Manage users and groups**
- Create, delete, and modify local user accounts
- Change passwords and adjust password aging for local user accounts
- Create, delete, and modify local groups and group memberships
- Configure superuser access

**Manage security**
- Configure firewall settings using firewall-cmd/firewalld
- Manage default file permissions
- Configure key-based authentication for SSH
- Set enforcing and permissive modes for SELinux
- List and identify SELinux file and process context
- Restore default file contexts
- Manage SELinux port labels
- Use boolean settings to modify system SELinux settings
- Diagnose and address routine SELinux policy violations

**Manage containers**
- Find and retrieve container images from a remote registry
- Inspect container images
- Perform container management using commands such as podman and skopeo
- Build a container from a Containerfile
- Perform basic container management such as running, starting, stopping, and listing running containers
- Run a service inside a container
- Configure a container to start automatically as a systemd service
- Attach persistent storage to a container
- As with all Red Hat performance-based exams, configurations must persist after reboot without intervention.


