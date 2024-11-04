# 1win bot


[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cucumber_scripts)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cucumber-pickle/Cucumber)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@cucumber_scripts)

## Registrations [http://t.me/token1win_bot/](http://t.me/token1win_bot/start?startapp=refId726837621)


## Features

- **Multi-account Support:** Automate actions across multiple accounts. 
- **Auto Complete Task** Automatically perform available quest
- **Configurable Settings:** Control various aspects of the script via a `HPV_Config.py` file.
- **Using a proxy**
- **Static user agent**

## Installation

**Clone the repository:**

   ```bash
   git clone https://github.com/cucumber-pickle/1winCum.git
   cd 1winCum
````

**Run bot**
   ```bash
   python bot.py
   ```


## About Proxy


You can add your proxy list in `HPV_Proxy.txt` and proxy format is like example below :

Format :

```
host:port:login:password
```

Example :

```
24.62.187.78:8382:IodsanxJ:Qwer123
201.60.154.211:6286:IodsanxJ:Qwer123
```

## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):

```javascript
copy(Telegram.WebApp.initData)
```

6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `HPV_Account.json` file, like this:

```json
{
  "Account_1": "user=%xxxxxx....",
  "Account2": "query_id=AA...."
}
```


## This bot helpfull?  Please support me by buying me a coffee: 

``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - BSC (BEP 20)

``` UQBiNbT2cqf5gLwjvfstTYvsScNj-nJZlN2NSmZ97rTcvKz0 ``` - TON

``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - Optimism

``` THaLf1cdEoaA73Kk5yiKmcRwUTuouXjM17 ``` - TRX (TRC 20)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions or support, please contact [CUCUMBER TG CHAT](https://t.me/cucumber_scripts_chat)
