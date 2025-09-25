# SpiderFoot-venv
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
##  Start after installation
```bash

source .SpiderFoot/bin/activate
```
