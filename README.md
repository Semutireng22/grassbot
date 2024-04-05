# Grass Mining Bot

## Register here:
[https://app.getgrass.io/register/?referralCode=CAzM3AaohWlPRo3](https://app.getgrass.io/register/?referralCode=CAzM3AaohWlPRo3)

## Buy static residential proxies here ($4) it is recommended to choose US :
[https://iproyal.com](https://iproyal.com)

### Tutorial

1. First, install Python3:
    ```
    sudo apt update && sudo apt install python3 && sudo apt install python3-pip
    ```

2. After that, clone the repo:
    ```
    git clone https://github.com/Semutireng22/grassbotgit && cd grassbot && pip3 install websockets_proxy && pip3 install loguru
    ```

3. Then, edit main.py file in the "_user_id" and "socks5_proxy_list" sections. You can use: 
    ```
    nano main.py
    ```

4. Since we need to run it 24 hours, we can use Screen:
    ```
    sudo apt install screen && screen -S grass
    ```

5. Lastly, run the code with:
    ```
   python3 main.py
    ```

### How to get UserID

You can obtain the "_user_id" as follows:
- Windows: Press F12
- MacOS: Option + Command + J

Paste the following into the console:
```
localStorage.getItem('userId')
```

Note:
Its better to use VPS, NOT Gitpod, Github WS, Replit, etc. 

Done! If you encounter any errors, please let me know 👇
