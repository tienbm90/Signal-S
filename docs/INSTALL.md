#### CREATE CERT  FOR SIGNAL SERVER

```
cd /opt/
openssl req -newkey rsa:2048 -nodes -keyout key.pem -x509 -days 365 -out certificate.pem
openssl x509 -text -noout -in certificate.pem
openssl pkcs12 -in certificate.p12 -noout -info
readlink -f certificate.p12 
chmod 755 ./*.prem
chmod 755 ./*.pem
openssl rsa -in key.pem -check
openssl rsa -in certificate.p -check
openssl rsa -in certificate.pem-check
openssl rsa -in certificate.pem -check
openssl rsa -in key.pem -check
openssl rsa -in key.pem -outform PEM -out cert.key  

```
 