# Azure Virtual Network With Virtual Machine Integration

A small project demonstrating the configuration of two virtual networks and virtual machines which communicate via the private Azure backbone.

**Project Overview**

This project demonstrates the configuration of Azure Virtual Networks and Virtual Machines, including the configuration of separate resource groups and VNet(Virtual Network) Peering to enable private communication between networks and their associated virtual machines.

<img width="1919" height="1011" alt="image" src="https://github.com/user-attachments/assets/744007d2-7676-489c-8dc9-28796bf85f1e" />

<img width="1919" height="814" alt="image" src="https://github.com/user-attachments/assets/3d61db67-3484-4a84-9b92-d21975fa9afc" />

*Enabling Peering on Virtual Network*

**Architecture/Design decisions**

Some of the decisions that needed to be made for this project were:

The region in which to have the virtual networks

Virtual machines needed to have sufficient storage but with cost efficiency still in mind(using spot discount to reduce cost) and the ideal Operating System

**Spot Discount**

Only to be used when conducting tests/non production workload due to potential evictions/interruptions when Azure resources are in demand.

Clear consistent names for all of the virtual networks and virtual machines ensuring work remained organised.

<img width="1914" height="511" alt="image" src="https://github.com/user-attachments/assets/9927aa17-1bd6-4624-a2fe-6264be551c93" />

*Enabling Azure Spot Discount*

**What I Learnt**

Creating Azure Virtual Network
<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/c4e2dad0-a537-484e-9d93-7b8d3643633e" />
*Creating the Azure Virtual Network*

How to allow virtual networks and their resource services such as Virtual Machines to communicate with each other

Importance of creating resource groups associated with resources

The dramatic effect storage in various regions can have on the price of storage and services.

Creating a Azure Virtual Machine with low cost

<img width="1915" height="818" alt="image" src="https://github.com/user-attachments/assets/884baf42-0c95-4d4d-bbbf-f6c5fff01732" />
*Final Page of Creating the Virtual Machine*

**Issues Encountered**

The one issue I encountered with this project was that it was more expensive to deploy a virtual network and therefore virtual machine in Norway East, I decided to ammend this later on in my project and change this to UK South.

**Proof of concept**

To show these two networks were communicating with each other I Pinged the private ip address with resulted in recieved packets showing capability of transferring data.

<img width="1919" height="405" alt="image" src="https://github.com/user-attachments/assets/ae94f741-39b7-4418-8315-1c7e3907650c" />

*Private Ip Address being pinged*

<img width="951" height="321" alt="image" src="https://github.com/user-attachments/assets/985acc5e-38fb-4613-828d-beb2fcbf557a" />

*Virtual Machine overview*

**Cleanup and cost management**

Like all other projects I deleted all resources used in this project to avoid any unnecessary costs and to ensure everything remains organised.



