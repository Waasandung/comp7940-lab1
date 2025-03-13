## comp7940-lab1

It's an assignment program🧑‍🎓, aiming to build a chatbot in telegram🤖.   
***config.ini*** file is needed to add at the root directory🫚, in the form of   
```
[TELEGRAM]
ACCESS_TOKEN = 
[REDIS]
HOST = 
PASSWORD = []
REDISPORT = 
DECODE_RESPONSE = True
USER_NAME = 'default'
[CHATGPT]
BASICURL = https://genai.hkbu.edu.hk/general/rest
MODELNAME = gpt-4-o-mini
APIVERSION = 2024-05-01-preview
ACCESS_TOKEN =
```   
To get your own `ACCESS_TOKEN` of your telegram chatbot🈶, you can search and add **@BotFather**, and send the message `/newbot`💬.   
`HOST`, `PASSWORD`, and `REDISPORT` are used to connect your *Redis cloud database* with the *client* type *Python*☁️.    
Open the *[HKBU's ChatGPT webpage](https://genai.hkbu.edu.hk/)*, and select *API* in the upper-right corner of the webpage↗️ to generate an *access token*.   
___
Other languages versions will be added later🌐.
___
In the lastest change, the access token has been stored on cloud🗝️.
