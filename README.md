# GO_SSLCertGen
It is a simple program that uses golang standard library packages to generate a SSL certificate.

It generates two files:
* cert.pem
* key.pem

These two files can be used later on running simple go web server using ListenAndServeTLS method.

---

NOTE that you won’t use them (the certificate and private key created here) in a production 
server, it’s useful to understand how an SSL certificate and private key can be generated
for development and testing purposes.