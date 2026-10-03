
# Stage 2: Initial Server Setup

## System info
- OS: Ubuntu 26.04.1 LTS, kernel 7.0.0-38-generic
- Platform: VirtualBox (x86-64)

## Commands used
- `sudo apt update && sudo apt upgrade -y`: refresh and upgrade packages
- `hostnamectl`, `df -h`, `free -h`, `uptime`: inspect the system
- `timedatectl set-timezone Asia/Tbilisi`: set timezone

## Observations
- Ubuntu 26.04 ships `coreutils-from-uutils` (Rust rewrite of coreutils)
  as the provider of `df` and other core commands.
