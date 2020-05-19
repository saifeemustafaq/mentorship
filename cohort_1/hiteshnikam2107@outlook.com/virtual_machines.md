# VIRTUAL MACHINE
### A virtual machine (VM) is a virtual environment that functions as a virtual computer system with its own CPU, memory, network interface, and storage, created on a physical hardware system.Software called a hypervisor separates the machine’s resources from the hardware and provisions them appropriately so they can be used by the VM.
### Virtualization makes it possible to create multiple virtual machines, each with their own operating system (OS) and applications, on a single physical machine. A VM cannot interact directly with a physical computer. Instead, it needs a lightweight software layer called a hypervisor to coordinate between it and the underlying physical hardware. The hypervisor allocates physical computing resources such as processors, memory, and storage to each VM. It keeps each VM separate from others so they don’t interfere with each other.
## Working of virtual machines:
### Multiple virtual machines can run simultaneously on the same physical computer. For servers, the multiple operating systems run side by side with a piece of software called a hypervisor to manage them, while desktop computers typical employ one operating system to run the other operating systems within its program windows. Each virtual machine provides its own virtual hardware, including CPUs, memory, hard drives, network interfaces, and other devices. The virtual hardware is then mapped to the real hardware on the physical machine which saves costs by reducing the need for physical hardware systems along with the associated maintenance costs that go with it, plus reduces power and cooling demand.

![](https://qphs.fs.quoracdn.net/main-qimg-9f79ce74e0e085123034f20b309382d4)

## Why use VMs?
#### Most operating system and application deployments only use a small amount of the physical resources available when deployed to bare metal. By virtualizing your servers, you can place many virtual servers onto each physical server to improve hardware utilization.This keeps you from needing to purchase additional physical resources, like hard drives or hard disks, as well as reducing the need for power, space, and cooling in the datacenter. VMs provide additional disaster recovery options by enabling failover and redundancy that could previously only be achieved through additional hardware.

## Advantages Of Virtual Machine :
 - #### Multiple OS environments can exist simultaneously on the same machine, isolated from each other.
 - #### Virtual machine can offer an instruction set architecture that differs from real computers.
 - #### Easy maintenance, application provisioning, availability and convenient recovery.
 
 ## Disadvantages Of Virtual Machine :
 - #### When multiple virtual machines are simultaneously running on a host computer, each virtual machine may introduce an unstable performance, which depends on the workload on the system by other running virtual machines.
 - #### Virtual machine is not that efficient as a real one when accessing the hardware.
