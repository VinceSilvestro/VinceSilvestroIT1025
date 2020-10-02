# Executive Summary

In this lab, I survey the concepts of cybersecurity and networking. I identify networking components, topologies and the role of NSA in networking security, and define encryption technologies and approaches to cybersecurity to reduce threats.

---

# Lucidchart

I used Lucidchart, a tool to help people better visualize processes and make diagrams, to organize the operations of an imaginary computer program. This program would ask for a number and then print "Big" if the number is greater than 15 or "Small" if the number is less than 15. Using Lucidchart for this task was straightforward. 

The Shapes sidebar in the platform offers similar tools available in Microsoft Paint or Google Drawings, for example, and is all-around user-friendly. I have seen flowcharts before, but was interested to learn that there are certain conventions for starting a flowchart, making a decision within the process, and ending a flowchart. It turns out that there are specific shapes for each of these steps for easy identification and implementation. I was surprised to discover that Lucidchart also offers templates for venn diagrams, family trees, and even floor plans.

Generally speaking I think that flowcharts are a great way to go about solving problems rationally and can be used in day-to-day life, too. Every day has a beginning, each decision that we make has consequences that we must face throughout the day, and every day has an end. The mind map template appears to be useful in this light. 

---

# Introduction to Networking

- ### Data Transmission 

To understand the basics of networking, it is important to understand terms like packet, packet-switching, IP address, DNS, and protocol. A packet refers to the fundamental unit of data transmitted over the Internet. A single packet contains the sender’s address, the destination address, a sequence number (which helps in ordering the man packet requests), and a segment of the overall message being delivered. Packet-switching is technology that allows packets of data to be routed based on its destination address. It occurs when routers reorganize packets for the most effective user experience possible. IP addresses, found in packets, are unique identifying numbers found on every individual device connected to the internet. The Domain Name System/Server, or DNS, is essentially a directory of IP address common names. DNS comes into play when a user requests to access a website. A DNS server is then queried and at that point returns the IP address of the host requested, which allows for proper routing. A protocol denotes a set of rules to allow devices to communicate. They dictate how communications take place on a given network.

- ### Network Hardware

A hub connects network devices together on an internal network with the use of ethernet cables. A hub merely copies all packets to each connected network device and is not capable of selectively transferring data from one specific device to another. Switches differ in that they can in fact pass along data from one machine to another (or a group of them) exclusively. This is accomplished by virtue of the switch’s ability to read the physical MAC addresses of connected devices. This makes switches generally preferable over hubs as they reduce excessive network traffic, thus saving bandwidth.  

As cloud computing continues to dominate, another piece of network hardware called the router is even more preferred over the switch—routers are used to connect one network to another network based on their IP address. Hubs and switches are used to create networks, and routers are used to connect networks. 

- ### Network Topologies

A network topology is a layout of how a network communicates with different devices. Most commonly, the star topology is a network made up of computers and hardware such a hub or a switch. When the switch in a star topologies is compromised, this is known as a single point of failure.

Infrastructure Topology and Wireless Mesh are two wireless topologies. They are similar because they both involve modems drawing an internet connection into a building and also switches to further carrying signals to wireless routers and then wireless devices. Wired devices are present in Infrastructure but not present in Wireless Mesh topologies. Wireless mesh takes the signal from the wireless router connected to the switch and repeats it to other nearby WAPs in the network. In my opinion, Wireless Mesh topologies are better because they offer stronger backup options to users in the network. 

- ### Network Design
	
The network I designed on Lucidchart exhibits an Infrastructure Topology. It begins with a modem (at the top) providing signal to the wired router below it. The router bridges the modem with a wireless router (left) and a wired desktop computer. The wireless router or WAP carries the signal to the printer (bottom left) and wireless laptop (bottom right), providing internet access. 

- ### NSA/CSS

The National Security Agency or NSA is an active player in U.S. cybersecurity. The agency leads the government in ways to encrypt and decrypt data. It protects the country and our allies by managing computer network operations incessantly. 

---

# Cybersecurity and Encryption

- ### Information Systems Security

In computing, the information security triad is Confidentiality, Integrity, and Availability (CIA). Hypothetically, as a part of the Amazon.com online chat, each component of the security triad would impact my job in some way. I would have moral, and probably legal, obligations to keep Amazon customers’ purchase and browsing history private. Further, I would need to work with integrity. This means protecting user information and not exploiting customers’ home addresses, phone numbers, or credit card numbers. Availability here would mean a couple of things: twenty-four online accessibility of the personal Amazon-stored information to customers and around-the-clock availability of the same critical information to relevant Amazon.com online chat workers. 

The three daily tasks that require authentication are as follows: identifying someone through something they know, something they have, or something they are. Each one of these elements can be combined with another distinct means of authentication to yield multi-factor authentication.

ACL and RBAC are two common types of access control systems which determine which users have permission to read, modify, add, or delete information. ACL, the Access Control List is a central place for specialists to keep track of the specific permissions for individual users. These permissions include reading, writing, deleting, and adding. In RBAC users are assigned to roles and then those roles are assigned the access.  Most administrators agree that RBACs are simpler and superior to ACLs. 

In public key encryption, both the sender and receiver of an encrypted message have their own set of public and private keys. These keys encrypt and decrypt their conversations. In a process known as asymmetric encryption, the sender of a plaintext message first uses a public key to encrypt the information. In the communication channel, this encrypted code is referred to as ciphertext. Finally, the recipient of the messages decodes the ciphertext with their personal private key to access the information. 

Public key cryptography is crucial for sharing information to only certain people or specific groups of people. It prevents encoded information from being obtained by rivals of a corporation or national enemies, for example. 

- ### Cryptography 

Using the Caesar Cipher Exploration box, my secret message came out to be “jvtivkj 
jvtivkj riv ef wle.” To encrypt my message using Caesar Cipher, I applied a shift of 
18 to each letter of the original message. To decrypt the message, you would simply shift each letter in the encrypted text back 18 letters of the alphabet. This would translate to “secrets secrets are no fun.” 

The message that I typed into the Frequency Fingerprint Exploration section was 
“secrets secrets hurt someone.” This resulted in a large number of E’s and S’s, a 
moderate amount of C’s, O’s, R’s, T’s, and a small number of H’s, M’s, N’s, and U’s. In other languages, these results would be different as not all languages share the same alphabet. In the Italian alphabet, for example, there are 5 letters “missing,” which are J, K, W, X, and Y. 

A polyalphabetic cipher creates a lighter fingerprint than the Caesar cipher. It is where multiple Caesar shifts are found in one message. Here, participants in a conversation agree on a shift word instead of a shift number. First, the sender converts the shift word into numbers according to the letter position in the alphabet. The sequence of numbers repeats and is applied to each letter of the message. Next, each letter is encrypted by shifting according to the number below it. The receiver of the message reverses this process to decode the text.  

In the Polyalphabetic Exploration box, I entered “wise men have no secrets” with my shift word being “guess.” The box gave out the message “ddxx fli mtol it lxjmjml.” The box took my shift word and analyzed each letter of it in terms of its position in the alphabet. This progression of shift numbers was applied to the message and each of its letters were translated using the Caesar Cipher. 

- ### Brute-Force

In hacking, brute-force is a technique that analyzes a cipher and generates keys until it can correctly guess the decryption key. Kerckhoffs’ principle states that a cipher “should still be secure even if everyone knows how the cipher works and someone else has the ciphertext.” When creating passwords, for example, internet users must keep in mind Kerckhoffs’ principle; the part of the cipher that keeps the message secret is the key; and realize that Brute-force is still a powerful way for hackers to access and manipulate our personal data. 

---

# Conclusion 

I was interested to find that I already knew most of the basic networking vocabulary. However before this lab, I did not make the connection that the internet was simply a (distributed packet-switched) network of (independently operated) networks, hence its name. Discovering that routers are used to connect one network to another network based on their IP address was also a light bulb going off in my head. We are transitioning into a world where cloud computing and virtualization are dominant. With these changes, the idea that we can help other people with useful scientific information more quickly and safely than ever before is promising to the future of humanity. 
