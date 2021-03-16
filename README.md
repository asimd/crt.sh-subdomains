## CRT.sh Subdomains
A script to quickly obtain subdomains of any domain. This script uses response from https://crt.sh to obtain the subdomains.

### Example usage
```bash crt.sh github.com```

The command above will find all subdomains of Github.com domain and put them to Github-subdomains.txt file

The output from this script can be used neatly with [HTTProbe](https://github.com/tomnomnom/httprobe) from [Tomnomnom](https://github.com/tomnomnom) to see what domains are returning any response from both HTTP and HTTPS 

```cat github-subdomains.txt | httprobe >> github-alive-subdomains.txt```
