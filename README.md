# KIT ILIAS Persistent Login

A small Tampermonkey userscript for KIT ILIAS.

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Click the link below to install the userscript:

**[Install KIT ILIAS Persistent Login](https://raw.githubusercontent.com/cos7/kit-ilias-persistent-login/main/kit-ilias-persistent-login.user.js)**

## How it works

The script sends a GET request to the currently open ILIAS page at a random interval of 10–20 minutes. It includes the browser's existing session cookies, which may help keep the ILIAS session active.

**Note:** The script only runs while a matching ILIAS page is open. It stops when all matching tabs are closed.

Privacy: This script does not collect, store, or transmit any personal information or cookies. Session cookies are only used by the browser when sending requests to KIT ILIAS.
