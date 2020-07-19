# JSON Parsing
Write a script to take an input string. Parse this json file - [images.json](./images.json) and list all images'  `name` field whose `family` field contains the input.

For example,

```bash
$ ./script "centos"
"centos-6-v20200618"
"centos-7-v20200618"
"centos-8-v20200618"
```

```bash
$ ./script "ubuntu"
"ubuntu-1604-xenial-v20200702"
"ubuntu-1804-bionic-v20200701"
"ubuntu-1910-eoan-v20200708"
"ubuntu-2004-focal-v20200701"
"ubuntu-minimal-1604-xenial-v20200702"
"ubuntu-minimal-1804-bionic-v20200703a"
"ubuntu-minimal-1910-eoan-v20200610"
"ubuntu-minimal-2004-focal-v20200702"
```