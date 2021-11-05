# docker-php-apache-ssl
Docker Compose for PHP with apache and SSL

```bash
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ./docker/ssl/cert-key -out ./docker/ssl/cert.crt
```
