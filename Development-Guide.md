# Architecture

![](https://docs.google.com/drawings/d/1fGcN6fcKC_oCL1KtC_-pmWCT_1Da-ka0nijrzUuxiyw/pub?w=661&h=567)

[View large image](https://docs.google.com/drawings/d/1fGcN6fcKC_oCL1KtC_-pmWCT_1Da-ka0nijrzUuxiyw/pub?w=1984&h=1701)

# Technology Choices

* __Scala__ for data processing and Play framework: solid, stable toolkit for dealing with complex data.
* __jsoup__ for rendering templates: dynamic, works well with HTML5 and XML.

# Developing

Install SBT: http://www.scala-sbt.org/download.html

Use IntelliJ Community Edition: https://www.jetbrains.com/idea/download/. Simply import the directory as an 'SBT' project.

```
sbt web/run
```

# Running tests

```
sbt clean test it:test
```

# API endpoints

The API endpoints are intended to be stable.

We provide CSV where possible, and JSON otherwise.

## Recommended
* https://actionfps.com/player/by-email/?email=your-email@gmail.com
* https://actionfps.com/players/?format=json
* https://actionfps.com/all/games.ndjson
* https://actionfps.com/all/games.json
* https://actionfps.com/server-updates/
* https://actionfps.com/new-games/
* https://actionfps.com/inters/
* https://actionfps.com/clans/?format=csv
* https://actionfps.com/clans/?format=json

## Other
* https://actionfps.com/game/?id=2015-04-04T14:09:12Z&format=json
* https://actionfps.com/clan/?id=woop&format=json
* https://actionfps.com/all/games.tsv
* https://actionfps.com/all/games.csv
* https://actionfps.com/clanwars/?format=json
* https://actionfps.com/rankings/?format=json
* https://actionfps.com/clanwar/?id=2017-01-06T22:25:14Z&format=json
* https://actionfps.com/players/?format=registrations-csv
* https://actionfps.com/players/?format=nicknames-csv
* https://actionfps.com/players/?format=json
* https://actionfps.com/player/?id=sanzo&format=json
* https://actionfps.com/playerranks/?format=json
* https://actionfps.com/hof/?format=json
* https://actionfps.com/servers/?format=json
* https://actionfps.com/servers/?format=csv
* https://actionfps.com/ladder/?format=json

# Dev endpoints

As defined in [web/app/controllers/Dev.scala#L27](https://github.com/ScalaWilliam/ActionFPS/blob/master/web/app/controllers/Dev.scala#L27).

So you can edit templates without having to have the true data.

* https://actionfps.com/dev/live-template/
* https://actionfps.com/dev/clanwars/
* https://actionfps.com/dev/sig.svg
* https://actionfps.com/dev/sig/
* https://actionfps.com/dev/player/

# Debugging parsing issues etc

First stage of sanity is to use the 'dev-app' package:

```$xslt
$ sbt show dev-app/stage
...
[info] .../dev-app/target/universal/stage
$ .../dev-app/target/universal/stage
$ ls .../dev-app/target/universal/stage/bin
dev-app     dev-app.bat game-parser
$ 3999.log | ./dev-app/target/universal/stage/bin/game-parser
```