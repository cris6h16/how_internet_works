# How does the Internet Work?
Before we learn what the Internet is, we need to understand what a Network is. A network is a group of computers or other devices which are connected to eachother. For example, you at your home might have a network of computers and devices. Your friend living next door might have a similar network of devices. Their neighbor might have a similar network of devices. All these networks when connected together form the internet.
## How the Internet Works: An Overview
internet works by connecting devices and computer systems together using a set of standardized protocols. These protocols define how information is exchanged between devices and ensure that data is transmitted reliably and securely.  

**The core of the internet is a global network of interconnected routers, which are responsible for directing traffic between different devices and systems.** When you send data over the internet, it is broken up into small packets that are sent from your device to a router. The router examines the packet and forwards it to the next router in the path towards its destination. This process continues until the packet reaches its final destination.  

To ensure that packets are sent and received correctly, the internet uses a variety of protocols, including the Internet Protocol (**IP**) and the Transmission Control Protocol (**TCP**). **IP is responsible for routing packets to their correct destination**, while **TCP ensures that packets are transmitted reliably and in the correct order**.  

In addition to these core protocols, there are a wide range of other technologies and protocols that are used to enable communication and data exchange over the internet, including the Domain Name System (DNS), the Hypertext Transfer Protocol (HTTP), and the Secure Sockets Layer/Transport Layer Security (SSL/TLS) protocol.  

## Basic Concepts and Terminology

To understand the internet, it’s important to be familiar with some basic concepts and terminology. Here are some key terms and concepts to be aware of:

- **Packet**: A small unit of data that is transmitted over the internet.
- **Router**: A device that directs packets of data between different networks.
- **IP Address**: A unique identifier assigned to each device on a network, used to route data to the correct destination.
- **Domain Name**: A human-readable name that is used to identify a website, such as google.com.
- **DNS**: The Domain Name System is responsible for translating domain names into IP addresses.
- **HTTP**: The Hypertext Transfer Protocol is used to transfer data between a client (such as a web browser) and a server (such as a website).
- **HTTPS**: An encrypted version of HTTP that is used to provide secure communication between a client and server.
- **SSL/TLS**: The Secure Sockets Layer and Transport Layer Security protocols are used to provide secure communication over the internet.

## The Role of Protocols in Internet
There are many different protocols used in internet communication, including the Internet Protocol (IP), the Transmission Control Protocol (TCP), the User Datagram Protocol (UDP), the Domain Name System (DNS), and many others.  

IP is responsible for routing packets of data to their correct destination, while TCP and UDP ensure that packets are transmitted reliably and efficiently. DNS is used to translate domain names into IP addresses, and HTTP is used to transfer data between clients and servers.

## Understanding IP Addresses and Domain Names
IP addresses and domain names are both important concepts to understand when working with the internet.

An IP address is a unique identifier assigned to each device on a network. It’s used to route data to the correct destination, ensuring that information is sent to the intended recipient. IP addresses are typically represented as a series of four numbers separated by periods, such as “192.168.1.1”.

Domain names, on the other hand, are human-readable names used to identify websites and other internet resources. They’re typically composed of two or more parts, separated by periods. For example, “google.com” is a domain name. Domain names are translated into IP addresses using the Domain Name System (DNS).

DNS is a critical part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address. Your computer then uses that IP address to connect to the website or other resource you’ve requested.

## Introduction to HTTP and HTTPS
HTTP is the protocol used to transfer data between a client (such as a web browser) and a server (such as a website). When you visit a website, your web browser sends an HTTP request to the server, asking for the webpage or other resource you’ve requested. The server then sends an HTTP response back to the client, containing the requested data.

HTTPS is a more secure version of HTTP, which encrypts the data being transmitted between the client and server using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption. This provides an additional layer of security, helping to protect sensitive information such as login credentials, payment information, and other personal data.

## Building Applications with TCP/IP

TCP/IP (Transmission Control Protocol/Internet Protocol) is the underlying communication protocol used by most internet-based applications and services. It provides a reliable, ordered, and error-checked delivery of data between applications running on different devices.

When building applications with TCP/IP, there are a few key concepts to understand:

- **Ports**: Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.
- **Sockets**: A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
- **Connections**: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection.
- **Data transfer**: Once a connection is established, data can be transferred between the applications running on each device. Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.

When building applications with TCP/IP, you’ll need to ensure that your application is designed to work with the appropriate ports, sockets, and connections. You’ll also need to be familiar with the various protocols and standards that are commonly used with TCP/IP, such as HTTP, FTP (File Transfer Protocol), and SMTP (Simple Mail Transfer Protocol). Understanding these concepts and protocols is essential for building effective, scalable, and secure internet-based applications and services.

## Securing Internet Communication with SSL/TLS

As we discussed earlier, SSL/TLS is a protocol used to encrypt data being transmitted over the internet. It is commonly used to provide secure connections for applications such as web browsers, email clients, and file transfer programs.

When using SSL/TLS to secure internet communication, there are a few key concepts to understand:

- **Certificates**: SSL/TLS certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party (a Certificate Authority) to verify their authenticity.

- **Handshake:** During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.

- **Encryption**: Once the secure connection is established, data is encrypted using the agreed-upon algorithm and can be transmitted securely between the client and server.

When building internet-based applications and services, it’s important to understand how SSL/TLS works and to ensure that your application is designed to use SSL/TLS when transmitting sensitive data such as login credentials, payment information, and other personal data. You’ll also need to ensure that you obtain and maintain valid SSL/TLS certificates for your servers, and that you follow best practices for configuring and securing your SSL/TLS connections. By doing so, you can help protect your users’ data and ensure the integrity and confidentiality of your application’s communication over the internet.


### Extracted from
- [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work#how-the-internet-works-an-overview)
