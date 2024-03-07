# fly

fly is a wrapper script for Ubuntu/Debian/Termux that connects the standard package manager with my own package manager

## Normal Pakage Install

```bash
fly install <pakage>
```

```bash
fly search <pakage>
```

## Own Pakage install

```bash
fly -ti <pakage>
```

```bash
fly -ts <pakage>
```

### Installation

```bash
apt update && apt upgrade
apt-get install curl
apt-get install git
git clone https://github.com/termuxmirror/fly
chmod +x *
./setup
```

#### License