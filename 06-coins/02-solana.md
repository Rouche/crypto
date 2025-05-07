## Live Linux Mint CD

### Solana CLI
https://solana.com/docs/intro/installation


## 1. Change sources for apt
```
sudo nano /etc/apt/sources.list
```
* Change content for:
```
deb http://packages.linuxmint.com vera main upstream import backport #id:linuxmint_main
deb http://archive.ubuntu.com/ubuntu/ jammy main restricted universe multiverse
deb http://archive.ubuntu.com/ubuntu/ jammy-updates main restricted universe multiverse
deb http://archive.ubuntu.com/ubuntu/ jammy-security main restricted universe multiverse
```

## 2. Install KeePassXC
```
sudo add-apt-repository ppa:phoerious/keepassxc
sudo apt update
sudo apt install keepassxc
```

## 3. Solana CLI
```
curl --proto '=https' --tlsv1.2 -sSfL https://solana-install.solana.workers.dev | bash
```

## 4. Solana Wallet:
```
cd ~/.local/share/solana/install/active_release/bin
./solana new
```