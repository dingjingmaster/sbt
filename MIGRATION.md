Migration notes
===============

- `project/Build.scala` style based on `sbt.Build` is removed. Migrate to `build.sbt`.
- `Project(...)` constructor is limited to just two parameters.

- change import in auto plugin to:

```scala
import sbt._, syntax._, Keys._
```