<span class="badge-paypal"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=F5UAFVHBPQWXQ" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-bitcoin"><a href="http://btcchip.in/11fe" title="Donate once-off to this project using Bitcoin"><img src="https://img.shields.io/badge/bitcoin-donate-yellow.svg" alt="Bitcoin donate button" /></a></span>


# MyIP
Pyton script that get's you public IP and saves it into Pastebin, in casa your DDNS fails

Install:

1. pip install Pastebin

2. Go to http://pastebin.com/api and get you api key

3. Edit myip.py and insert your api key, pastebin username and password

4. Run 'python MyIP.py'

5. Optional: make it run at boot, as explained here http://www.instructables.com/id/Raspberry-Pi-Launch-Python-script-on-startup/


The script will run every 90 minutes, deleting the previous paste and creating a new one, containing the current timestamp
and your public (Internet) IP
