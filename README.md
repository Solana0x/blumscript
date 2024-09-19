# Get BULM Multi Account 100% Uptime FREE NODE.js Bot

This Node.js Bot script manages Multi Account for Blum bot, Unlimited Account Support and multiple blum Accounts handling DAILY CLAIM, DAILY GAMES, DAILY TASKS. The script also includes functionality to periodically send Claim BLUM tokens. If you can run your pc 24/7 then you dont need a Vps else Better buy a small VPS!! Bot can handle Thousands of BLUM Accounts AT ONCE !

**Register here Blum** - [https://t.me/blum/app?startapp=ref_4P0iHV9xlf](https://t.me/blum/app?startapp=ref_4P0iHV9xlf)

# Dont miss Blum its invested by Binance Labs ! Season VII ! ![image](https://github.com/user-attachments/assets/8ad531fd-d417-40e0-9c74-66b91da03a02)


# Get Query_id by ->

1. Go to telegram desktop Settings then Advance > experimental settings.
2. ![image](https://github.com/user-attachments/assets/f2251f9a-be84-4db7-b568-7bc164bc3f78)
3. Then Turn on `enable web inspecting`
4. ![image](https://github.com/user-attachments/assets/9bc59cbc-0fd4-4cf8-ac70-1f6547edc366)
5. Done ! Login to Blum Bot and inspect to get the Query ID (right click to Inspect)
6. ![image](https://github.com/user-attachments/assets/c27bccac-b8bd-43fd-a3dd-7727be662abe)


# Setps to follow !

1. clone the repo - `git clone https://github.com/Solana0x/blumscript`
2. Then `cd blumscript`
3. Then `npm install`
4. Get `query_id=` from Telegram desktop by right click on your bot and then inspect
5. The Go to console and write `allow pasting` first then write `sessionStorage.getItem('query_id');`
6. Then you will see output as `'query_id=AAENbsx1uxHCS49780&hash=7a153fc0cfd3e78056x3bfdd346d783036'` copy the queryid
7. Add `query_id=` in data.txt file every line = new `query_id=`
8. Repeat the process for all the Telegram accounts
9. One done Run the Bot code by - `node blum.js`
10. If You wanted to USE proxys to be safe from Sybil ! then use `node blum-proxy.js` and add your proxis in the `proxy.txt` file !! 
11. Bot have 2 Ways 1. if you do yes (y) then it will complete the tasks also like Coinmarketcap, binance etc all tasks in app
   2. if you do no (n) then it will skip the task and just play game and daily checkin etc stuff.
11. So, Use yes(y) may be first time then afterwards for daily usage use (n) !!


```  async randomDelay() {
    const delay = Math.floor(Math.random() * (5000 - 3000 + 1)) + 3000;
    return new Promise(resolve => setTimeout(resolve, delay));
  }
```

# IF you wanted to add your Custom Random Delay than You can changed `3000` this to 0 ! 3000 means => 3 seconds delay in btw Tasks !

# Features of the BOT

1. AUTO FARMING BOT
2. AUTO DAILY CHECKIN 
3. AUTO 7 hrs CHECKIN
4. AUTO PLAY THE GAME 
5. AUTO JOIN THE TRIBE
6. AUTO COMPLETE THE TASKS

# Buy proxy !

1. As per my suggestion you can buy residentail or datacenter proxy as per your budget from this website [https://dataimpulse.com/?aff=23392](https://dataimpulse.com/?aff=23392) .

![image](https://github.com/user-attachments/assets/95248b67-4d6b-44f2-a2a7-950c71a3be5e)


# FOR ANY KIND OF HELP CONTACT : 0xphatom on Discord https://discord.com/users/979641024215416842

# Disclaimer and Warning

**Educational Purposes Only:**

This script is intended solely for educational and research purposes. The authors and contributors of this project are not responsible for any misuse of this code. Any actions taken using this code are the sole responsibility of the user.

- **Non-Liability**: The authors of this code do not bear any responsibility for legal or ethical violations that occur due to the use of this script. The script should only be used in a controlled, legal environment, and not for any illegal activities. Misuse of this software may result in legal actions taken against the user by third parties.
- 
- **Third-Party Liability**: The author is not responsible for any actions taken by any organization, including but not limited to the Blum team, or any other entities that may use or interpret this code in any manner.

**Copyright Notice:**

This script is protected under the provisions of the **U.S. Copyright Act of 1976**, Title 17, United States Code. Unauthorized reproduction or distribution of this script, or any portion of it, may result in severe civil and criminal penalties, and will be prosecuted to the maximum extent possible under the law.
For more information, please consult the full text of the law: [Title 17 of the U.S. Code](https://www.copyright.gov/title17/).
