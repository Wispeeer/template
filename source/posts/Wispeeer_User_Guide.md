------
title: Wispeeer User Guide
date: 2021-01-16 21:31:47
tags: [Wispeeer]
categories: [Wispeeer]
------


# Absract

Usage: wispeeer -[g p d h v] [-i alias_name] [-n title]

If you are using it for the first time,first execute the command "wispeeer init <Blog directory>" to initialize the blog.

<!-- more -->

# wispeeer

## 依赖 (Require)
### 编译依赖 (Build Require)
> GNU Make 3.81 (make --version)
> 
> git version 2.29.2 (git version)
> 
> go version go1.15.5 darwin/amd64 (go version)

### 功能依赖 (Run Require)
> git version 2.29.2 (git version)

## Build
```bash
make
```
**output like this**
```bash
making bin/wispeeer_latest_darwin_amd64
Wispeeer Version:eba79cb
Wispeeer Last Update:Sat Jan 16 18:02:15 CST 2021
```
binary program
`./bin/wispeeer_latest_<host info>`

## Usage
```bash
wispeeer -h
```

## wispeeer init
```bash
wispeeer init ${USER}.github.io
cd ${USER}.github.io
```

# Reference
- [github.com/ka1i/wispeeer](https://github.com/ka1i/wispeeer)
- [github.com/Wispeeer/template](https://github.com/Wispeeer/template)