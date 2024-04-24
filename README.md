# Contributing-to-the-Ceremony---Risc-Zero-
<img src="https://pbs.twimg.com/media/GLjQzeyaYAAWcQw?format=png&name=small" width="1200" height="400" alt="RISC Zero Image">


# RISC Zero Contribution Guide

Welcome to the RISC Zero contribution guide. Here you'll find the requirements and steps to contribute to the RISC Zero project using your GitHub account.

## 🖥 Hardware Requirements

To participate, make sure your system meets the following requirements:
- **Memory**: 8GB or more RAM
- **Bandwidth**: At least 25 Mbps for both Download and Upload

For more details, visit the [RISC Zero website](https://www.risczero.com/).

## 🦑 GitHub Account Requirements

Before you start, ensure your GitHub account meets these criteria:
- At least **1 public repository**
- Following **at least 5 GitHub accounts**
- At least **1 follower**

## ✅ Contribution Steps

### Install Dependencies and Binary

Open your terminal and run the following commands:

```shell
curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | sh -
source ~/.profile
mkdir p0tion-tmp
cd p0tion-tmp
nvm install 16.20
nvm use 16.20
npm install @p0tion/phase2cli
```

Authenticate GitHub Account
Authenticate your GitHub account by running:
```shell
npx phase2cli auth
```

Contribute
Since the contribution process is interactive, we will use screen:
```shell
screen -RS risczero
```
```shell
npx phase2cli contribute
```

Follow the instructions until you see a message about the waiting time for contributors. You can detach the screen by pressing CTRL+A then CTRL+D without releasing the CTRL button.

To check your progress later, use:
```shell
screen -r risczero
```


### 🖥 High Spec Cheap VPS Rentals

Click here to rent: [High Spec Cheap VPS (from €4.50/month)](https://example.com/your-vps-link)

### 📖 Details and Tutorials

- For more details: [Ceremony Contribution Public Instructions](https://www.risczero.com/blog/ceremony-contribution-public-instructions)
- Step-by-step tutorial: [VPS Setup Tutorial](https://p0tion.super.site/ce8f7047468b41239dc512919644535c)















