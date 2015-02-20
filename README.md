# Setup
To run fmfserver on your machine you first need to move into your root
to do so run the following in the command line: 
```
cd
```

Next open your bash_profile in nano.
```
nano .bash_profile
```

Create an enviroment variable by copying the line below into your bash_profile
```
export FMF_ASSET_PATH='http://localhost:9000'
```

Now we need to run the `source` command on the `.bash_profile`
```
source ~/.bash_profile
```

Now navigate back to where you cloned the fmfserver directory and run the following
```
sudo npm install
```

and finally to run the server use the following
```
nodemon server.js
```

