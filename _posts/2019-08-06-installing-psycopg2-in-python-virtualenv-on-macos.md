---
layout: post
title:  "Installing psycopg2 in Python's virtualenv on macOS"
date:   2019-08-06 01:05:00 +0800
categories: [python, psycopg2, postgresql, virtualenv, pip, homebrew, brew]
---

### Background / Context

Packages and dependencies are installed with Homebrew.

#### Error

Homebrew `openssl` not linked to Python `pip`

#### Fix / Solution

Ensure that x-code Command Line Tool is installed:

```console
$ xcode-select --install
```

Update Homebrew and its packages:

```console
$ brew updates
$ brew upgrade
```

Install `psycopg2` with below command:

```console
$ env LDFLAGS=`$(pg_config --ldflags)` pip install psycopg2==2.8.3
```
