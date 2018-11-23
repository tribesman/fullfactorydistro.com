# fullfactorydistro.com
Products scrapper for fullfactorydistro.com

### Results

This programm generate two files:
* log.txt is a log file
* products.cvs is a table of products

### Before start
Create config file in programm folder ./config.toml

Example
```
Login = "login"
Password = "pwd"
```

### Build

```
GOOS=darwin GOARCH=amd64  go build -o build/fullfactorydistro_mac
GOOS=windows GOARCH=amd64  go build -o build/fullfactorydistro_win.exe
```

