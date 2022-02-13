
# OSI model
* OSI stands for open system interconnection.
* It is used to define. How data is transfered from one device to another.
* This model is introduced by ISO (International Organization for Standardization).
* It is  a seven layered model.
* Each  layer of this model contains a package of network protocols.
* The OSI model is just a theoretical model and used as refrence model. OSI model was never implemented on the 
  Internet.


## Layers of OSI model 


![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/computer-network-osi-model-layers.png)


## 1. Application layer
   At the very top of the OSI model stack we find the Application layer. The Application Layer is used 
   by the Network Applications (i.e Chrome,firefox) not only web browsers there are 
   dozens of Network Applications available. The main goal of Application layer is to 
   provide required Protocols for file Transfer,web surfing,virtual terminal etc. This layer acts as 
   a path between end user and the internet.
    
   There are various Application layer Protocols some of them are-

   1. HTTP - hyper text transfer protocol
   2. HTTPS - hyper text transfer protocol secure
   3. FTP - file transfer protocol
   4. NFS - network file system
   5. DHCP - dynamic host configuration protocol
   6. SMTP - simple mail transfer protocol
   
## 2. Presentation layer 
   Presentation layer is also called Translation layer. This layer takes the data form
   Application layer  and translates the data to machine code or any other required formate.
   There are more jobs which is also performed by Presentation layer (i.e data compression,data encryption/decryption)
    
   * Data Compression- Data compression is done in order to reduce the size of data. This helps in quick 
     transfer of data over the media.
   * Data Encryption/Decryption- Data Encryption translates the data into another form of
     code on the basis of some algorithm. This is used to prevent the data from attakers. Data Decryption
     is used to convert the data from encrypted form to normal form. Encryption is done at sender end & Decryption is receiver end.


## 3. Session layer
   The session layer is responsible for connection establishment,connection maintenance, authentication
   authorization, maintenance of session and also security.
   All these operation are performed by web browser and the functions of Application layer and
   Presentation layer is also performed by the web browser.

## 4. Transport layer
   The Transport layer takes care of the reliablity of connection. It is also responsible
   for End to End delivery of message. The reliablity of the connection is assured by performing
   these three operations on the data. It is also responsible for sending and reciving
   acknowledgements about sent and received data.
   
   * Segmentation - The of the data into multiple small chunks called Segmentation. Each
     segment of the data contains sequence number, port number & the data itself.
   * Flow control - Flow control tells that how much data is to be transfer 
     from sender to receiver such that there is minimal packet lost or no packet lost.
     It is the synchronization of speed of sending and receiving data packets.
   * Error controll - While transfering the data over a network via any medium. There
     might be any situation when one or more bits of the data gets currupted due to
     excess noise or something else. Error controll takes care that the curroption of data
     is as minimal as possible & if error occured transport layer uses automatic 
     repeat request to send the packet again.
## 5. Network layer
   The network layer takes care about transmission of data from sender to receiver 
   or any other intermediate node. It is also responsible for finding best possible
   path towards destination. The routing decision are made on the basis of IPaddress.

## 6. Data Link layer
   The Data link layer the second last layer of the OSI model. It is a software 
   implemented in network  interface card of the device. It is responsible for end to end
   delivery of data packets. Below given are the functions of data link layer.

    
   * Framing - It is the partition of data into meaning full bits.
   * Physical addressing - Physical address is also called MAC address which is 
     provided by the device manufacturer. After Framing the data link layer is responsible
     for addition of receivers MAC address in the header of each frame.
   * Error controll - While transfering the data over a network via any medium. There
     might be any situation when one or more bits of the data gets currupted due to
     excess noise or something else. Error controll takes care that the curroption of data
     is as minimal as possible & if error occured transport layer uses automatic 
     repeat request to send the packet again.
   * Flow control - Flow control tells that how much data is to be transfer 
     from sender to receiver such that there is minimal packet lost or no packet lost.
     It is the synchronization of speed of sending and receiving data packets.
   * Access controll - It refers to the controll of the access media over a network.

## 7. Physical layer
   Physical layer is the last layer of the OSI model. Physical layer is responsible
   for transfering of each bit of the data from one node to another. It is also responsible
   for sending the data to data link layer from receiver end.
   
   Functions of Physical layer are -
   
   * Bit synchronization - This helps in flow controll at bit level.
   * Bit rate control - Number of bits transfered/received per unit time.
   * Physical Topologies - It determines the topology of the network (i.e star,mesh)
   * Transmission Mode - It determines the nature of the media (i.e duplex,half-duplex,full-duplex)


## Refrences 
   [Geeksforgeeks](https://www.geeksforgeeks.org/layers-of-osi-model/).    
  



