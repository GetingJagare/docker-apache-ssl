## App Starting
Copy project to app/ directory
```
mkdir db && mkdir logs && mkdir certs
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ./certs/apache-selfsigned.key -out ./certs/apache-selfsigned.crt
make run
```