
## Date: June 13, 2020

> # ***Virtual machine (VM) :***

###  ***A virtual machine (VM) is a software program or operating system that not only exhibits the behavior of a separate computer, but is also capable of performing tasks such as running applications and programs like a separate computer.Virtual machines are implemented by software emulation methods or hardware virtualization techniques.***

---

![](https://qph.fs.quoracdn.net/main-qimg-845bdc01dfe2f21e24b1399fa47b154f)
       
---

**A virtual machine is a program on a computer that works like it is a separate computer inside the main computer. The program that controls virtual machines is called a hypervisor and the computer that is running the virtual machine is called the host. The hypervisor controls how the virtual machine can access memory, hard drive space, and other resources on the host computer. Virtual machines can be created through software known as virtualization software.**


> # Key Properties of Virtual Machines :


## 1. Partitioning

- **Run multiple operating systems on one physical machine.**
- **Divide system resources between virtual machines.**

## 2. Isolation

- **Provide fault and security isolation at the hardware level.**
- **Preserve performance with advanced resource controls.**

## 3. Encapsulation

- **Save the entire state of a virtual machine to files.**
- **Move and copy virtual machines as easily as moving and copying files.**

## 4. Hardware Independence

- **Provision or migrate any virtual machine to any physical server.**

> # ***Why Virtual Machines?***

**Virtual machines are created to perform specific tasks that are risky to perform in a host environment, such as accessing virus-infected data and testing operating systems. Since the virtual machine is sandboxed from the rest of the system, the software inside the virtual machine cannot tamper with the host computer. Virtual machines can also be used for other purposes such as server virtualization.**


> # ***The Two Types of Virtual Machines:***

![](https://miro.medium.com/max/5760/1*whzUZGM68tKcFF8m-LzTnQ.jpeg)

# 1. Process Virtual Machine :

- **Process Virtual Machine is also known as application VM, a process virtual machine is designed to provide a platform-independent programming environment that supports a single process. It is created when the process is started, and destroyed upon exit.**

- **A process VM is used to mask the information of the underlying hardware or operating system, and allows program execution to take place in the same way on any given platform.**
   
   **Example: Linux process, Java VM, .NET VM.**


# 2. System Virtual Machine:

- **A system platform that supports the sharing of the host computer's physical resources between multiple virtual machines, each running with its own copy of the operating system.**

- **The virtualization technique is provided by the hypervisor, which can run either on bare hardware or on top of an operating system.**


> # Advantages of virtual machines :

- **Allows multiple operating system environments on a single physical computer without any intervention.**

- **Virtual machines are widely available and are easy to manage and maintain.**

- **Offers application provisioning and disaster recovery options.**

- **A VM can be created or replicated very quickly by cloning it with an OS already installed, rather than installing a new OS on a physical server.**

- **VMs are offer high availability since they can be moved from one server to another for maintenance purposes, even whilst running.**

> # Drawbacks of virtual machines :

- **They are not as efficient as a physical computer because the hardware resources are distributed in an indirect way.**

- **Multiple VMs running on a single physical machine can deliver unstable performance.**


> # Examples of when to use virtual machines:


- **During testing and development. VMs provide a quick and easy way to create different OS and application configurations. Test and development personnel can then easily delete the VMs when they no longer need them.**

- **When running applications in the cloud. The ability to run certain applications in the public cloud as opposed to creating a traditional infrastructure to run them can provide substantial economic benefits. For example, if an application needs to handle fluctuations in demand, being able to shut down VMs when you don't need them or quickly start them up to meet a suddenly increased demand means you pay only for the resources you use.**

- **When extending your datacenter to the cloud. An organization can extend the capabilities of its own on-premises network by creating a virtual network in Azure and adding VMs to that virtual network. Applications like SharePoint can then run on an Azure VM instead of running locally, making it easier or less expensive to deploy than in an on-premises environment.**

- **During disaster recovery. As with running certain types of applications in the cloud and extending an on-premises network to the cloud, you can get significant costs savings by using an IaaS-based approach to disaster recovery. If a primary datacenter fails, you can create VMs running on Azure to run your critical applications and then shut them down when the primary datacenter becomes operational again.**



