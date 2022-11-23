### What is TelgramCLI?

Telegram CLI is a microservice for sending messages to a Telegram channel.  Both text messages
with HTML(bold, italics, and underline are supported) and image messages are supported.

### How to use TelegramCLI?

There are the following syntaxes for TelegramCLI:

```telegramcli```

Displays a thorough help message on the various syntaxes and restrictions on messages.

```telegramcli -t "Text Message"```

Sends the "Text Message" to the designated channel from environment variables.

```telegramcli -i \path\to\image```

Sends the image file to the designated channel from environment variables.

### How to Install TelegramCLI?

1.  Download both ```requirements.txt``` and ```telegramcli```.  Folder location doesn't matter for now.

2.  Run ```pip3 install -r requirements.txt``` to install dependencies.

3.  Run ```sudo chmod +x telegramcli``` to make the file executable.

4.  Run ```sudo mv telegramcli usr/local/bin``` to move the file to the executable script directory.

5.  Create a Telegram bot account through the Botfather.

6.  Run ```nano ~/.bashrc``` to open up the bashfile.

7.  Add the following two exports: ```EXPORT TELEGRAM_CHAT_ID="xx"``` and ```EXPORT_TELEGRAM_TOKEN="xx"```.  Look through the Telegram documentation for information on how to get these values.

8.  Try out the code to make sure it works.  Type in ```telegramcli -t "Hello World!"```.

### How to Contact the Author?
Either through here or email me at olindgallet@olingallet.com
