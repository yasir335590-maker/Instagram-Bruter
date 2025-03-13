# Instagram Bruter

## Description
Instagram Bruter is a password brute-force tool designed to test the security of Instagram accounts. It automates login attempts using a list of passwords and proxies.

## Author
Pralin Khaira

## Features
- Multi-threaded brute-force attack
- Proxy support for anonymity
- Session resume functionality
- Password list-based attack
- Proxy pruning and statistics tracking

## Requirements
- Python 3.x
- Required libraries (install with `pip install -r requirements.txt`)

## Usage
```sh
python instagram.py -u <username> -p <password_list.txt> -px <proxy_list.txt> -m <mode>
```
### Options:
- `-u, --username` : Target Instagram username or email
- `-p, --passlist` : Path to password list file
- `-px, --proxylist` : Path to proxy list file
- `-m, --mode` : Attack mode (0 to 3, where 0 = 32 bots, 3 = 4 bots)
- `--prune` : Prune the proxy database (value between 0 and 1)
- `--stats` : Show proxy statistics
- `-nc, --no-color` : Disable color output

## Example
```sh
python instagram.py -u target_user -p passwords.txt -px proxies.txt -m 2
```

## Disclaimer
This tool is for educational purposes only. Unauthorized use against accounts you do not own is illegal.
