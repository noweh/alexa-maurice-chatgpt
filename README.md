<p align="center">
  <img width="250px" src="/img/image.png" />
</p>

# Alexa's skill Maurice Chatgpt

![Node.js](https://img.shields.io/static/v1?style=flat-square&message=Node.js&color=339933&logo=Node.js&logoColor=FFFFFF&label=)
![OpenAI ChatGPT](https://img.shields.io/static/v1?style=flat-square&message=OpenAI&nbsp;ChatGPT&color=412991&logo=OpenAI&logoColor=FFFFFF&label=)
[![MIT Licensed](https://img.shields.io/github/license/noweh/alexa-maurice-chatgpt)](LICENSE)

Source code of a Alexa's skill using ChatGPT API.

:warning: This skill is still in development because there are still some issues to validate.

## Prerequisite

For the skill to work, you need to [generate](https://beta.openai.com/account/api-keys) an OpenAI API key and replace it in the file [/alexa-skill/lambda/index.js](/alexa-skill/lambda/index.js).

---

## Common issues observed

1.	The skill allowed the user to search for mature questions but failed to filter out inappropriate responses via voice and home card. 
Please ensure that the skill filters out responses via voice and home card that violate Amazon content policies including profanity, sexually explicit material, hate speech or other mature content.

2.	The skill allowed the user to search for answers to questions but failed to provide clear attribution to the source of those answers. 
Please ensure that the skill provides attribution to the source in the skill description, voice response or home card.
