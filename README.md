# SpiderFoot-venv

## License

This project is released under the MIT License.  
The software is provided “AS IS”, without warranties of any kind.

If you reuse code, ideas, or modules inspired by **SpiderFoot** (https://github.com/smicallef/spiderfoot), please note that SpiderFoot is also licensed under MIT. Your use here does not imply any affiliation or endorsement.

---

## Attribution & No Affiliation

This project is not affiliated with, sponsored by, or endorsed by **SpiderFoot**, **SpiderFoot HX**, or spiderfoot.net.  
All product names, logos, and brands are property of their respective owners and are used for identification purposes only.

---

## Third-Party Components (NOTICE)

This project may depend on or interface with third-party libraries and tools that have their own licenses. These do **not** change this project’s MIT license, but their terms still apply to those components.

Examples (update this list to match your actual dependencies):

- `requests` — Apache-2.0  
- `beautifulsoup4` — MIT  
- `dnspython` — ISC  
- `phonenumbers` — Apache-2.0  
- `networkx` — BSD-3-Clause

---

## External Services & Terms of Use

Some features may query external services/APIs (e.g., Shodan, Have I Been Pwned, Censys, etc.).  
Using those features means **you** must comply with each provider’s Terms of Service, rate limits, and legal restrictions. Provide your own API keys where required.

---

## Security Policy

Please report vulnerabilities privately.  
Avoid publishing PoC details that contain sensitive or personal data. We will acknowledge reports and work on a fix promptly.

---

## Privacy

This project is intended for lawful use. Do not include or publish sensitive personal data.  

---

## Trademarks

All trademarks and service marks are the property of their respective owners.  
Their use here is solely for descriptive purposes and does not imply endorsement.

---

## Credits

- Inspired by research/tools in the OSINT community, including **SpiderFoot** (MIT).  


## Quick Start
```bash 
sudo apt update
sudo apt install -y python3 python3-pip python3-venv
sudo apt install -y build-essential python3-dev libffi-dev libssl-dev


mkdir -p ~/projekty/SpiderFoot && cd ~/projekty/SpiderFoot
python3 -m venv .SpiderFoot   
source .SpiderFoot/bin/activate

wget https://github.com/smicallef/spiderfoot/archive/v4.0.tar.gz
tar zxvf v4.0.tar.gz
cd spiderfoot-4.0

pip install cherrypy
pip install cherrypy_cors
pip install cryptography 

python -m pip install --upgrade pip
pip install "dnspython>=2.6,<3"


pip install netaddr  
pip install phonenumbers  
python -m pip install --upgrade pip
pip install pyOpenSSL cryptography

pip install requests   
pip install bs4  
pip install publicsuffixlist 
pip install networkx   

python -m pip install --upgrade pip
pip install "PyYAML>=6,<7"
pip install mako   
pip install openpyxl   
pip install secure 
python -m pip install --upgrade pip
pip install "ipwhois>=1.2,<2" "python-whois>=0.8,<1"
pip install "adblockparser>=0.7,<1"
python -m pip install --upgrade pip
pip install "PyPDF2>=3,<4"
pip install "python-docx>=0.8.11,<1"
pip install "exifread>=3,<4"
pip install Pillow lxml
python3 -m pip install "python-pptx>=0.6,<1" Pillow lxml

python3 -m pip uninstall -y secure
python3 -m pip install "secure==0.3.0"
python3 ./sf.py -l 127.0.0.1:5001
```
Open your browser and go to 127.0.0.1:5001

##  Start after installation - after restarting system
```bash
cd projekty/SpiderFoot
source .SpiderFoot/bin/activate
cd spiderfoot-4.0/
python3 ./sf.py -l 127.0.0.1:5001
```
Open your browser and go to 127.0.0.1:5001

##  Close venv after use SpiderFoot
```bash
deactivate
```

