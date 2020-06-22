### Thursday, 14 May
> Topics discussed:
 1. What is Internet of Things(Iot)?
 2. Why is IoT so important?
 3. Benifits of having Iot devices around us!
 4. Future of IoT security.
 5. IoT powered Industrial Light monitor project.

### What is **Internet of Things**(Iot)?
- Internet of Things, is a system of internet connected computing devices, mechanical and digital machines or objects that have the ability to transfer data over a private network, resulting in reduced human efforts and a number of other advantages.
- Thanks to some brilliant minds, computer chips and wireless networks, we can turn anything(possibly) into a part of IoT.
- With Arduino, different sensors and motors, we can add some *digital intelligence* to dumb things, also enabling them to communicate, collect data or work for us without involving humans; the possibilities are endless.
- A intresting example of IoT device is **Amazon Echo** and many other smart speakers. It makes easier for people to play music, sounds amazing right!!
- Another example is Smart Home Lights. With a simple touch or Voice command, network connection, Smart led lights can be turned On/Off or their colour could be changed.
- IoT platform grants the user to control the IoT devices safely, whereever you are.

### Why is IoT so important?
- let's start with a simple example:
  - Say you're a manager in a big pharmaceutical industry and the responsibility of monitoring the **temp.** of a given drug rests on your shoulders.
  - The **Gov** has decided the threshold limit values of the drug, such that the **temp.** should not strictly exceed these limits, else your company might face a big loss.
  - A smart **Arduino and sensor** would make it easier for you to continuously monitor these temperatures as it would alert you by sending a pop-up messsage on your device if the temperature is about to exceed the set limits.
  - Also **Self-driving Cars, Smart cities..** just to name a few.
- Many Organisations use different approach with the help of IoT to operate more efficiently, to improve, monitor or to change decision making.

### Benifits of having Iot devices around us!
- **Productivity improvement:** Monitoring and control of the different processes improves the different operations that increase productivity and efficiency
- **Predictive analysis:** IoT’s new technologies make it possible to examine recurring patterns and predicts irregularities.
- **Rapid response:** The data makes it possible to monitor the systems in place, in real time and even remotely, giving the company a strategic advantage in monitoring market developments.
- **Reduction of human errors:** Artificial intelligence in IoT makes it possible to reduce human errors due to work load or repetitive tasks.
- **Saves time and money**
- **Enhances productivity**
- **Encourages new techniques and business modals**
- **IoT** is big and getting bigger, and the benifits are countless, depending on perticular implementation, improving efficiency wherever it is utilised.

![5379966-screen-shot-2017-05-23-at-20512-pm](https://user-images.githubusercontent.com/65165798/82146980-42a0a100-986a-11ea-9ff8-108a6e18906e.png)

> ## About BOLT IOT:

- [Bolt IoT](https://www.boltiot.com/) is a paid Internet of Things platform for budding developers.

- Excellent online video training for those who want to start with IoT and Machine Learning because, it teaches you to build projects from the basics.

- The training makes you job hiring ready since it teaches fundamentals of IOT and ML and offers you a certificate upon completion.

### Features of Bolt IoT:-

1. A Wifi microcontroller 
2. Remote Configuration
3. Code Editor
4. Smartphone App
5. Notification(SMS & E-Mail)
6. Visualisation & Analysis
7. Remote Control and monnitoring
 
> ### Light Monitoring for Plants using Bolt.

- Bolt IoT Platform starter kit is used in this project that consisted of Bolt IoT Bolt WiFi Module Light Dependent Resistor(LDR) and Resistor 10k .
- Story;
  - Plants require sunlight for their healthy growth.
  - However, we may not be able to keep a track of it or What if we are not sure if our plants are getting enough sunlight.
  - IOT would help us in this situation.
- In this project, I built a system so that i could monitor the light anywhere and send the data to Bolt Cloud.  
- I also plotted a line graph which indicated what intensity of light the sensor picked at any point of time.
- This plant light monitor is also available by [Xiaomi](https://www.amazon.com/HHCC-Xiaomi-Plant-Flower-Monitor/dp/B06X9V2FKJ), but as a curious person, I made it at home.

----  
  
> ## Things used in this project

### Hardware components


1. Bolt IoT Bolt WiFi Module
2. Light Dependent Resistor
3. Resistor 10k ohm


### Software apps and online services

1. Bolt IoT Bolt Cloud
2. Bolt IoT Android App


**Bolt WiFi Module:**

![bolt module](https://user-images.githubusercontent.com/65165798/84678603-d8088100-af4d-11ea-9875-ac390460d35b.jpeg)

**LDR (Light Dependent Resistor):**

![LDR](https://user-images.githubusercontent.com/65165798/84678592-d5a62700-af4d-11ea-8793-3d29d3b85c66.jpeg)

**Resistor 10K:**

![Resistor](https://user-images.githubusercontent.com/65165798/84678598-d6d75400-af4d-11ea-8e58-f26f799876db.jpeg)


> ##  Overview of the BOLT WI-FI Module:

![Module](https://user-images.githubusercontent.com/65165798/84678584-d474fa00-af4d-11ea-8f88-fa38ff9acee6.jpg)

----

# **PROCEDURE:**
 

## Step 1: Building the circuit

#### First we have to set up the BOLT WIFI MODULE and make sure that it is connected to Bolt Cloud and the Green LED on Bolt Module is Glowing.

- If you dont know how to, then follow the steps in this project to setup the device: [Setting Up the Bolt WiFi Module](https://docs.boltiot.com/docs/setting-up-the-bolt-wifi-module).
- Make sure you have not powered on your Bolt Module while connecting the circuit.
- This will ensure that in case we make any mistake, it will not short circuit your device. 
- Switch off the power if it is connected.


> #### Connect one end of the LDR to the A0 (analog) pin of the Bolt device and other ends of the LDR to the 3V3 pin of the Bolt as shown in the image below.

![m1_t4_s2_i3](https://user-images.githubusercontent.com/65165798/85008441-a0325100-b17a-11ea-95c1-3cbaef0b4b46.jpg)
 
 
> #### Connect the 10K ohm resistor between the GND and A0 pin of the Bolt so that LDR and the resistor form a series connection. 

![m1_t4_s2_i5](https://user-images.githubusercontent.com/65165798/85008586-cce66880-b17a-11ea-8fcb-e9aa1aba11a0.jpg)

- Warning!! Make sure that at no point do the 3.3V (or even 5V) and GND pins or wires coming out of them touch each other.
- If you short power to Ground without a resistor even accidentally, the current drawn might be high enough to destroy the Bolt module 


### Thus, we are effectively measuring the voltage across the 10k Ohm Resistor and the final circuit should look like the image below:

![m1_t4_s2_i6](https://user-images.githubusercontent.com/65165798/85008817-1df65c80-b17b-11ea-84cc-777a4e45e3d9.jpg)


#### Now our circuit is ready. We may power on your device.


## Step 2: Connecting the circuit to the Cloud

#### Connect our Bolt device to the Bolt Cloud. We can skip this step if we already connected our Bolt device to the Bolt Cloud.

- To check if it is connected to Cloud, have a look at the green coloured Cloud LED on the Bolt WiFi module. It should be glowing.
![connections_wjwozpHcJ3](https://user-images.githubusercontent.com/65165798/85202151-fc83a500-b321-11ea-8c57-a3004b3584fb.jpeg)
 
## Step 3: Configuring the Product

Next Step will be to write the Software Coding for out project.

- Visit Cloud [cloud.boltiot.com](cloud.boltiot.com) and Login into your Account.
- Once we Login into our account, We'll see your Bolt Device which we have previously Linked to the Bolt Cloud.

![Screenshot (15)](https://user-images.githubusercontent.com/65165798/85203020-62732b00-b328-11ea-825a-dfd40b0822a4.png)

- We now need to create a **Product** with all our Code and Configurations for our project.

- Then we have to Click on the Products tab.

![Screenshot (23)](https://user-images.githubusercontent.com/65165798/85203233-e843a600-b329-11ea-92c6-7c650c759aeb.png)

- Give a name and assign a image to your product.

- We are naming our product as Plant_Monitor.

![Screenshot (24)](https://user-images.githubusercontent.com/65165798/85203341-ac5d1080-b32a-11ea-87f4-2af660913130.png)

- Now we are using our product as a Input Device for collecting the Light Intensity Data and also LDR is a Input device.

- We are collecting our data as a GPIO (General purpose Input/Output) and then click on the done button.


![Screenshot (17)](https://user-images.githubusercontent.com/65165798/85203474-c64b2300-b32b-11ea-864e-ca1d616a8501.png)

This will take you to the products page. Thus we have created a new **Product for our light monitoring system.**

- Products are created once and can be used for multiple Bolt devices. 
- This ensures scalability for IoT products we build on Bolt.

## Step 4: Configuring the Product:

Click on the Configure icon.

![Screenshot (25)](https://user-images.githubusercontent.com/65165798/85203615-93edf580-b32c-11ea-988b-a17caee20ac5.png)

- It will take you to the new Configuration page that has two tabs i.e. 
1. Hardware
2. Code

![Screenshot (20)](https://user-images.githubusercontent.com/65165798/85203676-ee875180-b32c-11ea-8d45-20eec3da3a6b.png)

> ### Part 1: Hardware.

#### Under the Hardware tab, you’ll be asked 3  steps.

#### Step 1.
Is already DONE.

#### Step 2.

In step 2, we have to select the pins as per the circuit designed and have to assign a unique variable name to them.
- We have used the pin AO and we will select it.
- We will aslo assign a name to it.

![Screenshot (26)](https://user-images.githubusercontent.com/65165798/85229769-632fbe00-b409-11ea-9f3f-afb7ff684bcb.png)

- Here I am using the name “light” and I will be using the same name in our code that I will be writing.
#### Step 3.

Third step is to select the Data collection rate i.e. selecting the interval of time after which the Data will be collected and sent to the Cloud.

![Screenshot (27)](https://user-images.githubusercontent.com/65165798/85229807-93775c80-b409-11ea-9045-08e2d55fdad6.png)

- Here I am selecting 5 MINUTES and the Data will be sent to the Cloud after every 5 min.
- If I’d select 10, the Data will be sent Cloud every 10 min and so on.
- You can play around with the values as you wish.


> ### Part 2: Coding.

- First we give a suitable name to our code file.

- I’ll give the name “light_monitor” and then choose the file type as “.js” (JavaScript), as we are using JavaScript to write this code.

![Screenshot (28)](https://user-images.githubusercontent.com/65165798/85229888-1a2c3980-b40a-11ea-87a8-9727574bed97.png)

- Then we just have to write one single line of code to display this data in the form of a table.

- The Code is **plotChart(“time_stamp”,”Variable_name”);**

As the Variable name is “light”, I’ll use light in the place of Variable name.
- Then the code becomes **plotChart(“time_stamp”,”light”);**

![Screenshot (29)](https://user-images.githubusercontent.com/65165798/85229927-6aa39700-b40a-11ea-92a7-568927ec31c3.png)

plotChart function, by default, will plot the data in the form of a Table.

- The first column will contain the timestamp i.e. the time at which the data was collected and the second column will be the value of light intensity measured at that time.

- Then click on the **Save** button.

![Screenshot (30)](https://user-images.githubusercontent.com/65165798/85229958-9888db80-b40a-11ea-8991-f5c8a3e02d4f.png)

In the next section, I’ll show how to Link the Product I have created for my Bolt device and also view the data collected.


