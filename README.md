# Telegram File Share Bot

## Features
- Upload files from admin account
- Generate share links
- Users click and receive files
- Works on Termux
- Python based

## Install (Termux)

```bash
pkg update -y
pkg install python -y
pip install -r requirements.txt
```

## Run

Edit `main.py`

Replace:

```python
TOKEN = "YOUR_BOT_TOKEN"
ADMIN_ID = 123456789
```

Then run:

```bash
python main.py
```

## Get Bot Token
Create bot from @BotFather
