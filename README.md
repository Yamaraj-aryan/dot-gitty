# DotGitty
An extension for checking if .git is exposed in domains in a file or in a single URL

Scans using both http and https

usage: python dotgitty.py [-h] [-v] [-u SINGLE_DOMAIN] [file_path]

positional arguments:
  file_path          Path to the file containing domain names

optional arguments:
 *  -h, --help            show this help message and exit 
 *  -v, --verbose         Enable verbose mode 
 *  -u SINGLE_DOMAIN, --single_domain SINGLE_DOMAIN 

## For Single url 
python script.py -u example.com 

## For list of Urls
python script.py ~/root/domains.txt -v 

Made For Educational Purpose Only. Use at your own risk.

## Make sure you use the -v command or else you will see an empty terminal!!!
