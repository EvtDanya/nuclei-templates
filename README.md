# Nuclei templates
## How to use

with subdomains discovery
```bash
subfinder -d http://target.com -all -silent | nuclei -t nuclei-templates/ -c 30 -rl 50
```

simple use


```bash
nuclei -l targets.txt -t nuclei-templates/ -c 30 -rl 50
```
