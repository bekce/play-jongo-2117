PlayJongo Play 2.6.x Module (bekce's fork)
==========================================

This fork actually WORKS for Play 2.6.x and Scala 2.12.2

Edit your `build.sbt` like: 

```
...
lazy val root = (project in file(".")).enablePlugins(PlayJava)
    .dependsOn(playJongo)

lazy val playJongo = RootProject(uri("https://github.com/bekce/play-jongo.git"))
...
```

[Here is a `build.sbt` file in a working project](https://github.com/bekce/oauthly/blob/master/build.sbt)

You're welcome.
