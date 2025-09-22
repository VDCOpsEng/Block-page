# DNSFilter Block Page (VDCOpsEng)

This repository hosts the branded DNSFilter **302 redirect block page** for Vantage Data Centers.

## Features
- Displays blocked **domain name**
- Shows the matched **category/categories**
- Displays the **username** (instead of source IP)
- Includes company branding and custom layout

## GitHub Pages URL
Deployed at:  
👉 https://vdcoopseng.github.io/Block-page/

## How It Works
When a user visits a site blocked by DNSFilter, the policy redirects them (HTTP 302) to this page.  
The page extracts details from the redirect URL (domain, categories, username) and displays them dynamically.

## Example Redirect
https://vdcoopseng.github.io/Block-page/#domain=bittorrent.com&categories=P2P,Hacking&user=jdoe

## Repository Contents
- `index.html` – Main block page HTML & JavaScript
- `vantage_logo_small.png` – Company logo

## Contributing
Updates and improvements should be submitted via pull requests.  
For issues, open a GitHub issue in this repo.

## Maintainers
VDCOpsEng Cybersecurity Team
