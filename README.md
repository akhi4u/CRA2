 [![N|Solid](http://doc.rultor.com/images/docker-logo.png)](https://www.docker.com/)
# UMASSD CIS 602-01 CR [Assignment 2] [assign]

### Important commands and links:
Use the links to checkout images at [Docker Hub][hub] and commands to execute them.

* For Build it yourself
-- Please clone the repo
-- Install [VisTrails][vistrails] and [Docker][docker]

### Part 1: 
* Open the file <tb.vt> from folder P1 in VisTrails and execute the workflow.

### Base: [Image] [Base]
* Part 2 and 3 use the Base image.

Build it yourself:
```sh
$ cd Base
$ docker build -t akhi4u/vistrails .
```
Direct execution:
 ```sh
$ docker run -i -t akhi4u/vistrails
```
### Part 2: [Image] [part2n3]
Build it yourself:
```sh
$ cd P2
$ docker build -t akhi4u/tb-wf:nigeria .
```
Direct execution:
 ```sh
$ docker run akhi4u/tb-wf:nigeria
```
### Part 3: [Image] [part2n3]
Build it yourself:
```sh
$ cd P3
$ docker build -t akhi4u/tb-wf:parameterized .
```
Direct execution:
 ```sh
$ docker run akhi4u/tb-wf:parameterized country=Albania
```







   [Base]: <https://hub.docker.com/r/akhi4u/vistrails/>
   [hub]: <https://hub.docker.com/>
   [docker]: <https://www.docker.com/>
   [vistrails]: <https://www.vistrails.org/index.php/Main_Page>
   [part2n3]: <https://hub.docker.com/r/akhi4u/tb-wf/>
   [assign]: <http://www.cis.umassd.edu/~dkoop/cis602-2016fa/assignment2.html>
  
