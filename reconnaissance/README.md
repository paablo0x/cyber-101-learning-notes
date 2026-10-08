# Reconnaissance and Enumeration

Reconnaissance is used to gather information about a target before moving further into an assessment.

## Topics

- Host discovery
- Port scanning
- Service enumeration
- Version detection
- Attack surface
- Basic reconnaissance

## Tools

- Nmap
- Gobuster

## Example Nmap commands

```bash
nmap <target>
nmap -sV <target>
nmap -sC <target>
nmap -p- <target>
```

The important part is not just finding an open port. The goal is to understand what is running behind it.
