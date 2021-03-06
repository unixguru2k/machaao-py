# machaao - make personalized chatbots that scale
[![codebeat badge](https://codebeat.co/badges/9ddf5add-675b-4816-8209-45cf29e686a3)](https://codebeat.co/projects/github-com-machaao-machaao-py-master)  

An easy to use module for python developers looking to build, prototype and publish chat apps

### Minimum Requirements
```bash
python # 3.6 or higher version
```

# Get your FREE API Key through the Dev Portal
Get your FREE API Key @ https://portal.messengerx.io

### Install
```bash
# For Linux/MacOS
pip3 install machaao

# For Windows
pip install machaao
```

### Create new chatbot project
```bash
machaao startproject -s <project_name>
```

### Navigate to the newly created chatbot project directory
```bash
cd <project_name>
```

### Open ```chatbot.py``` in any text editor, update the api key and base url as shown below
```bash
MESSENGERX_API_TOKEN = "<API_KEY_FROM_PORTAL>"
MESSENGERX_BASE_URL = "https://ganglia-dev.machaao.com" [for development purposes]
```
### Run Machaao Tunnel in a seperate terminal and note down your FORWARDING URL
```bash
machaao tunnel -p 5000 -t [CHATBOT-TOKEN]

[https://<....>.tunnel.messengerx.io/]
```


### Go to your bot settings on the portal and update your Chatbot Webhook URL Settings
```bash
[https://<....>.tunnel.messengerx.io/machaao/incoming]
```

### Run your simple chatbot on your local server
```bash
# For Linux/MacOS
python3 chatbot.py

# For Windows
python chatbot.py
```

###  https://dev.messengerx.io/<chatbot_name> to send a message to your chatbot.


### Your chatbot is now ready to start receiving incoming messages from users
```bash
# HappyCoding
```

#### NOTE: UNDER ACTIVE DEVELOPMENT (ACCEPTING PULL REQUESTS)
