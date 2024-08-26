# commit-msg-config

![NPM Version](https://img.shields.io/npm/v/%40dlinc%2Fcommit-msg-config)

A JS script as a git hook which enforces the following commit message standards

- Messages must be shorter than 80 chars
- Messages must being with a capital letter
- Messages must end with a period

The script will auto correct messages that don't start with a capital or end with a period, and will reject commits over 80 chars.
