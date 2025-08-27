<div align="left">

#   **PIPE-CLI📔**

A powerful command-line interface for interacting with the Pipe distributed storage network.

</div>

---

# Pre-Requirements 🛠

## Install All Require Dependencies


```
sudo apt update && sudo apt install -y \
  build-essential \
  pkg-config \
  libssl-dev \
  git \
  curl
```


## Install rustup

* For {Linux}

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
```

# Installation

### Clone the Repo


```
git clone https://github.com/PipeNetwork/pipe.git
cd pipe
```

### Install pipe-cli globally on your system

```
cargo install --path .
```
---

# Quick Start
## Basic Usage

### Create New User

```
pipe new-user <your_username>
```

>Save your `Solana Pubkey:` 

### Save Your Profile Data

>Save the Profile data :

```
cat ~/.pipe-cli.json
```

#### Activate your PIPE Account:

```
pipe referral apply ONEEYEKI-H2A2
```

### Swap Sol (Devnet) to Pipe

* Get 5 Sol Devnet Faucet from [here](https://faucet.solana.com/)

* Complete your First Swap

```
pipe  swap-sol-for-pipe 1
```

>Swap minimum 1sol to pipe

### Upload a File

```
pipe upload-file <FILE_PATH> <FILE_NAME>
```
>Upload any image or video (DON'T UPLOAD ANY PRIVATE / CONFIDENTIAL INFORMATION)

>Replace <FILE_PATH> & <FILE_NAME> with their actual path and name.


### Create Public Link

```
pipe create-public-link <FILE_NAME>
```


### Check Token-Usage

>You can check your Token usage using this below command, uploading files burn Pipe tokens.
```
pipe token-usage
```

---

### Create Your Referral Code

```
pipe referral generate
```
>Earn up to 100 PIPE for every successful referral.


#### Check your referral stats

```
pipe referral show
```

---


# Get 🔥Firestarter Role


### [Join the Pipe Dc](https://discord.gg/f5Kn8kZka4)

## Role Requirement👇

<img width="1875" height="330" alt="image" src="https://github.com/user-attachments/assets/4e0d0e20-5e3a-42b3-9982-ebeede20a025" />


### Upload Your File from: [Upload a File](#upload-a-file)

### Get public link of your upload files from: [Create Public Link](#create-public-link)


>Join Discord and post in [Pipe-Community-Social](https://discord.com/channels/1276592413049356391/1392272776278184079) to get your Firestarter Role.

---

