# Sandbox

- http://techcrunch.com/2016/04/22/how-iot-security-can-benefit-from-machine-learning/?utm_content=buffer6ff2b&utm_medium=social&utm_source=twitter&utm_campaign=aeris
- http://techcrunch.com/2015/10/24/why-iot-security-is-so-critical/

## Importance of Security
>As the IoT grows, so do the security vulnerabilities of the linked objects.
>With the arrival of IoT several new types of devices are connected to IP networks.

* Medical equipment
* Buildings
* Cameras
* Industrial sensors
* Many other devices.

>All these devices need management Access to transport data securely over the internet.
## Secure Data Traffic
>Secure Data Traffic focuses on protecting critical data.
>Any data traffic between a device and the cloud (including information transmitted via mobile apps) should be examined to make sure it is secured.
##Software Security Solutions

### Cryptography Protocols
>In order to encrypt data we need to have protocols that stablish how the rules for this process.
>SSL & TLS are protocols that provide data encryption and authentication between applications and servers in scenarios where that data is being sent across an insecure network, such as checking your email.
>This two protocols are designed to work in the transport layer in the OSI Model.
>Protocols on higher layers (such as HTTP) can be left unchanged while still providing a secure connection. Underneath the SSL layer, HTTP is identical to HTTPS.
>The source and the destination must have the correct SSL/TLS certificate in order to do a correct handshake.


#### SSL
>Secure Sockets Layer1. 

#### TLS
> Transport Layer Security
> SSL's more secure "successor", TLS is the new version of SSL, 
 TLS also encrypts data in transit and requires a handshake between two authorized servers before it shows its contents.
#### Handshake
>Is a sub-protocol used to negotiate session information between the client and the server. The session information consists of a session ID, peer certificates, the cipher spec to be used, the compression algorithm to be used, and a shared secret that is used to generate keys.
### Examples of Software Security Solutions
>NanoSSL
>Authenticates endpoints and encrypts channels to provide session privacy and security on the Internet. NanoSSL operates at the transport layer in the OSI stack, and provides secured data transport for applications. It supports peer negotiation for algorithm selection, public key based exchange of secret session keys and X.509 certificates. 
>WolfSSL
>The wolfSSL embedded SSL library (formerly CyaSSL) is a lightweight, portable, C-language-based SSL/TLS library targeted at IoT, embedded, and RTOS environments primarily because of its size, speed, and feature set. 
>Mosquitto
>Is an open source message broker that implements the MQTT protocol, provides a lightweight method of carrying out messaging using a publish/subscribe model. 
MosquittoSSL provides SSL support for encrypted network connections and authentication. 


## Hardware Security Solutions
### Discrete TPM
>Discrete Trusted Platform Module (TPM) is a microcontroller that stores encryption keys, passwords and digital certificates. 
>The discrete form is the silicon module was separated from other system elements and communicated with them via a dedicated hardware bus.
### Secure Boot
>Secure Boot is a security standard developed by members of the PC industry to help make sure that your PC boots using only software and hardware modules that are trusted by the PC manufacturer.
### Hands-On
>What happens if a new hardware isn’t trusted? 
>How do I edit my PC’s Secure Boot database? 
>How can I add hardware or run software or operating systems that haven’t been trusted by my manufacturer? 


# 

https://www.npmjs.com/package/lda
https://github.com/intelsdi-x/snap
spark
cloudera
hive
nkkdi
kafka
