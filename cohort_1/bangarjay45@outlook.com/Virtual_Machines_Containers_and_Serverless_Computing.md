## Sunday, 17 May
> ## **Virtual Machines**:
- A virtual machine is almost similer to the guest user created in your machine.
- It’s a isolated duplicate of a real computer machine.
- The physical  hardware running the VM is generally referred to as the 'host', and the virtual machine is referred to as the 'guest'. 
- A host can occupy several guests, each of which can exist with different operating systems and hardware platforms.
![thumbnail](https://user-images.githubusercontent.com/65165798/82153902-f95f4a00-9887-11ea-8ec3-d22a4ae97fc2.png)

## Need for Virtualization:
- 1.Using different Operating system:
  - If someone needs to work on different operating system on top of another OS. E.g. You may want to use Linux for your work on top of windows.
- 2.Running old applications:
  - If you have an application that won't support on windows 10 or windows 8 but supports on windows 7 , all you need to do is install windows 7 within virtual machine and use it.
- 3.Testing softwares:
  - Primary reason to use virtual machine for this is in case your software gets crashes in between it won't effect your memory including your hard disk and ram of your host operatoring system.
- 4.Reducing Operational Expense(OpEx) with Virtual Machines:
  - If you want to avoid the difficulties of a capital expenditure, you will probably chose public cloud services that use a pay as you go model.
  - Hence, expenditure is reduced and profits increase because of **Virtual Machines**
  
 ## Advantages of using **Virtual machines**
  1. It’s a isolated duplicate of a real computer machine.
  2. It gives adaptability in any network and installed applications will be set up separately from the host computer, and will exist in the software.
  3. When you create your virtual machine, you create a virtual hard disk. So, everything on that machine can crash, but if it does, it won’t affect the host machine.
  4. There are security benefits to running virtual machines. For example, if you need to run an application of not promising security, you can run it in a guest operating system. So, if the application causes damage, then it won't affect the host.
  5. It is cheaper because virtualization doesn’t require actual hardware components to be used or installed, IT infrastructures find it to be a cheaper system to implement.


> # What are **Containers:**
- Containers provide a consistent, isolated execution environment for applications.
- They are similar to VM's but they don't require a guest OS.
- It is a isolated test environment where all the execution of the application is done.
- The result is the application runs quickly and reliably.
  - Ex. Docker is a leading platform for **containers** as it is efficient, lightweight approach to application deployment.
  - It allows different components of the application to be deployed independently into different containers. 
![docker](https://user-images.githubusercontent.com/65165798/82722093-2032db80-9ce1-11ea-9701-569697db6d8f.png)
  
### benefits of containers:
- A container may be only tens of megabytes in size, whereas a virtual machine with its own entire operating system may be several gigabytes in size. 
- Because of this, a single server can host far more containers than virtual machines.
- It saves us time as bootloading is faster.
- Rather than run an entire complex application inside a single container, the application can be split in to modules .
- This makes it easier for the developers to manage the applications.












