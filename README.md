# Nport (Net Port Link)

## Normal install

```sh
npm install git+https://github.com/tuanngocptn/nport.git
```

## Global install

```sh
npm install -g git+https://github.com/tuanngocptn/nport.git
```

# How to use

### Short way (with normal install)

```sh
npx nport --sub xxx -p 3000 # https://xxx.nport.link
```
### Short way (with global install)

```sh
nport --sub xxx -p 3000 # https://xxx.nport.link
```

### Full script (with normal install)

```sh
npx nport --server https://nport.link --subdomain xxx --hostname 127.0.0.1 --port 3000 # https://xxx.nport.link
```

### Full script (with global install)

```sh
nport --server https://nport.link --subdomain xxx --hostname 127.0.0.1 --port 3000 # https://xxx.nport.link
```

# Source from socket-tunnel

Tunnel HTTP connections via socket.io streams. Inspired by [localtunnel](https://github.com/localtunnel/localtunnel).

## Blog Post

[Read all about it](https://ericbarch.com/post/sockettunnel/)