# fleeknetwork
Fleek Network is a decentralized content delivery network. 

They raised $25M various crypto VCs.

They are currently in the Devnet phase, and once they pass the Testnet phase, they will launch an incentivized node testnet. Today, we are going to run a node on Devnet

![image](https://user-images.githubusercontent.com/98783018/228665555-11f6868e-e987-4973-a7b3-fd17bf31e0d1.png)

**Min system requirement**

_4CPU - 8GB RAM - 150GB SS_

Let's start with Root

```
sudo su
cd $HOME
```

Update the server.

```
sudo apt update && sudo apt upgrade -y
```

Install a screen

```
sudo apt install screen -y
```

Necessary libraries 

```
sudo apt-get install build-essential -y
```

```
sudo apt-get install cmake clang pkg-config libssl-dev -y
```

```
sudo apt-get install cmake clang pkg-config libssl-dev -y
```

```
sudo apt-get install protobuf-compiler -y
```

```
sudo apt install git -y
```

Create a Screen

```
screen -S fleek
```

Upload rust

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

![image](https://user-images.githubusercontent.com/98783018/228670986-c41cb581-8760-4250-aebb-49bb3ee29a29.png)

```
source "$HOME/.cargo/env"
```

Upload Sccache

```
cargo install sccache
```

Clone the project to the server

```
git clone https://github.com/fleek-network/ursa.git
cd ursa
```

It has to be long after this code (be patience)

```
make install
```

To see the logs

```
ursa
```

![image](https://user-images.githubusercontent.com/98783018/228671763-384cecf0-6ae7-4ec2-bcb8-80d36e85051a.png)

If you need to help come our [telegram](https://t.me/LossNodeChat) and [discord](https://discord.gg/MGZDjdBx3X) channel. We'll be ready to help you❣️

![image](https://user-images.githubusercontent.com/98783018/228673744-30da4320-8a6c-4ee1-a282-bd016f9a7685.png)

-[Fleek discord](https://discord.gg/fleekxyz)

