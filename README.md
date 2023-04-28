# Telegram_bot_with_chatgpt
```
Hey, This is a Telegram bot powered by ChatGPT. It is made using a echo bot which echoes the responses of chatGPT in Telegram chat.
```
# Getting started
Activating Environment
```
bash init_setup.sh
```
Alternative
```
pip install -r requirements.txt
```
# Getting Telegram Bot Token-
```
1. Open Telegram app
2. Search for BotFather(with a verified mark)
3. Put /newbot command
4. Once Bot is created, It'll give you a TOKEN save it for future usage.
```
# Getting OpenAi API Key-
```
1. Goto https://platform.openai.com/account/api-keys
2. Click on "Create new secret key"
3. Save API Key somewhere safe for future usage.
```
# .env file
```
Create a .env file and put your bot token and OpenAi token as following-

TOKEN= "YOUR_BOT_TOKEN"
OPENAI_API_KEY= "YOUR_OPENAI_API_KEY"

```
# Echo bot reference-
```
https://docs.aiogram.dev/en/latest/quick_start.html#summary
```
# Features
```
1. It gives you answer of your query by using ChatGPT's response.
2. You can ask any query to the bot (3 responses/min are allowed by OpenAi)
```
# Commands
```
/start - To start the conversation
/clear - To clear the previous conversation
/help - To get the help menu
```
# Troubleshooting
```
If it's not giving you a response that means you might have used 3 responses/min quota so wait for a while then ask your query again.
```
# Contact
```
If you face any kind of issue with the code or any suggestions you have, please feel free to reach out:-

Email:- nilaykr27@gmail.com
```