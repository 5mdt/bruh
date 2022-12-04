# bruh

Bruh is a simple IM CLI notification tool.

## When i need it

Typical use-case for this utility:

```bash
# some-task-running-for-time ; bruh
```

When the long running task would end - the bot (in IM, like telegram, ms teams, etc) sends you a message

## Config.yml

Config template

```yaml
---
credentials:
  - name: telegram_private
    token: AAAAAA
    chat_id: 0
    type: telegram
    exitcode: true
  - name: telegram_chat
    token: BBBBBB
    chat_id: -0
    type: telegram
    message: "Please notice me, sempai"
  - name: MS_TEAMS_PROD
    token: CCCCCC
    type: msteams
default_cred: telegram_private
default_message: "bruh"
```

## Links

- [Github Project](https://github.com/5mdt/bruh)
- DockerHub Page

## License

All code in this repository is licensed under the terms of the MIT License. For further information please refer to the LICENSE file.

## Authors

- Vladimir Budylnikov aka [@nett00n](https://github.com/nett00n)

---
2022, Yerevan

