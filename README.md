OAuth Lift Module
==================

This module provides a the basics for building an OAuth server.

To include this module in your Lift project, update your `libraryDependencies` in `build.sbt` to include:

For Lift 2.6 and Scala 2.10 and 2.11:

    "net.liftmodules" %% "oauth_2.6" % "1.2-SNAPSHOT"


For Lift 3.0 and Scala 2.11:

    "net.liftmodules" %% "oauth_3.0" % "1.2-SNAPSHOT"


For Lift 2.5 and Scala 2.9 and 2.10:

    "net.liftmodules" %% "oauth_2.5" % "1.2"


**Note:** The module package changed from `net.liftweb.oauth` to `net.liftmodules.oauth` in May 2012.  Please consider this when referencing documentation written before that date.

---

Notes for module developers
===========================

* The [Jenkins build](https://liftmodules.ci.cloudbees.com/job/oauth/) is triggered on a push to master.



