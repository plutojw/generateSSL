# generateSSL

1. Create ssl.conf
2. Command: 
    openssl req -x509 -new -nodes -sha256 -utf8 -days 3650 -newkey rsa:2048 -keyout gitlab.key -out gitlab.crt -config ssl.conf
3. Command:
    openssl dhparam -out dhparam.pem 2048

