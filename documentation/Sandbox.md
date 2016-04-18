# Sandbox

## Importance of Security
>As the IoT grows, so do the security vulnerabilities of the linked objects.
>With the arrival of IoT several new types of devices are connected to IP networks.

* Medical equipment
* Buildings
* Cameras
* Industrial sensors
* Many other devices.

>All these devices need management Access to transport data securely over the internet.
### Secure Data Traffic
>Secure Data Traffic focuses on protecting critical data.
>Any data traffic between a device and the cloud (including information transmitted via mobile apps) should be examined to make sure it is secured.

### Cryptography Protocols
>In order to encrypt data we need to have protocols that stablish how the rules for this process.
>SSL & TLS are protocols that provide data encryption and authentication between applications and servers in scenarios where that data is being sent across an insecure network, such as checking your email.
>This two protocols are designed to work in the transport layer in the OSI Model.
>Protocols on higher layers (such as HTTP) can be left unchanged while still providing a secure connection. Underneath the SSL layer, HTTP is identical to HTTPS.

#### SSL
>Secure Sockets Layer1. 

#### TLS
> Transport Layer Security
> SSL's more secure "successor", TLS is the new version of SSL, 
 TLS also encrypts data in transit and requires a handshake between two authorized servers before it shows its contents.
#### Handshake
>Is a sub-protocol used to negotiate session information between the client and the server. The session information consists of a session ID, peer certificates, the cipher spec to be used, the compression algorithm to be used, and a shared secret that is used to generate keys.
