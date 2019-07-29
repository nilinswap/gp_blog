# gp_blog

A bare minimum page with [graftpress](https://github.com/amitu/graftpress) at the back.

## Getting Started

These instructions will get you a copy of the graftpress  project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites


```
node 8
Python 3.6+
Rust 1.36.0
```

### Installing

install graftpress-cli and graftpress using pip

```
$ pip install graftpress-cli
$ cargo install graftpress

```

Clone the repo and move inside the project folder

```
$ cd gp_blog

```

install elm

```
$ graftpress-cli init

```


## Deployment

build elm files

```
$ graftpress-cli build

```

run server

```
$ graftpress

```

go to https://127.0.0.1:3000

To publish website(statically) to say 'docs' folder, open another terminal 
while keeping graftpress server running, checkout to project folder and enter

```
$ graftpress-cli publish docs

```

You will see a new folder 'docs' with website content.


## Built With

* [graft](https://github.com/amitu/graft) 
* [graftpress](https://github.com/amitu/graftpress)