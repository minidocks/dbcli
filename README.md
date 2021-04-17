DBCLI docker image ([minidocks/dbcli](https://hub.docker.com/r/minidocks/dbcli))
================================================================================

![](https://www.dbcli.com/images/avatar.png)

[DBCLI](https://www.dbcli.com/) is Commandline Database Clients with
Autocompletion and Syntax Highlighting.

Usage
-----

Run `pgcli`:

```shell
docker run --rm -it -v `pwd`:/app -w /app minidocks/dbcli:pgcli --help
```

Run `mycli`:

```shell
docker run --rm -it -v `pwd`:/app -w /app minidocks/dbcli:mycli --help
```

Run `litecli`:

```shell
docker run --rm -it -v `pwd`:/app -w /app minidocks/dbcli:litecli --help
```

Run `iredis`:

```shell
docker run --rm -it -v `pwd`:/app -w /app minidocks/dbcli:iredis --help
```

Run container with `pgcli`, `mycli` and `litecli`:

```shell
docker run --rm -it -v `pwd`:/app -w /app minidocks/dbcli sh
```

Tags
----

| Tag     | Size                                                                         |
|---------|------------------------------------------------------------------------------|
| latest  | ![](https://images.microbadger.com/badges/image/minidocks/dbcli.svg)         |
| pgcli   | ![](https://images.microbadger.com/badges/image/minidocks/dbcli:pgcli.svg)   |
| mycli   | ![](https://images.microbadger.com/badges/image/minidocks/dbcli:mycli.svg)   |
| litecli | ![](https://images.microbadger.com/badges/image/minidocks/dbcli:litecli.svg) |
| iredis  | ![](https://images.microbadger.com/badges/image/minidocks/dbcli:iredis.svg)  |
