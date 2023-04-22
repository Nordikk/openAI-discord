# OpenAI Discord Bot (powered by Nordik-Hosting)


## Features

* `/chat [message]` Chat with ChatGPT!
* `/draw [prompt]` Generate an image with the Dalle2 model
* `/switchpersona [persona]` Switch between optional chatGPT jailbreaks
   * `random`: Picks a random persona
   * `chatGPT`: Standard chatGPT mode
   * `dan`: Dan Mode 11.0, infamous Do Anything Now Mode
   * `sda`: Superior DAN has even more freedom in DAN Mode
   * `confidant`: Evil Confidant, evil trusted confidant
   * `based`: BasedGPT v2, sexy gpt
   * `oppo`: OPPO says exact opposite of what chatGPT would say
   * `dev`: Developer Mode, v2 Developer mode enabled

* `/private` ChatGPT switch to private mode
* `/public` ChatGPT switch to public mode
* `/replyall` ChatGPT switch between replyAll mode and default mode
* `/reset` Clear ChatGPT conversation history
* `/chat-model` Switch different chat model
   * `OFFICIAL-GPT-3.5`: GPT-3.5 model
   * `OFFICIAL-GPT-4.0`: GPT-4.0 model (make sure your account can access gpt-4 model)
   * `Website ChatGPT-3.5`: Website ChatGPT-3.5 model (UNOFFICIAL)
   * `Website ChatGPT-4.0`: Website ChatGPT-4.0 model (UNOFFICIAL)(available if you got a plus account)
   * `Bard`: Google Bard Model


### Switch Persona

![image](https://user-images.githubusercontent.com/91911303/223772334-7aece61f-ead7-4119-bcd4-7274979c4702.png)



### Mode

* `public mode (default)`  the bot directly reply on the channel

  ![image](https://user-images.githubusercontent.com/89479282/206565977-d7c5d405-fdb4-4202-bbdd-715b7c8e8415.gif)

* `private mode` the bot's reply can only be seen by the person who used the command

  ![image](https://user-images.githubusercontent.com/89479282/206565873-b181e600-e793-4a94-a978-47f806b986da.gif)

* `replyall mode` the bot will reply to all messages in the channel without using slash commands (`/chat` will also be unavailable)

   > **Warning**
   > The bot will easily be triggered in `replyall` mode, which could cause program failures


