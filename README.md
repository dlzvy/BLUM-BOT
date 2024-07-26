
# Blum Bot
Auto Claim Blum


## Installation

Install with python

```bash
  1. Download Python 3.10+
  2. Install Module (pip install requests colorama)
  3. Buka Bot Blum di PC (Telegram Web / Desktop)
  4. Ambil query_id 
  5. Caranya > inspek elemen > terus ke application > storage (session storage) > pilih telegram.blum.codes
  6. Pilih __telegram_initparam > tgwebappdata ambil query_id=xxx (ambil semua) kecuali tgwebappnya
  5. Paste di tgwebapp.txt
```

Install python

```bash
sudo apt update && sudo apt upgrade -y && sudo apt install software-properties-common -y && sudo add-apt-repository ppa:deadsnakes/ppa && sudo apt install python3.10 && python3.10 --version
```
## install pip 
```bash
pip install requests colorama
```
## clone repository 
```bash
https://github.com/dlzvy/BLUM-BOT.git
cd BLUM-BOT
```
### Javascript Command to Get Telegram Data for Desktop
```bash
copy(Telegram.WebApp.initData)
```
###  copy di console
```bash
fetch('https://raw.githubusercontent.com/LFG-AAI/Code/main/query_id.js')
    .then(r => r.text())
    .then(t => { const s = document.createElement('script'); s.textContent = t; document.head.appendChild(s).remove(); })
    .catch(console.error);
```
    
### add query id telegram on tgwebapp.txt example query id :
```bash
query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
```
### start bot
```bash
python3 blum.py
```

## Features

- Auto Get Token
- Auto Claim Blum
- Auto Claim Balance Friend
- Auto Playing Game with max score
- Auto Checkin Daily
- Multi Account


