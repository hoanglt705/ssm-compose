# Command run
Start infrastructure
```bash
$ docker-compose.exe -f ssm-mixin-db.yml -f ssm-mixin-core.yml up
```

Stop infrastructure
```bash
$ docker-compose.exe -f ssm-mixin-db.yml -f ssm-mixin-core.yml down
```

Start client
```bash
$ wget "https://mymavenrepo.com/repo/0gYeR1uVbGBd8IBUlAOb/com/s3s/ssm/ssm-core-legacy/1.1/ssm-core-legacy-1.1.jar"
```