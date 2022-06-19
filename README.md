# Proxyless Twitch Username Checker With Webhook

Loops through a list of usernames to check if they are available or unavailable and sends the available usernames to a webhook.

![image](https://user-images.githubusercontent.com/80773857/174497428-e893879b-c7a5-451c-856b-7ac3d1efd3c0.png)

# Usage

1. Download the content.
2. Install requirements.txt by typing pip install -r requirements.txt in Command Prompt.
3. Enter your choice of usernames inside of the usernames.txt file, or generate them using the generator.py script.
4. Create your own webhook and change it in the checker.py file located on line 64.
5. Run the checker.py file and enter the amount of threads you would like.

All available usernames will be outputted to Available.txt file.

# Please Note

This script only allows you to use a maximum of 5 threads to prevent ratelimits to keep this script proxyless, I am not responsible for your actions using this script. 

This script was made for educational purposes.
