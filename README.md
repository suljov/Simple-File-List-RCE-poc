# Simple-File-List-RCE-poc

* A poc for the WordPress Plugin Simple File List 4.2.2 - Arbitrary File Upload  exploit
* Simple File List < 4.2.3 - Unauthenticated Arbitrary File Upload RCE
---
Poc taken from:
https://www.exploit-db.com/exploits/48979 and made into a bash script
* script uploads a jpg file called 'pwn.jpg' which is just a php webshell called [p0wny-shell](https://github.com/flozz/p0wny-shell)


# Usage

```
$ ./exploit.sh --help                        

Usage: ./exploit.sh <target_url> <file_name>

Example: ./exploit.sh http://acme.org pwn.jpg
```
