# logs

how to use, help, commands 
```bash
./apidsl.sh --help
```

## LOGS

print logs for latest run
```bash
./apidsl.sh --logs 'get("https://github.com/letpath/bash","letpath")'
```

## DEBUG

```bash
apidsl --logs 'letpath.load("apifork.txt")'
```

Show infos after run

```bash
apidsl --logs 'get("https://github.com/letpath/bash","letpath").letpath.load("apifork.txt")'
```


## STOP
