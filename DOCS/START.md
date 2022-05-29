
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
./apidsl.sh ../scripts/example2.txt
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
./apidsl.sh ../scripts/example7.txt
```
check from command
```bash
./apidsl.sh 'http("https://www.rezydent.de/").letpath.tag("title")'
./apidsl.sh 'letpath.tag("title")'
```

get whois data

```bash
./apidsl.sh 'letwhois.ns("softreck.com")'
```


```bash
./apidsl.sh 'letwhois.reverseIp("8.8.8.8")'
```

get ip from domain host

```bash
./apidsl.sh 'letwhois.domainIp("softreck.com")'
```

```bash
./apidsl.sh 'nslookup("softreck.com")'
```

---

### Check how it works
```bash
./apidsl.sh ../scripts/example7.txt
```
www | Rezydent Podatkowy Niemiec
    
---

## Test removing package function

remove [letpath](https://github.com/letpath/bash) package from apidsl project in /apidsl/bash/letpath

```bash
./del.sh bash letpath
```


