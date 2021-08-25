# IPGeolocation
**=============================================**
A tool to retrieve IP Geolocation information
Powered by ip-api
## Requirements
- Python 3.x<br>
- termcolor<br>
- colorama
## Download/Installation
> `$git clone https://github.com/maldevel/IPGeoLocation`<br>
> `$pip3 install -r requirements.txt --user`<br>
### if pip3 is missing:
>`$apt-get install python3-setuptools `<br>
>`$easy_install3 pip`<br>
>`$pip3 install -r requirements.txt`<br>
## Features
- Retrieve IP or Domain Geolocation.
- Retrieve your own IP Geolocation.
- Retrieve Geolocation for IPs or Domains loaded from file. Each target in new line.
- Define your own custom User Agent string.
- Select random User-Agent strings from file. Each User Agent string in new line.
- Proxy support.
- Select random proxy from file. Each proxy URL in new line.
- Open IP geolocation in Google Maps using the default browser.
- Export results to csv, xml and txt format.
## Geolocation Information
- ASN
- City
- Country
- Country Code
- ISP
- Latitude
- Longtitude
- Organization
- Region Code
- Region Name
- Timezone
- Zip Code
# Usage
`$ ./ip2geolocation.py
usage: ipgeolocation.py [-h] [-m] [-t TARGET] [-T file] [-u User-Agent]
                        [-U file] [-g] [--noprint] [-v] [--nolog] [-x PROXY]
                        [-X file] [-e file] [-ec file] [-ex file]

IPGeolocation 2.0.4

--[ Retrieve IP Geolocation information from ip-api.com
--[ Copyright (c) 2015-2016 maldevel (@maldevel)
--[ ip-api.com service will automatically ban any IP addresses doing over 150 requests per minute.

optional arguments:
  -h, --help            show this help message and exit
  -m, --my-ip           Get Geolocation info for my IP address.
  -t TARGET, --target TARGET
                        IP Address or Domain to be analyzed.
  -T file, --tlist file
                        A list of IPs/Domains targets, each target in new line.
  -u User-Agent, --user-agent User-Agent
                        Set the User-Agent request header (default: IP2GeoLocation 2.0.3).
  -U file, --ulist file
                        A list of User-Agent strings, each string in new line.
  -g                    Open IP location in Google maps with default browser.
  --noprint             IPGeolocation will print IP Geolocation info to terminal. It is possible to tell IPGeolocation n
ot to print results to terminal with this option.
  -v, --verbose         Enable verbose output.
  --nolog               IPGeolocation will save a .log file. It is possible to tell IPGeolocation not to save those log
files with this option.
  -x PROXY, --proxy PROXY
                        Setup proxy server (example: http://127.0.0.1:8080)
  -X file, --xlist file
                        A list of proxies, each proxy url in new line.
  -e file, --txt file   Export results.
  -ec file, --csv file  Export results in CSV format.
  -ex file, --xml file  Export results in XML format.`
  
