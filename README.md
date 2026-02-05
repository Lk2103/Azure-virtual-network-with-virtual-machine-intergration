# Azure-virtual-network-with-virtual-machine-intergration
A small project demonstrating the configuration of two virtual networks and virtual machines which communicate via the private azure backbone.

**Project Overview**

This project demonstrates configuration of virtual networks and virtual machines which includes the configuration of separate resource groups to allow the peering(private communication line) of the two networks and the virtual machines associated with them

**Architecture/Design decisions**

Some of the decisions that needed to be made for this project were:

The region in which to have the virtual networks

Virtual machines needed to have sufficient storage but with cost efficiency still in mind(using spot discount to reduce cost) and the ideal Operating System

It was important I had clear correct names for all of the virtual networks and virtual machines ensuring work remained organised.

**What I Learnt**

Ive learnt what it takes to create a virtual network

How to allow virtual networks and there resource services such as Virtual Machines to communicate with each other

Importance of creating resource groups associated with resources

The dramatic effect storage in various regions can have on the price of storage and services.

**Cleanup and cost management**

Like all other projects I deleted all resources used in this project to avoid any uneccessary costs and to ensure everything remains organised.

Azure Adviosr reccomends any improvments I could potentially make to be more cost efficient and ensure maximum performance out of the services I have implemnted.




