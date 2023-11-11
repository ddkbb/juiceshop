# OWASP


## Install Burpsuite
1. Navigate to https://portswigger.net/burp/releases/professional-community-2023-10-3-4?requestededition=community&requestedplatform=
2. Make sure the options are set to `Burp Suite Community Edition` and `Linux (64-bit)` and click `Download`

## Install Firefox
1. Navigate to https://www.mozilla.org/en-US/firefox/new/

## Setting up FoxyProxy
1. Download foxyproxy standard from this link
https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
2. enable extension in private browsing
3. click on the extension and hit `Options`
4. navigate to `Proxies` tab
5. click `Add` and configure a new proxy
6. title `Burp`
7. type: `HTTP`
8. hostname: `127.0.0.1`
9. port: `8080`
10. click `save`
