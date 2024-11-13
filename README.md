
# Basic Azure Onboarding

This repository documents my experience with **Microsoft Azure** onboarding, carried out in a DIO lab environment. During this process, I explored some key services and initial configurations, including setting up a subscription, using Azure Bastion, configuring Azure Virtual Desktop, exploring the "All Services" tab, creating a virtual machine, understanding storage account redundancy options, and setting up a private endpoint for a storage account.

---

## Topics Covered

1. **Azure Subscription**:  
   - Creation and activation of a basic subscription to access Azure resources.

2. **Azure Virtual Desktop**:  
   - Initial configuration of the remote desktop environment to facilitate access and work on virtual desktops.

3. **"All Services" Tab (Network and Compute)**:  
   - Navigation through the tab to explore resources and discover tools in Networking and Compute.

4. **Creating a Virtual Machine (VM)**:  
   - Step-by-step configuration and launch of a VM with basic networking and storage options.

5. **Azure Bastion**:  
   - Use of Bastion for secure connections to virtual machines without exposing public IPs.

6. **Azure Storage Accounts and Redundancy Options**:  
   - Configuration of storage accounts and understanding the types of redundancy options available for data protection.

7. **Private Endpoint for Storage Account**:  
   - Creation and configuration of a private endpoint to securely access a storage account within a virtual network.

---

## Process Overview

### 1. Azure Subscription
   - **Experience**: I started by creating a free Azure subscription, which granted access to various resources and trial credits. This step is essential for accessing the portal and resources.

### 2. Azure Virtual Desktop Configuration
   - **Experience**: I set up Azure Virtual Desktop to access a remote work environment, enabling cloud-based desktops that can be accessed from anywhere.

### 3. Exploring "All Services"
   - **Experience**: In the "All Services" tab, I explored the **Networking** and **Compute** sections, where I discovered resources like virtual machines, virtual networks, and Bastions.

### 4. Creating a Virtual Machine (VM)
   - **Experience**: I created my first virtual machine by following the recommended steps in the portal. I set the operating system, size, and basic networking and storage configurations.

### 5. Azure Bastion Configuration
   - **Experience**: I configured **Azure Bastion** to connect to virtual machines securely without exposing public IPs.

### 6. Azure Storage Accounts and Redundancy Options
   - **Experience**: I created a storage account and explored different redundancy options. In Azure, **Storage Accounts** are used to store data in the cloud, and the types of redundancy determine how your data is protected from failures and outages. The main types of redundancy are:
     - **Locally Redundant Storage (LRS)**: Data is replicated three times within a single data center in a region.
     - **Geo-Redundant Storage (GRS)**: Data is replicated across two regions—primary and secondary—providing disaster recovery capabilities.
     - **Zone-Redundant Storage (ZRS)**: Data is replicated across multiple availability zones within a region, ensuring availability even if one zone goes down.
     - **Read-Access Geo-Redundant Storage (RA-GRS)**: Similar to GRS, but allows read access to the secondary region, even during outages in the primary region.

### 7. Private Endpoint for Storage Account
   - **Experience**: I created a **private endpoint** to securely connect to my Azure Storage Account within a **virtual network**. This ensures that traffic between my services and the storage account does not traverse the public internet, providing an additional layer of security. The private endpoint enables the use of private IP addresses to access the storage account, restricting access to only resources within the network.

---

## Conclusion

This basic onboarding experience on Azure allowed me to explore essential resources and become familiar with the portal, as well as compute, networking, and storage services. I also gained insights into the redundancy options available to ensure data resilience in cloud environments. Additionally, setting up a private endpoint added an important layer of security for accessing the storage account. This repository serves as a record of this onboarding and will be useful for future Azure projects.

---

## Additional Resources

- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)
- [Introductory Azure Tutorials](https://docs.microsoft.com/en-us/learn/azure/)
- [Azure Bastion - Documentation](https://docs.microsoft.com/en-us/azure/bastion/)
- [Azure Virtual Desktop - Documentation](https://docs.microsoft.com/en-us/azure/virtual-desktop/)
- [Azure Storage Redundancy - Documentation](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)
- [Private Endpoints - Documentation](https://docs.microsoft.com/en-us/azure/storage/common/storage-private-endpoints)

---

## Contribution

This report can be expanded as I explore more services and functionalities in Azure. Suggestions and improvements are welcome!
