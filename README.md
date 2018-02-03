# What is this?
Rod is REPLs On Docker. Use rod for your better programming experience.

# Prerequisite 
You need to install docker on your system to run rod.

# Dockerhub
https://hub.docker.com/r/kyagi/rod/

# Usage
```
$ docker run -it kyagi/rod
 ____  _____ ____  _                         ____             _
|  _ \| ____|  _ \| |    ___    ___  _ __   |  _ \  ___   ___| | _____ _ __
| |_) |  _| | |_) | |   / __|  / _ \| '_ \  | | | |/ _ \ / __| |/ / _ \ '__|
|  _ <| |___|  __/| |___\__ \ | (_) | | | | | |_| | (_) | (__|   <  __/ |
|_| \_\_____|_|   |_____|___/  \___/|_| |_| |____/ \___/ \___|_|\_\___|_|

root@04eef017dfc0:~# rod scala
```

or
```
$ git clone git@github.com:kyagi/rod.git
$ cd rod
$ ./rod scala
```

# Supporting Programming Languages and REPLs

| Lang | Version | REPL | Pre-Installed Libraries |
| ----- | -------| ---- | ----------------------------------- |
| [Scala](https://www.scala-lang.org/)  | 2.12.4 | [amm](https://github.com/lihaoyi/Ammonite) | cats, shapeless, fs2, doobie, circe |
| [Ruby](https://www.ruby-lang.org/en/) | 2.4.3  | [pry](https://github.com/pry/pry)  | rubocop, guard |
| [Go](https://golang.org/)             | 1.9.6  | [gore](https://github.com/motemen/gore) | TBD |
