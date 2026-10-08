# Security Toolkit

A small browser-based tool for learning basic cyber hygiene. Everything runs client-side in plain HTML, CSS and JavaScript: nothing you type is sent to a server.

https://dilshodusmonjonov73-source.github.io/security-toolkit/ 

## Features

- **Password strength checker**: estimates entropy from length and character variety, penalises common passwords, repeated characters, simple sequences and "word + number" patterns, and shows an estimated brute-force time.
- **Phishing URL checker**: parses a link and scores red flags such as non-HTTPS, IP-address hosts, `@` in the URL, punycode domains, too many subdomains, URL shorteners, risky TLDs, phishing keywords and brand look-alike domains (e.g. `paypa1-login.example.com`).

## Tech

HTML5, CSS3 (custom properties, light/dark mode), vanilla JavaScript, GitHub Pages. No dependencies.

## Limitations

This is an educational heuristic tool. A "low risk" result does not prove a link is safe, and the entropy estimate is approximate. For real accounts, use a password manager and multi-factor authentication.

## Run locally

Open `index.html` in a browser.