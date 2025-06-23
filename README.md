# Telegram-Bridge



create registration.yaml from config.yaml
```
cd mautrix-telegram/
docker run --rm   -v "$(pwd)":/data   dock.mau.dev/mautrix/telegram:latest   python -m mautrix_telegram -g     -c /data/config.yaml     -r /data/registration.yaml
```


pull discord bridge config.yaml from latest 
```
docker run --rm -v `pwd`:/data:z dock.mau.dev/mautrix/discord:latest
```