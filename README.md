# Kbot
The starter project Kbot.

# Requirements & Dependencies
- Language: Go
- Messaging: Telegram
- Lib: github.com/spf13/cobra-cli
- Lib: gopkg.in/telebot.v3

# How to connect
https://t.me/aabootis_bot

# How to build
```
git clone https://github.com/aabootis/kbot.git
cd kbot
go install

# WINDOWS PWSH
$env:TELE_TOKEN = "5855378706:AAE3b1C0XzvNlyLO9sXAqEHlqF7lEuUzKtE"

# LINUX
export TELE_TOKEN=5855378706:AAE3b1C0XzvNlyLO9sXAqEHlqF7lEuUzKtE

go build -ldflags "-X=github.com/aabootis/kbot/cmd.appVersion=v1.0.2"

kbot start
```
# Command examples
```
command: /exec hello
response: Hello I'm Kbot v1.0.2!

command: /exec bye
response: See you later, Alligator.

command: /exec where is the money
response: No money, no fanny.

```

# Create path
```
go get github.com/spf13/cobra-cli
go install github.com/spf13/cobra-cli
cobra-cli init
cobra-cli add version
go run main.go help
go run main.go version
cobra-cli add kbot
go build -ldflags "-X=github.com/aabootis/kbot/cmd.appVersion=v1.0.0"
./kbot
./kbot version
```

Update
```
go build -ldflags "-X=github.com/aabootis/kbot/cmd.appVersion=v1.0.2"
# pwsh env
$env:TELE_TOKEN = "5855378706:AAE3b1C0XzvNlyLO9sXAqEHlqF7lEuUzKtE"
kbot start

```