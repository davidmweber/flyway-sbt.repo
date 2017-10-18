---
layout: default
---

## Flyway-sbt alternative Maven repo

This hosts releases of the [flyway-sbt plugin](https://github.com/flyway/flyway-sbt) 
for the impatient. The maintainers will publish snapshots and releases here first. 
The plugins should make their way to the [official site](https://flyway.org). Use 
this repo by adding the following to your `project/plugin.sbt` file:

```
resolvers += "Flyway" at "https://davidmweber.github.io/flyway-sbt.repo"

addSbtPlugin("org.flywaydb" % "flyway-sbt" % "4.2.0")
```

