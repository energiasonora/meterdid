# STARKID

a DID managing tool to communicate your public and private data with sovereignty


# LINKS
demo https://starkid.web.app

git https://github.com/xunorus/starkid


# INSTALL
```
nvm use 18    
nvm use 20

yarn                              
```

# RUN
```
yarn parcel src/index.html  --port 4444 --https
<!-- yarn parcel src/index.html src/connect.html  --port 4444 --https -->
```


# deploy to firebase

```
nvm use 18       
yarn parcel src/index.html --dist-dir public  --public-url ./
firebase deploy --only hosting:starkid
```

# log
v0.6 chat UI updates
v0.5 chat UI
v0.4 qr scans
v0.3 short address fix for starknet 64 character addresses