# toran-proxy-environment
### Initial setup
##### Create .env file
```bash
echo -e "TORAN_REVERSE=true\nTORAN_HOST=toran-proxy.example.com\nTORAN_HTTPS=true\nPHP_TIMEZONE=Europe/Vilnius\nTORAN_TOKEN_GITHUB=123456\nTORAN_CRON_TIMER=daily" > .env
```

### Control
##### Start/restart environment
```bash
./scripts/launch.sh
```
