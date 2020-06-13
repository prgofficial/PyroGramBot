# PyroGramUserBot 🔥🤖

A Telegram User / Bot based on [Pyrogram](https://github.com/pyrogram/pyrogram)

## Installing

#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/prgofficial/PyroGramBot)

#### The Legacy Way
Simply clone the repository and run the main file:

```sh
git clone https://github.com/prgofficial/PyroGramBot.git
cd PyroGramUserBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create config.py with variables as given below>
python3 -m pyrobot
```


## Getting config.py values

An example `config.py` file could be:

**Not All of the variables are mandatory**

__The UserBot should work by setting only these variables__

```python3
from pyrobot.sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  HU_STRING_SESSION = ""
```

## GET STRING SESSION (use this instead of termux app)

[![Repl.it](https://img.shields.io/badge/REPL%20RUN-Run%20Online-blue.svg)](https://string-gen.prgofficial.repl.run/)
