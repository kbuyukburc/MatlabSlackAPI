# Story
 Hi everyone,
  I started this Matlab project for anybody who wants to share figures and results
  with their Teammates through Slack.

## Here We Go
>  What Do You NEED?
  - Slack Channel
  - Access Token.
  - Not required any external ToolBox
  - Keyboard

## Access Token
 - You can create your [Token here.](https://api.slack.com/custom-integrations/legacy-tokens)
 - it should something like xoxp-XXXXXXXXXX-XXXXXXXX-XXXXXXXX-XXXXXXXXXXXXXXXXXXXXXXX

## How to USE
```
>>api = SlackAPI('xoxp-XXXXXXXXXX-XXXXXXXX-XXXXXXXX-XXXXXXXXXXXXXXXXXXXXXXX')
>>SendMsg(api, '@kbuyukburc', 'Hello World')
>>SendMsg(api,'#general','Hello Glaxy')
>>SendFile(api,'#general','test.jpg')
```
