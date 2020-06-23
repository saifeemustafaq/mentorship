## Date: June 22, 2020

> # ***Latency***

### **Latency is the delay between a user’s action and a web application’s response to that action, often referred to in networking terms as the total round trip time it takes for a data packet to travel.**

![](https://networkencyclopedia.com/wp-content/uploads/2019/10/latency-1024x402.png)


- #### **The term “latency” can also refer to the delay in forming a connection, such as the 15 to 30 seconds required to establish a modem connection.**

- #### **Intrinsic latency in a transmission is caused by the finite transmission speed of the electrical signals through the wires (or the light signals through the fiber-optic cabling). Intrinsic latency cannot be eliminated but is usually quite small.**

- #### **Much greater latency is usually introduced into a network by gateway devices such as routers and bridges, which process packets and perform protocol conversion.**

- #### **The latency for a bridge is thus the time delay between the moment when the packet enters one port of the bridge and the moment when it leaves another port – usually a fraction of a millisecond.**


> # ***Latency vs bandwidth vs throughput***

- **Bandwidth** determines how narrow or wide a pipe is. The narrower it is, the less data is able to be pushed through it at once and vice-versa.

- **Latency** determines how fast the contents within a pipe can be transferred from the client to the server and back.

- **Throughput** is the amount of data which can be transferred over a given time period.

If the latency in a pipe is low and the bandwidth is also low, that means that the throughput will be inherently low. However, if the latency is low and the bandwidth is high that will allow for greater throughput and a more efficient connection. Ultimately, latency creates bottlenecks within the network thus reducing the amount of data which can be transferred over a period of time.

> # Causes of network latency

### 1.Transmission medium: 

The physical path between the start point and the end point. The type ofmedium can impact latency. For instance, old copper cable-based networks have a higher latency than modern optic fibers.

### 2. Propagation: 

The further apart two nodes are the more latency there is as latency is dependent on the distance between the two communicating nodes. Theoretically, latency of a packet going on a round trip across the world is 133ms. In actuality, such a round trip takes longer, though latency is decreased when direct connections through network backbones are achieved.

### 3. Routers: 

The efficiency in which routers process incoming data has a direct impact on latency. Router to router hops can increase latency.Storage delays: Accessing stored data can increase latency as the storage network may take time to process and return information.

> # How to reduce latency

- Latency can be reduced by addressing the aforementioned components and ensuring that they are working correctly. It can also be reduced by using dedicated networks that streamline the network path and provide direct communication between nodes.

- Content Delivery Network (CDN) providers such as StackPath provide customers with private networks that allow them to bypass the public internet. These private networks reduce latency by providing more efficient paths for data packets to travel on.


> # Other types of latency

## ***1. network latency***

Latency is a measure of delay.  In a network, latency measures the time it takes for some data to get to its destination across the network.  It is usually measured as a round trip delay - the time taken for information to get to its destination and back again.   The round trip delay is an important measure because a computer that uses a TCP/IP network sends a limited amount of data to its destination and then waits for an acknowledgement to come back before sending any more.  Thus, the round trip delay has a key impact on the performance of the network.

Latency is usually measured in milliseconds (ms).


## ***2. Fibre optic latency***

Latency in the case of data transfer through fibre optic cables can't be fully explained without first discussing the speed of light and how it relates to latency. Based on the speed of light alone (299,792,458 meters/second), there is a latency of 3.33 microseconds (0.000001 of a second) for every kilometer of path covered. Light travels slower in a cable which means the latency of light traveling in a fibre optic cable is around 4.9 microseconds per kilometer.

Based on how far a packet must travel, the amount of latency can quickly add up. Cable imperfections can also degrade the connection and increase the amount of latency incurred by a fibre optic cable.


## ***3. Audio latency***

This form of latency is the time difference between a sound being created and heard. The speed of sound plays a role in this form of latency which can vary based on the environment it travels through e.g solids vs liquids. In technology, audio latency can occur from various sources including analog to digital conversion, signal processing, hardware / software used, etc

##  ***4. Disk latency***

Disk latency is the delay between the time data is requested from a storage device and when the data starts being returned. Factors that effect disk latency include the rotational latency (of a hard drive) and the seek time. A hard drive with a rotational speed of 5400 RPM, for example, will have almost twice the rotational latency of a drive that rotates at 10,000 RPM.



### **Typical values for latency :**

- 800ms for satellite

- 120ms for 3G cellular data

- 60ms for 4G cellular data which is often used for 4G WAN and internet connections

- 20ms for an mpls network such as BT IP Connect, when using Class of Service to prioritise traffic

- 10ms for a modern Carrier Ethernet network such as BT Ethernet Connect or BT Wholesale Ethernet in the UK


