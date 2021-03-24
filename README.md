# how-install-nodejs-via-binary-archive
How to install Node.js via binary archive on Linux

## unzip
```
sudo mkdir /usr/local/lib/node
sudo tar -xJvf node-package.tar.xz
sudo mv /usr/local/lib/node/nodejs-folder /usr/local/lib/node/nodejs
```


## edit this file
```
~/.profile
```


## add this lines
```
export NODEJS_HOME=/usr/local/lib/node/nodejs
export PATH=$NODEJS_HOME/bin:$PATH
```

## refresh profile
```
. ~/.profile
```

## Test installation
```
node -v
npm version
```
