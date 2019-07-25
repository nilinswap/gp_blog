# gp_blog

A bare minimum page with graftpress at the back.

## Getting Started

These instructions will get you a copy of the graftpress  project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites



```
node 8
Python 3.7
Rust 1.36.0
```

### Installing

install graft-cli and graftpress using pip

```
pip install graft-cli
cargo install graftpress

```

move inside the project folder

```
cd gp_blog

```

install elm

```
graft-cli init

```





 

## Deployment

build elm files

```
graft-cli build

```

run server

```
graftpress

```

go to https://127.0.0.1:3000



## Built With

* [graft](https://github.com/amitu/graft) 
* [graft](https://github.com/amitu/graftpress)