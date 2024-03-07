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
cd fly
chmod +x *
./setup
```

#### License

MIT License

Copyright (c) 2024 Krefting Developer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.