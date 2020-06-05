> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: May 28, 2020

I learned how to use github.

Also I learned that how to submit the work on github.


## Date: May 29, 2020

- Today I learned some basic things about clout computing.
- Today I learned that why cloud computing is important in many fields.
- Today I learned that how the cloud computing makes things easy for us.
- Also cloud computing saves the time and lack of efforts.


## Date: 1 June, 2020

- Today I Learned about virtual machine.
# Virtual Machine-
In computing, a virtual machine (VM) is an emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.
### There are different kinds of virtual machines, each with different functions:
### 1)System Virtual machines:
### 2)Process Virtual machines:
### System Virtual Machine:
- In computing, a system virtual machine is a virtual machine that provides a complete system platform and supports the execution of a complete operating system (OS).These usually emulate an existing architecture, and are built with the purpose of either providing a platform to run programs where the real hardware is not available for use (for example, executing on otherwise obsolete platforms), or of having multiple instances of virtual machines leading to more efficient use of computing resources, both in terms of energy consumption and cost effectiveness (known as hardware virtualization, the key to a cloud computing environment), or both. A VM was originally defined by Popek and Goldberg as "an efficient, isolated duplicate of a real machine".
- The desire to run multiple operating systems was the initial motive for virtual machines, so as to allow time-sharing among several single-tasking operating systems. In some respects, a system virtual machine can be considered a generalization of the concept of virtual memory that historically preceded it. IBM's CP/CMS, the first systems to allow full virtualization, implemented time sharing by providing each user with a single-user operating system, the Conversational Monitor System (CMS). Unlike virtual memory, a system virtual machine entitled the user to write privileged instructions in their code. This approach had certain advantages, such as adding input/output devices not allowed by the standard system.
- As technology evolves virtual memory for purposes of virtualization, new systems of memory overcommitment may be applied to manage memory sharing among multiple virtual machines on one computer operating system. It may be possible to share memory pages that have identical contents among multiple virtual machines that run on the same physical machine, what may result in mapping them to the same physical page by a technique termed kernel same-page merging (KSM). This is especially useful for read-only pages, such as those holding code segments, which is the case for multiple virtual machines running the same or similar software, software libraries, web servers, middleware components, etc. The guest operating systems do not need to be compliant with the host hardware, thus making it possible to run different operating systems on the same computer (e.g., Windows, Linux, or prior versions of an operating system) to support future software.
- The use of virtual machines to support separate guest operating systems is popular in regard to embedded systems. A typical use would be to run a real-time operating system simultaneously with a preferred complex operating system, such as Linux or Windows. Another use would be for novel and unproven software still in the developmental stage, so it runs inside a sandbox. Virtual machines have other advantages for operating system development and may include improved debugging access and faster reboots.
Multiple VMs running their own guest operating system are frequently engaged for server consolidation.
### Process Virtual Machine:
- A process VM, sometimes called an application virtual machine, or Managed Runtime Environment (MRE), runs as a normal application inside a host OS and supports a single process. It is created when that process is started and destroyed when it exits. Its purpose is to provide a platform-independent programming environment that abstracts away details of the underlying hardware or operating system and allows a program to execute in the same way on any platform.
- A process VM provides a high-level abstraction – that of a high-level programming language (compared to the low-level ISA abstraction of the system VM). Process VMs are implemented using an interpreter; performance comparable to compiled programming languages can be achieved by the use of just-in-time compilation.
- This type of VM has become popular with the Java programming language, which is implemented using the Java virtual machine. Other examples include the Parrot virtual machine and the .NET Framework, which runs on a VM called the Common Language Runtime. All of them can serve as an abstraction layer for any computer language.
- A special case of process VMs are systems that abstract over the communication mechanisms of a (potentially heterogeneous) computer cluster. Such a VM does not consist of a single process, but one process per physical machine in the cluster. They are designed to ease the task of programming concurrent applications by letting the programmer focus on algorithms rather than the communication mechanisms provided by the interconnect and the OS. They do not hide the fact that communication takes place, and as such do not attempt to present the cluster as a single machine.
- Unlike other process VMs, these systems do not provide a specific programming language, but are embedded in an existing language; typically such a system provides bindings for several languages (e.g., C and Fortran).Examples are Parallel Virtual Machine (PVM) and Message Passing Interface (MPI). They are not strictly virtual machines because the applications running on top still have access to all OS services and are therefore not confined to the system model.

## Advantages of VM:
- Can use multiple operating system environments on the same computer.
- Virtual machines can provide an instruction set architecture, or ISA, structure different than the actual computer. The ISA serves as the interface between software and hardware.
- When you create your virtual machine, you create a virtual hard disk. So, everything on that machine can crash, but if it does, it won’t affect the host machine.
- There are security benefits to running virtual machines. For example, if you need to run an application of questionable security, you can run it in a guest operating system. So, if the application causes damage, then it will be only temporary after the guest is shut down. Virtual machines also allow for better security forensics by monitoring guest operating systems for deficiencies and allowing the user to quarantine it for analysis.
## Disadvantages of VM:
- Virtual machines are less efficient than real machines because they access the hardware indirectly. Running software on top of the host operating system means that it will have to request access to the hardware from the host. That will slow the usability.
- When several virtual machines are running on the same host, performance may be hindered if the computer it’s running on lacks sufficient power. Your virtual machine still uses the resources of your host machine. The more powerful the host computer, the more quickly the virtual machine will run.
- A virtual machine can be infected with the weaknesses of the host machine. As an example, process isolation is a feature usually employed by operating systems. However, there are bugs that violate it. A regular computer devoid of virtual machines would then only be affected. But, a computer with a number of virtual machines would then infect each of those “machines” as well.


## Date: June 5, 2020

## Benefits of Cloud Computing:
> Cloud computing offers your business many benefits. It allows you to set up what is essentially a virtual office to give you the flexibility of connecting to your business anywhere, any time. With the growing number of web-enabled devices used in today's business environment (e.g. smartphones, tablets), access to your data is even easier.

There are many benefits to moving your business to the cloud:
## Reduced IT Costs:
> Moving to cloud computing may reduce the cost of managing and maintaining your IT systems. Rather than purchasing expensive systems and equipment for your business, you can reduce your costs by using the resources of your cloud computing service provider. You may be able to reduce your operating costs because:
- the cost of system upgrades, new hardware and software may be included in your contract
- you no longer need to pay wages for expert staff
- your energy consumption costs may be reduced
- there are fewer time delays.

## Scalability:
> Your business can scale up or scale down your operation and storage needs quickly to suit your situation, allowing flexibility as your needs change. Rather than purchasing and installing expensive upgrades yourself, your cloud computer service provider can handle this for you. Using the cloud frees up your time so you can get on with running your business.

## Business Continuity:
> Protecting your data and systems is an important part of business continuity planning. Whether you experience a natural disaster, power failure or other crisis, having your data stored in the cloud ensures it is backed up and protected in a secure and safe location. Being able to access your data again quickly allows you to conduct business as usual, minimising any downtime and loss of productivity.

## Collaboration Efficiency:
> Collaboration in a cloud environment gives your business the ability to communicate and share more easily outside of the traditional methods. If you are working on a project across different locations, you could use cloud computing to give employees, contractors and third parties access to the same files. You could also choose a cloud computing model that makes it easy for you to share your records with your advisers (e.g. a quick and secure way to share accounting records with your accountant or financial adviser).

## Flexibility of work practices:
> Cloud computing allows employees to be more flexible in their work practices. For example, you have the ability to access data from home, on holiday, or via the commute to and from work (providing you have an internet connection). If you need access to your data while you are off-site, you can connect to your virtual office, quickly and easily.

## Access to automatic updates:
> Access to automatic updates for your IT requirements may be included in your service fee. Depending on your cloud computing service provider, your system will regularly be updated with the latest technology. This could include up-to-date versions of software, as well as upgrades to servers and computer processing power.
