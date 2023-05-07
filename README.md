# kbot
kbot project


# Build path
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