# SubdomainFinder

SubdomainFinder is a tool for collecting subdomains. It increases the range of information gathering during the penetration test.

The reason for writing this tool is that my computer can't use Sublist3r, I don't want to spend time configuring the environment for it.


## Introduction


- Python Version: 3.7
- Dependencies: `pip3 install -r requirements.txt`
- Channels for collecting subdomains：

	`crt, dnsdumpster, threatcrowd, virustotal, natcraft, google transparencyreport, ask, baidu, bing, so, google`


## API

- https://www.virustotal.com/

## Usage

`usage: SubdomainFinder.py [-h] -d DOMAIN [-o] [-html]`

| Short Form | Long Form | Description |
| :-- | :-- | :-- |
| -h | --help | show this help message and exit |
| -d | --domain | Domain name to enumerate subdomains of |
| -o | --output | Output file name ,the domain name is thefile_name.txt |
| -html | --html | Output html, the domain name is the file_name.html |



s