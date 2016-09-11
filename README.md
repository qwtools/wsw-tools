# Web tool for starting Warsow server

### Available endpoints
* http://warsow.online/stats - get info about running server
* http://warsow.online/start - start server
* http://warsow.online/stop - stop server
* http://warsow.online/ - get into game management console

You can create bash aliases for this operations
```bash
alias game-stats='curl http://warsow.online/stats'
alias game-start='curl http://warsow.online/start'
alias game-stop='curl http://warsow.online/stop'
```

### Deploy to DigitalOcean
* Get an [API Token]( https://cloud.digitalocean.com/settings/api/tokens)
* Export TOKEN environment variable
```bash
export TOKEN=<your token>
```
* Run deploy script
```bash
./deploy
```
