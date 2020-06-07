# Sbt

sbt (scala build tool) is an open-source build tool for Scala and Java projects, similar to Java's Maven and Ant. It runs in the terminal

Execute sbt to enter it's shell:

```bash
$ sbt
```

You will see the prompt change from the bash prompt `$` to `>`

## Useful links

- [Directory Structure](https://www.scala-sbt.org/1.x/docs/Directories.html)
- [Commands](https://www.scala-sbt.org/1.x/docs/Running.html)
- [Command Line Reference](https://www.scala-sbt.org/1.x/docs/Command-Line-Reference.html)
- [Running SBT commands](https://www.scala-sbt.org/1.x/docs/Running.html)
- [Sbt's project structure](https://www.scala-sbt.org/1.x/docs/Directories.html)

## Sbt cheatsheet

| Command                  |            Description             |
| ------------------------ | :--------------------------------: |
| `help`                   | shows some info about sbt commands |
| `project <project name>` |        switch to a project         |
| `projects`               |      shows available projects      |
| `runMain`                |   runs an app in the main folder   |
| `testOnly`               |          executes a test           |
| `test`                   |         executes all tests         |
| `compile`                |      compiles the main folder      |
| `test:compile`           | compiles the main and test folder  |
| `console`                |    runs the scala REPL console     |
| `clean`                  |      cleans the compiled code      |
| `reload`                 |      reloads the sbt project       |
| `reload`                 |      reloads the sbt project       |
