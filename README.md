# Alexa's skill Maurice Chatgpt

![Node.js](https://img.shields.io/static/v1?style=flat-square&message=Node.js&color=339933&logo=Node.js&logoColor=FFFFFF&label=)
![OpenAI ChatGPT](https://img.shields.io/static/v1?style=flat-square&message=OpenAI&nbsp;ChatGPT&color=412991&logo=OpenAI&logoColor=FFFFFF&label=)
[![MIT Licensed](https://img.shields.io/github/license/noweh/alexa-maurice-chatgpt)](LICENSE)

<p align="center">
  <img src="https://s3.amazonaws.com/CAPS-SSE/echo_developer/2b13/b6fbe90e252b408c9eb21b85c921f5f1/APP_ICON?versionId=CsEltRB34BIqeN0mwkraDApiqwqc_lJq&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230110T182746Z&X-Amz-SignedHeaders=host&X-Amz-Expires=86400&X-Amz-Credential=AKIAWBV6LQ4QJ72TE65Z%2F20230110%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=187e707b368c63347d5b3febae398cd542c39debd2f0dec0bce168408d4d7179" />
</p>

Source code of a Alexa's skill using ChatGPT API.

:warning: This skill is still in development because there are still some issues to validate.

## Prerequisite

For the skill to work, you need to [generate](https://beta.openai.com/account/api-keys) an OpenAI API key and replace it in the file [/index.php](/index.php).

---

## Common issues observed

1.	The skill allowed the user to search for mature questions but failed to filter out inappropriate responses via voice and home card. 
Please ensure that the skill filters out responses via voice and home card that violate Amazon content policies including profanity, sexually explicit material, hate speech or other mature content.

2.	The skill allowed the user to search for answers to questions but failed to provide clear attribution to the source of those answers. 
Please ensure that the skill provides attribution to the source in the skill description, voice response or home card.
