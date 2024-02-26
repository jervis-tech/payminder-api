# payminder-api


## Setup Go environment

### Download goenv
```
  git clone https://github.com/go-nv/goenv.git ~/.goenv
```

### Setup environment variables
```
  echo 'export GOENV_ROOT="$HOME/.goenv"' >> ~/.bashrc
  echo 'export PATH="$GOENV_ROOT/bin:$PATH"' >> ~/.bashrc
  echo 'eval "$(goenv init -)"' >> ~/.bashrc
  echo 'export PATH="$GOROOT/bin:$PATH"' >> ~/.bashrc
  echo 'export PATH="$PATH:$GOPATH/bin"' >> ~/.bashrc
```

### Install goenv
```
  goenv install 1.19.3
  goenv global 1.19.3
```
```
  go version
```