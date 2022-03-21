# google-assistant-cli
Heavily based on [this](https://github.com/endoplasmic/google-assistant/blob/master/examples/console-input.js).

Added a possibility to use commandline arguments. If there aren't any present, show a prompt asking for the request.

## Installl dependencies
Install the required dependencies with ``yarn install``.

## Get keys
Register your project according to [this](https://developers.google.com/assistant/sdk/guides/service/python/embed/config-dev-project-and-account) but download your secrets.json from this site instead: [https://console.cloud.google.com/apis/credentials](https://console.cloud.google.com/apis/credentials).

Now run the script and log into your account. At the end, you are redirected to localhost. Inside the URL is your key, which you need to enter in the commandline.

## Usage
Send requests with
```console
node index.js light on
```
