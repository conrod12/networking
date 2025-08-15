ORIENTATION
FLOAT-IP.TXT TO DO CTFS 
odie.hettinger / odie.hettinger!
https://cted.cybbh.io/tech-college/cttsb/cctc/net/Net/Modules/01_Network_Access/fg.html#122-describe-lan-topologies-and-devices
wget https://git.cybbh.space/cted/tech-college/cttsb/cctc/net/Net/-/raw/main/Resources/packages_and_scripts/mac_oui_lookup.py -MAC OUI LOOKUP TOOL
wget https://git.cybbh.space/cted/tech-college/cttsb/cctc/net/Net/-/raw/main/Resources/cal.py- SUBNET CALCULATOR.
wget https://git.cybbh.space/cted/tech-college/cttsb/cctc/net/Net/-/raw/main/Resources/frag.py -FRAGMENTATION CALCULATOR.
PROXY CHAINS*
less /etc/p0f/p0f.fp #pof signature database

https://dash.ent1.pcte.mil/


wget https://git.cybbh.space/cted/tech-college/cttsb/cctc/net/Net/-/raw/main/Resources/packages_and_scripts/mac_oui_lookup.py; chmod +x mac_oui_lookup.py #fin mac oui and eui-64


site:*.ccboe.net "administrator" advance google searches

for i in {1..254}; do (ping -c 1 172.16.82.$i | grep "bytes from" &) ; done #use to ping a range.

TCP
nc -nzvw1 172.16.82.106 21-23 80 2>&1 | grep -E 'succ|open'  #vertical scanning, find range of ports with specific ip. 
UDP
nc -nuzvw1 172.16.82.106 1000-2000 2>&1 | grep -E 'succ|open'
TCP
for i in {1..254}; do nc -nvzw1 172.16.82.$i 20-23 80 2>&1 & done | grep -E 'succ|open' #Horizontal scanning
UDP
for i in {1..254}; do nc -nuvzw1 172.16.82.$i 1000-2000 2>&1 & done

FILE SEARCH
find / -name hint* 2> /dev/null #DEV/NULL SEND ALLL THE ERROR MESSAGES TO DEV/NULL
find / -iname flag* 2> /dev/null








