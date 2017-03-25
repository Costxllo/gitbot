# GitBot - The GitHub Chatbot

<img src="https://github.com/nating/gitbot/blob/master/docs/assets/gitbot-inverted-black.png" width="300">

GitBot is a chatbot that is able to answer questions about information from GitHub.

## [How to interact with GitBot](https://github.com/nating/gitbot/wiki/Talking-to-GitBot)

You can simply send GitBot a message from one of the supported platforms.

<img src="https://github.com/nating/gitbot/blob/master/docs/assets/gitbot-demo.gif" width="900">


## Supported Platforms

GitBot is not yet published.

## [How GitBot Works](https://github.com/nating/gitbot/wiki/How-GitBot-Works)

<img src="https://github.com/nating/gitbot/blob/master/docs/assets/gitbot-explanation.png" width="900">

GitBot is a chatbot built with the [Microsoft Bot Framework](https://dev.botframework.com/) and is hosted on [Azure](https://azure.microsoft.com/).  

The Bot Framework connects GitBot to all of the supported messaging platforms. When a message is sent to GitBot from one of the messaging platforms, it goes to his endpoint on Azure. GitBot sends any messages he recieves to [Microsoft's Language Understanding Intelligence Service](https://www.microsoft.com/cognitive-services/en-us/language-understanding-intelligent-service-luis) to understand the intent of the message. When GitBot knows the intent of the message, he asks for the relevant data from GitHub. When the data is recieved from GitHub, GitBot sends his response back to the user.  
