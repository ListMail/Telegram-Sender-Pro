Telegram Sender Pro - Setup and Usage Guide

Welcome! This guide will help you get the necessary data from Telegram (API ID and API Hash) and connect your accounts to the Telegram Sender Pro app in just a few minutes.


The tool is in the "Telegram Sender Pro" folder.


Part 1: How to get your API ID and API Hash

For the software to connect to Telegram using your account, you need two unique developer keys. The process is 100% free and official.

Follow these steps:



Go to the official Telegram developer website: https://my.telegram.org/

Enter the phone number of the account you want to use (including the country code, e.g., +1... or +44...) and click Next.

You will receive a confirmation code directly in your Telegram app (on your phone or PC). Enter that code on the website and click Sign In.

From the main menu, click on "API development tools".

A form will appear that you need to fill out to create an "Application".

What settings to fill in the form:

It doesn't matter much what you write here, but it's recommended to make it look natural. Here is a safe example:



App title: Choose any name (e.g., MyMarketingTool, SenderApp2024, TelegramManager).

Short name: A short name, no spaces, using letters and numbers (e.g., mymarketing24, sendappxyz).

URL: Leave blank.

Platform: Choose Desktop or Windows.

Description: Leave blank or write a short sentence (e.g., "Personal account manager tool").

Click the blue "Create application" button.

On the next page, you will see the App api_id (a string of numbers) and the App api_hash (a long string of letters and numbers).



⚠️ IMPORTANT: Save these two codes in a Notepad file or keep the page open. Do not share this API Hash with anyone!

(Pro Tip: If you get a red error when clicking "Create application", turn off any VPN you might have running, change your internet network (e.g., use mobile data), or add a few more letters to the "App title" and try again. Telegram is sometimes sensitive to IP addresses).



Part 2: How to connect the API to Telegram Sender Pro

Now that you have the data, connecting it to the software is very simple.



Open the Telegram Sender Pro program (the .exe file).

Click the + ADD NEW ACCOUNT button on the left side to create a new row for your account.

In the fields that appeared:

Copy and paste your API ID into the first box (e.g., 1234567).

Copy and paste your API Hash into the second box (e.g., a1b2c3d4e5f6g7...).

Click the Login button.

A pop-up window will ask for your phone number:

Enter the full number (e.g., +1xxxxxxxxx) and click OK.

A second pop-up window will ask for the security code:

Check your Telegram app (you will receive an official message from Telegram with a 5-digit code).

Enter the code into the software and click OK.

(If you have a 2FA/Two-Step Verification password set on your account, a third window will appear asking for the password).

🎉 Done! If the details were correct, the "OFFLINE" status will change to your account's name, written in green (e.g., JOHN DOE), and "Account connected" will appear in the log on the left.



Part 3: Quick Start (Your first message)

You can now add multiple accounts by repeating the steps above. Once logged in, follow these steps to launch your campaign:



Add your messages: Write the message you want to send in the text box under the connected account. If you want to use the Anti-Spam (Rotation) feature, click + Message and add 2-3 different variations of the same ad.

Choose the operating mode:

Rotation: Sends one message at a time (drip-feed).

All Groups: Sends a "blast" to all groups within the account, with short pauses in between.

Set the general pause: From the "Pause:" menu, choose how many minutes you want the software to wait before repeating the sending process.

START: Click the big green START button and relax. The software will do the work for you!

⚙️ Note on Auto-Saving

You don't need to redo the Login process every time! When you close the app, the program generates a local config.json file and a session_[API_ID].session file. Do not delete them! The next time you open the app, your accounts and messages will be pre-loaded and ready to go.
