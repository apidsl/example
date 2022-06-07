
# logs

how to use, help, commands 
```bash
./apidsl.sh --help
```
EXECUTED bash:
```bash
apidsl 0.2
OPERATOR or COMMAND is needed!
# OPERATORS:
apidsl dev - development packages, for contributors and developers
apidsl test - for testing the project
apidsl --get - get require dependency files apidsl script from file
apidsl --run - run apidsl script from file
apidsl --clean - clean cache data
apidsl --help - how to use apidsl
apidsl --history - show logs during runnig
apidsl --logs - show logs during runnig
apidsl --init - copy command apidsl.sh to /usrl/local/bin to use apidsl such a system command in shell
  apidsl --init apidsl - with 2 params: copy command apidsl to /usrl/local/bin to use apidsl such a system command in shell
apidsl --download - download from repository and save as apidsl file
# USAGE COMMAND:
apidsl 'get("https://github.com/letpath/bash","path")' - import project from git
apidsl 'path.load("flatedit.txt")' - use imported command, such load file 
```

## LOGS

print logs for latest run
```bash
./apidsl.sh --logs 'get("https://github.com/letpath/bash","letpath")'
```
EXECUTED bash:
```bash
./apidsl.sh: ./.apidsl.cache/1654635640.sh: /bin/b: Defekter Interpreter: Datei oder Verzeichnis nicht gefunden


COMMANDS:
get("https://github.com/letpath/bash","letpath"



SCRIPTS:
#!/bin/ba

LOGS:
23:00:40.066 START
CMD get("https://github.com/letpath/bash","letpath")
OPTION --logs
INPUT_FILE_PATH .apidsl.cache/1654635640.txt
get("https://github.com/letpath/bash","letpath")
LINE BEFORE CLEANING: get("https://github.com/letpath/bash","letpath"
 KEY: get
 VAL: "https://github.com/letpath/bash","letpath"
LINE BEFORE CLEANING: 
 F0: get
 V0: "https://github.com/letpath/bash","letpath"
!!! FOLDER letpath EXIST, PLEASE INSTALL IN ANOTHER FOLDER 
END: .apidsl.cache/1654635640.sh
```

## DEBUG

```bash
apidsl --logs 'letpath.load("apifork.txt")'
```
EXECUTED bash:
```bash
https://github.com/apidsl/bash apidsl


COMMANDS:
letpath.load("apifork.txt"



SCRIPTS:
#!/bin/bash
./letpath/load.sh "apifork.txt"

LOGS:
23:00:40.079 START
CMD letpath.load("apifork.txt")
OPTION --logs
INPUT_FILE_PATH .apidsl.cache/1654635640.txt
letpath.load("apifork.txt")
LINE BEFORE CLEANING: letpath.load("apifork.txt"
 KEY: letpath.load
 VAL: "apifork.txt"
LINE BEFORE CLEANING: 
 F0: letpath.load
 V0: "apifork.txt"
ADD COMMAND 0: letpath.load "apifork.txt"
ADD SCRIPT 0: ./letpath/load.sh "apifork.txt" TO FILE: .apidsl.cache/1654635640.sh
END: .apidsl.cache/1654635640.sh
```

Show infos after run

```bash
apidsl --logs 'get("https://github.com/letpath/bash","letpath").letpath.load("apifork.txt")'
```
EXECUTED bash:
```bash
https://github.com/apidsl/bash apidsl


COMMANDS:
get("https://github.com/letpath/bash","letpath"
letpath.load("apifork.txt"



SCRIPTS:
#!/bin/bash
./letpath/load.sh "apifork.txt"

LOGS:
23:00:40.094 START
CMD get("https://github.com/letpath/bash","letpath").letpath.load("apifork.txt")
OPTION --logs
INPUT_FILE_PATH .apidsl.cache/1654635640.txt
get("https://github.com/letpath/bash","letpath").letpath.load("apifork.txt")
LINE BEFORE CLEANING: get("https://github.com/letpath/bash","letpath"
 KEY: get
 VAL: "https://github.com/letpath/bash","letpath"
LINE BEFORE CLEANING: letpath.load("apifork.txt"
 KEY: letpath.load
 VAL: "apifork.txt"
LINE BEFORE CLEANING: 
 F0: get
 V0: "https://github.com/letpath/bash","letpath"
!!! FOLDER letpath EXIST, PLEASE INSTALL IN ANOTHER FOLDER 
 F1: letpath.load
 V1: "apifork.txt"
ADD COMMAND 1: letpath.load "apifork.txt"
ADD SCRIPT 1: ./letpath/load.sh "apifork.txt" TO FILE: .apidsl.cache/1654635640.sh
END: .apidsl.cache/1654635640.sh
```


## STOP
