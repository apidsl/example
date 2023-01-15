
![logo.apidsl.com](https://logo.apidsl.com/1/cover.png)

# [examples.apidsl.com](https://examples.apidsl.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/MENU.md) 

+ [contribution.apidsl.com](https://bash.apidsl.com/)
+ [Blog - www.apidsl.com](https://www.apidsl.com/)
+ [Documentation - docs.apidsl.com](https://docs.apidsl.com/)
+ [Logotyp: logo.apidsl.com](https://logo.apidsl.com/)
+ [LICENSE](LICENSE)

# Examples


+ [examples.apidsl.com](http://examples.apidsl.com)
+ [api # letAPI](http://examples.apidsl.com/api)
+ [deployment # letPath](http://examples.apidsl.com/deployment)
+ [letclient # make a screenshot](http://examples.apidsl.com/letclient)
+ [logs # logs](http://examples.apidsl.com/logs)
+ [loop # loop](http://examples.apidsl.com/loop)
+ [monitoring # letPath](http://examples.apidsl.com/monitoring)
+ [path # letPath](http://examples.apidsl.com/path)
+ [screenshot # make a screenshot](http://examples.apidsl.com/screenshot)
+ [whois # letWHOIS](http://examples.apidsl.com/whois)


## About apidsl [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/ABOUT.md)


Few examples:
+ Install apidsl project
+ Install letpath package

TODO: przenieść do examples
przykładowo aby zrobić zrzuty ekranu setek stron wystarczy lista plików w pliku tekstowym oraz 4 komendy w jednej linii

+ [screenshot # make a screenshot](http://examples.apidsl.com/screenshot)


## Start apidsl [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/START.md)

Test default functions

### Show the example functions

```bash
cat ../scripts/example2.txt
```
http("https://www.rezydent.de/").xpath("title");

---

### Check how it works

```bash
apidsl ../scripts/example2.txt
```
www | Rezydent Podatkowy Niemiec

---

## Test loaded package function

Install [letpath](https://github.com/letpath/bash) package to apidsl project in /apidsl/bash/letpath

```bash
./add.sh https://github.com/letpath/bash bash letpath
```

### Show the example functions
```bash
cd apidsl
```
```bash
cat ../scripts/example7.txt
```
http("https://www.rezydent.de/").letpath.tag("title");
```bash
apidsl ../scripts/example7.txt
```
---

### Check how it works
```bash
apidsl ../scripts/example7.txt
```
www | Rezydent Podatkowy Niemiec
    
---




## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/TODO.md)

przeniesć dokumentacje do docs
reszta do inframonit
przykładowe skrypty monitorujące w monit.page




# Tags

+ scripts
+ language

---

+ [edit](https://github.com/apidsl/examples/edit/main/README.md)
+ [apidsl/examples](https://github.com/apidsl/examples)
+ [examples.apidsl.com](https://examples.apidsl.com)

