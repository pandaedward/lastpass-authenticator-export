# lastpass-authenticator-export
Forked from `https://github.com/dmaasland/lastpass-authenticator-export`

## Prerequisites
python 3.9
pip 21.3.1

## Steps
1. Install python dependencies `pip3 install -r requirements.txt`
2. Execute the script `python3.9 lastpass-authenticator-export.py -u <LASTPASS_ACCOUNT_NAME> 
3. The script will prompt for password and approve 2FA once authenticated. 
4. If all goes well an `export` folder will be created in current directory, with all the TOTP in QR codes for your export


