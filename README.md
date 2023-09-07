# Download
1. Clone this repo
2. Clone client https://github.com/m-rolana/multer-demo-client
3. Clone server https://github.com/m-rolana/multer-demo-server

# Run

### Run everything at once
In current repo folder run
```
./index.sh
```

<br/>

If there no permissions add some to make it executable
```
chmod 655 ./index.sh
```
and then run script one more time
```
./ index.sh
```
### OR run separatly

### server
`node ./server/index.js`

### client
just open with browser `./client/index.html`

# How to use
1. Choose image in client
2. Click `Upload` button
3. Observe image link on client page and image info in server logs
4. Open image link you got on client
5. Observe uploaded image, which is now saved on server 

# TODO
- [ ] Rewrite client on React
