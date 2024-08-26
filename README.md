# commit-msg-config

[![Latest version of '@dlinc/commit-msg-config' @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/dogwoodlogic/dlinc/npm/@dlinc/commit-msg-config/latest/x/?render=true&show_latest=true&badge_token=gAAAAABmzMFcuOgX6fT4DQbqH0RX_WBNP4Bf0Uus-gMQtKwTeN4FtdeQhFED5XpgqmNqbFUAjHs7NG6KeFpzrDhSf1j9y-tCgT8JQ9FTO-fc035YrcXRMhI%3D)](https://cloudsmith.io/~dogwoodlogic/repos/dlinc/packages/detail/npm/@dlinc%252Fcommit-msg-config/latest/)

A JS script as a git hook which enforces the following commit message standards

- Messages must be shorter than 80 chars
- Messages must being with a capital letter
- Messages must end with a period

The script will auto correct messages that don't start with a capital or end with a period, and will reject commits over 80 chars.
