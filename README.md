# What is this?
Rod is REPLs On Docker. Use rod for your better programming experience.

# Prerequisite 
You need to install docker on your system to run rod.

# Usage
```
$ docker run -it kyagi/rod
```

or 

```
$ rod scala
```

# Supporting Programming Languages and REPLs

| Lang | Version | REPL | Pre-Installed Libraries |
| ----- | -------| ---- | ----------------------------------- |
| Scala | 2.12.4 | [amm](https://github.com/lihaoyi/Ammonite)  | cats, shapeless, fs2, doobie, circe |
| Ruby  | 2.4.3  | [pry](https://github.com/pry/pry)  | rubocop, guard                      |
| Go    | 1.9.6  | gore | TBD                                 |
