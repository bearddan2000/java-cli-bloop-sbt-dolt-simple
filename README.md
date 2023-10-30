# java-cli-bloop-sbt-dolt-simple

## Description
A java bloop-sbt build, that connects to dolt database.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - 6.8.2

## Docker stack
- dolthub/dolt-sql-serverdb:latest
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
