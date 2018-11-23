# fullfactorydistro.com
Products scrapper for fullfactorydistro.com

### Build
GOOS=darwin GOARCH=amd64  go build -o build/fullfactorydistro_mac
GOOS=windows GOARCH=amd64  go build -o build/fullfactorydistro_win.exe

./config.toml example
```
Login = "login"
Password = "pwd"
```
