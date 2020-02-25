# lamp

## Installation

https://phoenixnap.com/kb/how-to-install-lamp-stack-on-ubuntu

## Post installation 

```bash

sudo ufw allow 80

# or

sudo ufw allow http 

```

## SSL 

https://hostadvice.com/how-to/configure-apache-with-tls-ssl-certificate-on-ubuntu-18/
https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-apache-in-ubuntu-18-04

**Note**: A self-signed certificate will encrypt communication between your server and any clients. However, because it is not signed by any of the trusted certificate authorities included with web browsers, users cannot use the certificate to validate the identity of your server automatically