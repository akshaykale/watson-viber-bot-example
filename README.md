# watson-viber-bot-example
Viber chat interface to interact with watson conservation APIs.

### Setup
> create `config` directory for storing the configurations.<br>
> add file `default.json` to `config/default.json`

##### config/default.json
```json
{
  "conv":{
    "username" : "<conservation_api_username>",
    "password" : "<password>",
    "workspace_id" : "<workspace_id>"
  },
  "viber":{
    "auth_token":"<auth_token>",
    "name":"<name_of_bot>"
  }
}
```


> For deploying, you need `config/production.json` file  for all the configurations.

##### config/production.json
```json
{
  "conv":{
    "username" : "<conservation_api_username>",
    "password" : "<password>",
    "workspace_id" : "<workspace_id>"
  },
  "viber":{
    "auth_token":"<auth_token>",
    "name":"<name_of_bot>"
  }
}
```


![screenshot_bot](https://github.com/akshaykale/watson-viber-bot-example/blob/master/viber-watson-conversation.png)




<br>
<br>

MIT License

Copyright (c) 2017 Akshay Kale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
