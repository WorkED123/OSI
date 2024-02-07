<h1> Lesson 2.2: The OSI Model </h1>
<h2> Summary</h2>

<p1>The Open System Interconnection (OSI) model is a networking framework that implements protocols in seven layers. The OSI model doesn't perform any functions in the networking process; instead, it is a conceptual framework to help better understand the complex interactions that are going on.</p1>
<br>

<h2>Learning Objectives</h2>
<ul>
<li>Students will define the layers' functions and explain how devices utilize them to communicate over the Internet.</li>
  <br>
<li>Students will apply the abstraction principle to simplify complex ideas and enable solutions to be used in different contexts.</li><br>
  
</ul>

<h2>Vocabulary and Acronyms</h2>

<ul>
<li>

  **OSI Model**</li>
  
<li>

**Encapsulation**</li>
  
<li>
  
**Packets**</li>

<li>
  
**Abstraction**</li>

<li>
  
**TCP**</li>


<li>
  
**UDP**</li>


<li>
  
**Segment**</li>

<li>
  
**Frame**</li>

<li>
  
**Header**</li>

</ul>




<h2>Lesson Prerequisites</h2>
<p1>Lesson 2.1: Introduction to Networks. </p1>
<br>


<h2>Introduction</h2>
Today, we're diving into a foundational concept in networking: The OSI Model. If you've ever wondered how computers communicate in a networked environment, then today's lesson is for you.

<h2>What is the OSI Model?</h2>
The OSI (Open Systems Interconnection) Model is a theoretical framework that categorizes the functions of a networking system into seven distinct layers. Its creation by the International Organization for Standardization (ISO) in 1984 aimed to standardize networking protocols and enhance interoperability between different products and software.

<h2>Why is it Relevant Today?</h2>
While we have more modern systems and architectures, understanding the OSI Model helps us grasp the fundamental principles underlying all networked communications.

<h2>A Deep Dive into the 7 Layers</h2>

<ul>
	<li><h4>1. Physical Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> This layer deals with the tangible aspects of data transfer. Think of it as the "nuts and bolts" of networking.</li>
			<li><ins>Components:</ins> Network hubs, cables, repeaters, adapters, modems.</li>
			<li><ins> Primary function:</ins> Transmitting raw, unstructured data bits.</li>
		</ul>
	<li><h4>2. Data Link Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> Ensures data transfer between directly connected nodes.</li>
			<li><ins>Components: </ins> Frames (packets of data)</li>
			<li><ins> Sublayers: </ins></li>
			<ul><li> MAC (Media Access Control): Manages how devices access and transmit on a network.</li>
			<li> LLC (Logical Link Control): Deals with flow/error control and recognizes line protocols.</li></ul>
		</ul>
	<li><h4>3. Network Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> Directs data frames based on their address.</li>
			<li><ins>Components: </ins> Routers.</li>
			<li><ins> Primary function: </ins> Directing data using logical addresses like IP addresses.</li>
		</ul>
	<li><h4>4.Transport Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> Supervises data transfer between systems. </li>
			<li><ins>Components:</ins>  Data packets.</li>
			<li><ins> Primary function: </ins> Ensures complete data transfer and manages data size, sequencing, and error checking. E.g., TCP (Transmission Control Protocol).</li>
		</ul>
	<li><h4>5. Session Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> Handles the "conversations" or connections between computers.</li>
			<li><ins> Primary function: </ins> Establishing, managing, and terminating connections. Also responsible for authentication and reconnections.</li>
		</ul>
	<li><h4>6. Presentation Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> Ensures that data is in a usable format.</li>
			<li><ins> Primary function: </ins>  Translates data for the application layer and deals with encryption and decryption.</li>
		</ul>
	<li><h4>7. Application Layer</li></h4>
		<ul>
			<li><ins>What is it?</ins> The layer where users and software applications interact with the network. </li>
			<li><ins> Primary function: </ins> Identifying communication partners, checking resource availability, and ensuring synchronized communication. Think of your web browsers and applications like Office 365!</li>
		</ul>
</ul>

<p1>Although theoretical, the OSI Model provides a blueprint for understanding the complex processes in network communication. Learning about each layer and its functions gives you a clearer perspective on how and why cybersecurity measures are vital at every step of the data transmission process. Remember, knowledge of the basics strengthens our understanding of more advanced topics, and the OSI Model is fundamental to networking.</p1>


<h2>Real-world Applications of the OSI Model</h2>
<ul>
 <li><h4>1. Physical Layer</h4></li>
	<ul>
		<li><ins>Protocols and Standards</ins>: USB, Ethernet (IEEE 802.3), Bluetooth, HDMI.</li>
		<li><ins>Devices and Technologies</ins>: Cables (e.g., Cat5, Cat6), switches, repeaters, modems.</li>
		<li><ins>Real-world application</ins>: You operate at the physical layer when you connect your computer to a router using an Ethernet cable.</li>
	</ul>
 <li><h4>2. Data Link Layer</h4></li>
	<ul>
		<li><ins>Protocols</ins>: Ethernet for LAN, PPP (PointtoPoint Protocol) for direct connections.</li>
		<li><ins>Devices and Technologies</ins>: Bridges, switches, network interface cards (NIC).</li>
		<li><ins>Real-world application</ins>: This interaction happens at the data link layer when your computer's MAC address communicates with another MAC address within a LAN.
</li>
	</ul>
 <li><h4>3. Network Layer</h4></li>
	<ul>
		<li><ins>Protocols</ins>: IP (Internet Protocol), ICMP (Internet Control Message Protocol), RIP (Routing Information Protocol).</li>
		<li><ins>Devices and Technologies</ins>: Routers, Layer 3 switches.</li>
		<li><ins>Real-world application</ins>: If you've ever used the 'ping' command to check the connectivity to a website, you've interacted with the network layer using ICMP.</li>
	</ul>
 <li><h4>4. Transport Layer</h4></li>
	<ul>
		<li><ins>Protocols</ins>: TCP (Transmission Control Protocol), UDP (User Datagram Protocol).</li>
		<li><ins>Real-world application</ins>: When you visit a website, and the data is broken down into packets to be transmitted and reassembled at your end, this is TCP at work.</li>
		
</ul>
 <li><h4>5. Session Layer</h4></li>
	<ul>
		<li><ins>Protocols</ins>: NetBIOS, RPC (Remote Procedure Call), PPTP (PointtoPoint Tunneling Protocol).</li>
		<li><ins>Real-world application</ins>: When you establish a VPN (Virtual Private Network) connection, the session layer protocols like PPTP help set up, coordinate, and terminate your connections.</li>
		
</ul>
 <li><h4>6. Presentation Layer</h4></li>
	<ul>
		<li><ins>Protocols and Standards</ins>: SSL/TLS (Secure Sockets Layer/Transport Layer Security), JPEG, GIF, MPEG, ASCII, EBCDIC.</li>
		<li><ins>Real-world application</ins>: When you access a secure website, and the data is encrypted or decrypted, this occurs at the presentation layer. The tiny padlock beside the website's URL indicates SSL/TLS.</li>
		
</ul>
 <li><h4>7. Application Layer</h4></li>
 <ul>
		<li><ins>Protocols</ins>: HTTP/HTTPS (Hypertext Transfer Protocol/Secure), FTP (File Transfer Protocol), SMTP (Simple Mail Transfer Protocol), DNS (Domain Name System).</li>
		<li><ins>Applications and Services</ins>: Web browsers (like Chrome or Firefox), email services (like Gmail or Outlook), domain name resolution.</li>
		<li><ins>Real-world application</ins>: When you type a website address into your browser, DNS (service at the application layer) translates that human-readable domain into an IP address, enabling you to access the desired website.</li>
	</ul>
	
</ul>



<h2>Conclusion</h2>

While the OSI Model is a theoretical framework, its layers provide a foundation for many daily networking protocols and technologies. Understanding the real-world applications of each layer is essential for anyone looking to delve deeper into network administration, cybersecurity, and IT in general.



<h2> Presentation</h2>



<h2> Hands-On Labs</h2>

<a href = "https://www.educaplay.com/learning-resources/1576783-osi_layers.html"> Play OSI Layers Matching Game </a> - Matching OSI Terms to the correct layer.

<h2> Additional Resources</h2>

<a href="https://www.guru99.com/layers-of-osi-model.html"> Layers of OSI Model Explained </a> - Brief overview of the OSI Model.<br>
<br>
<a href="https://www.freecodecamp.org/news/osi-model-networking-layers-explained-in-plain-english/"> The OSI Model </a> - The 7 Layers of Networking Explained in Plain English.<br>
<br>
<a href="https://youtu.be/qpsWLFMPlS4">  Introduction to the OSI Model with Real-World Examples </a>
