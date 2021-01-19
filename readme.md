## Run:
    1)openssl req -newkey rsa:2048 -x509 -nodes -keyout server0.key -new -out server0.crt -config ssl_certif.cnf -days 365
    2)openssl pkcs12 -export -out server0.pfx -inkey server0.key -in server0.crt -passin pass:keyServer -passout pass:pfxServer
##RunServer:
![screen1](static/0a7e7bce-682a-40e5-805d-2140616d2cb4.jfif)
