# Executive Summary
Lab 2 covered the different components inside of computers and what each parts role was. we covered the CPU, memory, storage, the motherboard, input devices, and output devices. we discussed how these different parts interact with each other and what affects the speed they interact with one another.<br/>

Lab 2 also covered data representation, including binary, decimal, and hexadecimal. we discussed how to convert from one unit to another and what uses each format.
## Hardware
### ALU and the Control Unit
The ALU or Arithmatic Logic Unit, and the Control Unit interact with one another inside the CPU to do all the mathematic functions that the computer does. First, the Control unit tells the ALU what kind of function is going to be done, before the data gets input. the data is then input and it is checked if the data, which is stored in a register. whenever the data needs to move, it will be transfered by the bus, however only 1 piece of data can be used on the but at the time. this process will continue until the final data is calculated. the data will then be sent out of the system.
### CPU, Input and Output
Input and output functions are important to all computers. keystrokes, mouse clicks, microphones, and even cameras serve as input devices, data being put into a device. output functions are just as important. audio sounds and displays such as your computer screen allow you to observe the data collected and make sure it is correct. the CPU and Memory serve as the connection between the two, storing the data and calculating the information.<br/>

An example is shopping at a grocery store. when at a self check out line, there are multiple different ways to input your purchases. you can use the camera to scan the bar code. use a keypad or touchscreen to enter the product ID, and in the case of produce, put the product on the scale to determine weight. from here. the device takes all that data, stores it in the system to keep for inventory purposes with t he memory, and calculates the cost for the product with the CPU. after the final calculated data is found, it will be either displayed or read out to the customer, depending on the device, where they can validate the price is correct.
### Logic Gates and Circuit
Logic gates are devices, both physical and coded, that are able to be used to help a machine determine what data is needed and what do return as an output in different situations. There are 7 different basic logic functions that can be used to determine different outcomes. The charts below show how each gate impacts the data inputed, however several key terms should be known to utilize gates to the fullest.<br/>

One term to know is what it means if X is in front of a term, such as Xor. if an X is in front of a term, it mean "exclusive", or that the data must exclusively be the function fulling. an example is Xor and Or: The difference is with Or being `True` if input 1 and 2 are `True`, including if both are `True`. However Xor is `True` only if input 1 **OR** 2 are `True`, not both.<br/>

Another key term to know is N in front of a term. this means "not", or that the output will be `True` if the gate would normally put out `False`, and vice versa. An example that can be used is And versus Nand. And gates only put out true if both Input 1 and 2 are `True`, otherwise it will output `False`
##### Not

| Input | Output |
| ------ | ------ |
| True | False |
| **False** | **True** |
##### And

| Input 1 | Input 2 | Output |
| - | - | - |
| False | False | False |
| False | True | False |
| True | False | False |
| **True** | **True** | **True** |
##### Or

| Input 1 | Input 2 | Output |
| - | - | - |
| False | False |  False |
| **False** | **True** | **True** |
| **True** | **False** | **True** |
| **True** | **True** | **True** |
##### Nand

| Input 1 | Input 2 | Output |
| - | - | - |
| **False** | **False** |  **True** |
| **False** | **True** | **True** |
| **True** | **False** | **True** |
| True | True | False |
##### Nor

| Input 1 | Input 2 | Output |
| - | - | - |
| **False** | **False** |  **True** |
| False | True | False |
| True | False | False |
| True | True | False |
##### Xand

| Input 1 | Input 2 | Output |
| - | - | - |
| **False** | **False** |  **True** |
| False | True | False |
| True | False | False |
| **True** | **True** | **True** |
##### Xor

| Input 1 | Input 2 | Output |
| - | - | - |
| False | False | False |
| **False** | **True** | **True** |
| **True** | **False** | **True** |
| True | True | False |

### IEEE - Ethically Aligned Design
The Institute of Electrical and Electronics Engineers, or IEEE is a group founded out of New York, USA, whose goal is to "foster technological innovation and excellence for the benefit of humanity." as of 2010, the group had over 395,000 members in 160 different countries. Groups such as the IEEE also help encourage and reccomend different Ethics Systems for machines and artifical intelligence, which has been growing in importances the further technology develops.<br/>

Robotics ethics has been developing in science since the first machine was capable of independant calculations. However author Issac Asimov was one of the first people to develop an Ethics code for robots. these were:<br/>
**Law 1:** "robot may not injure a human being or, through inaction, allow a human being to come to harm."<br/>
**Law 2:** "A robot must obey orders given it by human beings except where such orders would conflict with the First Law."<br/>
**Law 3:** "A robot must protect its own existence as long as such protection does not conflict with the First or Second Law."<br/>
**Law 4 (Zeroth Law):** "A robot may not harm humanity, or, by inaction, allow humanity to come to harm."<br/>

However, many different people have argued for different processes as well as who should decide the ethics a robot decides, most commonly utilitarianism. These codes are may be insignificant, however they could, if improperly written, lead to the doom of humanity in hyperbolic scenarios. 
## Data Represenation
### Numeric Conversions
The differences between binary (base 2), Decimal (base 10), and Hexadecimal (base 16) is the value that can be stored in 1 position before cycling one digit higher. in binary, each position can only hold 2 positions before it must cycle to a higher digit (0000, 0001, 0010...), when in Decimal it can hold 10 positions before cycling (00, 01, 02.. ..08, 09, 10), and Hexadecimal can hold 16 positions before cycling (00, 01, 02.. ..0E, 0F, 10). 
### Hexadecimal Color Representation
When identifying colors to put them on into number, the standardized system is hexadecimal. Since any color can be made with Red, Green, and Blue, the system used includes a number between 0 and 255 in the order red, green, blue; or rgb(###,###,###). The problem with this format, and sites that rely on it, is that many users dont know what #ffffff, or white, means in that format. since ff in hexadecimal is 16x16, there is 100% red, 100% green, 100% blue. this is an extremely difficult numbering system to first understand and many sites rely on a color picker system instead and give you the associated code instead.
# Conclusion
