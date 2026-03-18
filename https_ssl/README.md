# alu-webstack

## HTTPS & Subdomain Project

This project contains:

- Bash script `0-world_wide_web` that displays DNS record information for subdomains.
- Subdomains used (via `/etc/hosts` for testing):
  - `www.testproject.local` → 44.212.25.228
  - `lb-01.testproject.local` → 44.212.25.228
  - `web-01.testproject.local` → 34.203.218.185
  - `web-02.testproject.local` → 44.202.164.145

## Usage

```bash
./https_ssl/0-world_wide_web testproject.local
./https_ssl/0-world_wide_web testproject.local web-02
