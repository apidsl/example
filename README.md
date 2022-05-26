# example.apidsl.com

Install:
+ apidsl
+ apimacro
+ flatedit
+ plainedit

+ Example with plainedit

## START

install apidsl

```bash
git clone https://github.com/apidsl/bash apidsl
````

We are working on apidsl folder
```bash
cd apidsl 
````

### Test default function

Test 1

```bash
cat ../scripts/example2.txt
```
    http("https://www.rezydent.de/").xpath("title");

```bash
./apidsl.sh ../scripts/example2.txt
```

### Test loaded package function

Install [letpath](https://github.com/letpath/bash) package to apidsl project in /apidsl/bash/letpath

```bash
./add.sh https://github.com/letpath/bash bash letpath
```

Test 2

```bash
cat ../scripts/example7.txt
```
    http("https://www.rezydent.de/").letpath.tag("title");

```bash
./apidsl.sh ../scripts/example7.txt
```
