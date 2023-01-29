# [Bandit](https://overthewire.org/wargames/bandit/) OverTheWire CTF writeups

Home page: https://overthewire.org/wargames/bandit/

## Connect the game
+ssh bandit0@bandit.labs.overthewire.org -p 2220


## Notes for game

+ most useful command is `ls -la`
+ useful resources are `man`, `help`, `--help`, `-h`, google search, wiki
+ directory store password 's room is `/etc/bandit_pass/bandit<level>` (can see, but can't open)
+ directory store file 's room is `/home/bandit<level>`
+ can't work on [~] (/home/user) because of restricted permissions
+ you should create a new folder for each level in /tmp/ to work because you will have full control with it

## Level 0-6

> topic: file and folder

| Username | Password |
| :--- | :--- |
| bandit0 | bandit0 |



| Username | Password |
| :--- | :--- |
| bandit1 | NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL |
| cmd | cat (filename) |


| Username | Password |
| :--- | :--- |
| bandit2 | rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi |
| cmd | cat./- |



| Username | Password |
| :--- | :--- |
| bandit3 | aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG |
| cmd | cat 'spaces in this filename'|




| Username | Password |
| :--- | :--- |
| bandit4 | 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe |
| cmd | file ./-file* |
| cmd | find . -type f -exec file {} \; | grep ":.* ASCII text" |



| Username | Password |
| :--- | :--- |
| bandit5 | lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR |
| cmd | find -size 1033c |


| Username | Password |
| :--- | :--- |
| bandit6 | P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU |


## Level 7-12

> topic: handle file data

| Username | Password |
| :--- | :--- |
| bandit7 | HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs |



| Username | Password |
| :--- | :--- |
| bandit8 | cvX2JJa4CFALtqS87jk27qwqGhBM9plV |



| Username | Password |
| :--- | :--- |
| bandit9 | UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR |



| Username | Password |
| :--- | :--- |
| bandit10 | truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk |



| Username | Password |
| :--- | :--- |
| bandit11 | IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR |



| Username | Password |
| :--- | :--- |
| bandit12 | 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu |



# Level 13-20

> topic: network protocol

| Username | Password |
| :--- | :--- |
| bandit13 | 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL |


| Username | Password |
| :--- | :--- |
| bandit14 | 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e |



| Username | Password |
| :--- | :--- |
| bandit15 | BfMYroe26WYalil77FoDi9qh59eK5xNr |



| Username | Password |
| :--- | :--- |
| bandit16 | cluFn7wTiGryunymYOu4RcffSxQluehd |



| Username | Password |
| :--- | :--- |
| bandit17 | xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn |




| Username | Password |
| :--- | :--- |
| bandit18 | kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd |



| Username | Password |
| :--- | :--- |
| bandit19 | IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x |



| Username | Password |
| :--- | :--- |
| bandit20 | GbKksEFF4yrVs6il55v6gwY5aVje5f0j |



# Level 21-26

> topic: cron jobs & shell script

| Username | Password |
| :--- | :--- |
| bandit21 | gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr |



| Username | Password |
| :--- | :--- |
| bandit22 | Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI |



| Username | Password |
| :--- | :--- |
| bandit23 | jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n |



| Username | Password |
| :--- | :--- |
| bandit24 | UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ |



| Username | Password |
| :--- | :--- |
| bandit25 | uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG |



| Username | Password |
| :--- | :--- |
| bandit26 | 5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z |



## Level 27-31

> topic: git

| Username | Password |
| :--- | :--- |
| bandit27 | 3ba3118a22e93127a4ed485be72ef5ea |



| Username | Password |
| :--- | :--- |
| bandit28 | 0ef186ac70e04ea33b4c1853d2526fa2 |



| Username | Password |
| :--- | :--- |
| bandit29 | bbc96594b4e001778eee9975372716b2 |



| Username | Password |
| :--- | :--- |
| bandit30 | 5b90576bedb2cc04c86a9e924ce42faf |


| Username | Password |
| :--- | :--- |
| bandit31 | 47e603bb428404d265f59c42920d81e5 |


## Level 32-33

> topic: other

| Username | Password |
| :--- | :--- |
| bandit32 | 56a9bf19c63d650ce78e6ec0354ee45e |


| Username | Password |
| :--- | :--- |
| bandit33 | c9c3199ddf4121b10cf581a98d51caee |




This is last level for now

**^^ finished ^^ thank you ^^**

## Author -Abhishek Shukla

CONNECT  WITH  ME -
+ [Github](https://github.com/AVI-SHUKLA1110)
