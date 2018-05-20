## Utopian reviews

To start working on it

```
npm install
npm start
```

For SSL paste the certificate and key files in bin folder and uncomment line 13-19.

LetsEncrypt was used to generate SSL certificates

On server

After ssh stop the running server

```
forever stopall
```

Pull the changes or clone the repository

Make sure the SSL cert and privkey is present in bin folder

after that
```
cd bin
forever start www
```

### AUTHOR

ms10398
