**Proxmox VE**

Proxmox VE is an open-source platform for enterprise virtualization that integrates KVM (Kernel-based Virtual Machine) hypervisor and LXC (Linux Containers) containers. It is designed to manage virtual machines, containers, storage, and networking on a single platform.<br>

<br> I had to install Proxmox on my Main pc as a dual boot option. I installed Ubuntut and then added proxmox onto it. I decided not to change the kernel, which maybe was a mistake. But so far so good. I have also installed proxmox directly on another old corsair custom PC which was my HTPC (Home Theatre PC). I installed PI-hole and Pfsesne on it.


Here are its key features, pros, and cons:<br><br>


**Features:**
- **Hypervisor Support:** Uses KVM for virtualization, providing hardware-assisted virtualization for efficient performance.
- **Container Support:** Includes LXC containers for lightweight virtualization, enabling rapid deployment and scaling.
- **Web-based Management Interface:** Proxmox VE offers a powerful web-based GUI for easy management and administration.
- **High Availability:** Supports clustering and high availability configurations, ensuring resilience and fault tolerance.
- **Built-in Backup and Restore:** Integrated backup and restore capabilities for VMs and containers.
- **Software-defined Storage:** Supports various storage types including local storage, NFS, Ceph, and more.
- **Networking:** Flexible networking configurations with VLAN support and software-defined networking (SDN) capabilities.
- **Community and Enterprise Support:** Offers a vibrant community and optional enterprise support subscriptions.

**Pros:**
- **Free and Open Source:** Proxmox VE is open-source and free to use, with a commercial support option available.
- **Comprehensive Virtualization:** Supports both VMs and containers, providing flexibility for different workload types.
- **High Availability and Clustering:** Enables building resilient infrastructure with clustering and high availability features.
- **Easy Management:** The web-based GUI simplifies management tasks, making it accessible even for less experienced users.
- **Extensive Documentation:** Well-documented with a supportive community, offering resources and guides for users.

**Cons:**
- **Learning Curve:** Setting up and configuring Proxmox VE, especially in clustered environments, may require a learning curve.
- **Resource Requirements:** Running Proxmox VE effectively may demand significant resources, especially for larger deployments.
- **Compatibility Issues:** Like any virtualization platform, compatibility issues with specific hardware or software configurations may arise.
- **Enterprise Features:** Some advanced features may require a Proxmox VE subscription or additional configuration.

<img align="center" src="Virtualization/images/picture1.png" /><br/>
