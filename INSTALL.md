# Install

## FUSE

**Linux**

```sh
sudo apt-get install fuse
```

**macOS**

Download and install from https://osxfuse.github.io/ or:

```sh
brew install fuse
```

## Node.js

Install Node.js from https://nodejs.org/.

## IPFS

Install and run the `go-ipfs` daemon from https://ipfs.io/. I know, I know, but until `js-ipfs` gets MFS this project is not useable with it.

```sh
ipfs daemon
```

Note, currently your daemon API needs to be running on the default port.

## IPFS FUSE

```sh
npm install --global ipfs-fuse
```

You need Python 2 to install, so you might need to tell gyp the path to Python2. For me it looked like this:

```sh
npm_config_python=/usr/local/opt/python2/bin/python2 npm i -g ipfs-fuse
```

## Dev
The recommended node version is 17.

```sh
nvm use 17
```

Clone the project and install project dependencies:

```sh
npm install
```

(Optional) You need Python 2 to install, so you might need to tell gyp the path to Python2. For me it looked like this:

```sh
npm_config_python=/usr/local/opt/python2/bin/python2 npm i
```
