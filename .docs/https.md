# HTTPS Dev Environment

## Fundamentals

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)

### Handshaking process

1. Public key and private key form a pair where data encrypted with the public key can only be decrypted with the corresponding private key.
1. In SSH, the first step is handshaking, where the client encrypts data using the server's public key, so the only one can decrypt the key that who has its private key which in that key the server.

### tips

1. SSH primarily uses symmetric encryption after the handshake.

## HTTPS in Web Apps

### dotnet

- When you run a .NET application with HTTPS locally, it's likely using a self-signed certificate generated on-the-fly, which is bound to localhost or a specific domain. Browsers and client applications often allow such certificates for local connections, making development and testing more convenient. However, for production deployments, you should use certificates signed by trusted CAs.

## Notes

1. How to Know localhost ip
![alt text](image-4.png)
