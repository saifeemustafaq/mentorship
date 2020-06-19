# Date:June 19,2020

--------

## What is a Virtual Machine(VM)?

A virtual machine is a virtual representation, or emulation, of a physical computer. They are often referred to as a guest while the physical machine they run on is referred to as the host.
**Virtualization** makes it possible to create multiple virtual machines, each with their own operating system (OS) and applications, on a single physical machine. A VM cannot interact directly with a physical computer. Instead, it needs a lightweight software layer called a **hypervisor** to coordinate between it and the underlying physical hardware. The hypervisor allocates physical computing resources—such as processors, memory, and storage—to each VM. It keeps each VM separate from others so they don’t interfere with each other.

While this technology can go by many names, including virtual server, virtual server instance (VSI) and virtual private server (VPS), this article will simply refer to them as virtual machines.

--------

## How Virtualization Works?

- When a hypervisor is used on a physical computer or server, (also known as bare metal server), it allows the physical computer to separate its operating system and applications from its hardware. Then, it can divide itself into several independent “virtual machines.”

- Each of these new virtual machines can then run their own operating systems and applications independently while still sharing the original resources from the bare metal server, which the hypervisor manages. Those resources include memory, RAM, storage, etc.

The hypervisor acts like a traffic cop of sorts, directing and allocating the bare metal’s resources to each of the various new virtual machines, ensuring they don’t disrupt each other.

## There are two types of hypervisors:

--------

- **Type 1 hypervisors** run directly on the physical hardware (usually a server), taking the place of the OS. Typically, you use a separate software product to create and manipulate VMs on the hypervisor. Some management tools, like VMware’s vSphere, let you select a guest OS to install in the VM.

- **Type 2 hypervisors** run as an application within a host OS and usually target single-user desktop or notebook platforms. With a Type 2 hypervisor, you manually create a VM and then install a guest OS in it. You can use the hypervisor to allocate physical resources to your VM, manually setting the amount of processor cores and memory it can use. Depending on the hypervisor’s capabilities, you can also set options like 3D acceleration for graphics.

-------

## Benefits of VM:

- ## Resource Utilization:
Because multiple VMs run on a single physical computer, customers don’t have to buy a new server every time they want to run another OS, and they can get more return from each piece of hardware they already own.

- ## Scale:
With cloud computing, it’s easy to deploy multiple copies of the same virtual machine to better serve increases in load.

- ## Flexibility
Creating a VM is faster and easier than installing an OS on a physical server because you can clone a VM with the OS already installed. Developers and software testers can create new environments on demand to handle new tasks as they arise.

- ## Security
VMs improve security in several ways when compared to operating systems running directly on hardware. A VM is a file that can be scanned for malicious software by an external program. You can create an entire snapshot of the VM at any point in time and then restore it to that state if it becomes infected with malware, effectively taking the VM back in time. The fast, easy creation of VMs also makes it possible to completely delete a compromised VM and then recreate it quickly, hastening recovery from malware infections.

-------

## Types of VM:

- Windows virtual machines
- Android virtual machines
- Mac virtual machines
- iOS virtual machines
- Java virtual machines
- Python virtual machines
- Linux virtual machines
- VMware virtual machines
- Ubuntu virtual machines
