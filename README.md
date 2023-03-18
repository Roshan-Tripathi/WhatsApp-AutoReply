# WhatsApp AuotoReply

Usually, my friends WhatsApp me late at night regarding some work thinking that I'm awake and will reply before morning. 
Thus, I made this WhatsApp bot using selenium in Python which automatically responds to your friend's text (if they send one) that you're sleeping and thus won't be able to reply before morning!
Also, when you wake up, you'll know who texted you!

## Requirements
1. Python 3.x with selenium installed
2. Chrome Driver

**Install Python from here:** https://www.python.org/downloads/

**Install Selenium Using command:** pip3 install selenium

**Install Chrome Driver:**
1. Go to settings > About Google Chrome to check the version of Chrome Driver.
<img width="706" alt="Screenshot 2023-03-18 at 12 27 31 PM" src="https://user-images.githubusercontent.com/128136329/226090533-3d74328f-ed1c-4a52-8d34-7bfe7104de14.png">

2. Click on https://chromedriver.chromium.org/downloads and download the desired driver.

## How to use the bot?

1. Run the code.
2. The code will automatically open Whatsapp Web in Chrome where you're supposed to scan the QR code.
<img width="1440" alt="Screenshot 2023-03-18 at 12 30 22 PM" src="https://user-images.githubusercontent.com/128136329/226090621-42508193-baa4-4ed2-a8d9-081107009def.png">
3. Sleep Well! :)

## Working of the bot

<img width="988" alt="Screenshot 2023-03-18 at 12 15 40 PM" src="https://user-images.githubusercontent.com/128136329/226090279-b88985b9-628b-4753-9083-e2e1afc00a95.png">
After every 1 minutes, the bot checks for every person you've specified in the closefriends list, that if there is any unread text from their side or not. 
If you've received one, then it replies with the message specified.
Else does nothing.

## Limitations(Future Scope)
1. This is a bot for website verison of Whatsapp(Whatsapp Web) only, however we can extend it to the Desktop Application version too.
2. The QR code needs to be scanned manually every time you run the code.
3. Security concern is there as one is supposed to keep the Whatsapp Web open the whole night, however you can run the code and put the laptop on sleep mode the code will still run.
