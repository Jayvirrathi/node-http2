## HTTP/2 Example



### Run Command [URL](https://localhost:8000/)
```
npm run start
```

### Certificate 
```bash
openssl req -x509 -newkey rsa:4096 -nodes -sha256 -subj '/CN=localhost' -keyout localhost-private.pem -out localhost-cert.crt
```