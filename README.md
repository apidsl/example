
![logo.apidsl.com](https://logo.apidsl.com/1/cover.png)

# [examples.apidsl.com](https://examples.apidsl.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/MENU.md) 

+ [Blog - www.apidsl.com](https://www.apidsl.com/)
+ [Documentation - docs.apidsl.com](https://docs.apidsl.com/)
+ [Logotyp: logo.apidsl.com](https://logo.apidsl.com/)

+ [LICENSE](LICENSE)


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




## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/CONTRIBUTION.md)

Solutions for development:


## Contribution - documentation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/CONTRIBUTION/DOCS.md)


Edit documentation in 2 steps, first make the outputs over **plainedit.sh**
Create docs over **readme.sh**

list of projects
```bash
./plainedit.sh
```

Update html over plainedit

```bash
./plainedit.sh debug
```
```bash
./plainedit.sh deployment
```
```bash
./plainedit.sh api
```
```bash
./plainedit.sh client
```
```bash
./plainedit.sh path
```
```bash
./plainedit.sh whois
```
```bash
./plainedit.sh loop
```
```bash
./plainedit.sh monitoring
```
```bash
./plainedit.sh screenshot
```


Update documentation

```bash
./readme.sh
```




## Contribution - installation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/CONTRIBUTION/INSTALL.md)

Solutions for development:

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```


Install package list after created project
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
echo "https://github.com/letwhois/bash apidsl/apidsl/bash letwhois" >> "apipackage.txt"
./apipackage install
```

### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```


## Contribution - installation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/CONTRIBUTION/INSTALL.md)

Solutions for development:



### update

```bash
./apifork update
```



## Contribution - remove [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/examples/edit/main/DOCS/CONTRIBUTION/CLEAN.md)


### remove

```bash
./apifork remove
```



# Tags

+ scripts
+ language

---

+ [edit](https://github.com/apidsl/examples/edit/main/README.md)
+ [apidsl/examples](https://github.com/apidsl/examples)
+ [examples.apidsl.com](https://examples.apidsl.com)
