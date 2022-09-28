# MojoHaus Exec Maven Plugin

This is the [exec-maven-plugin](http://www.mojohaus.org/exec-maven-plugin/).
 
[![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/mojohaus/sql-maven-plugin.svg?label=License)](http://www.apache.org/licenses/)
[![Maven Central](https://img.shields.io/maven-central/v/org.codehaus.mojo/exec-maven-plugin.svg?label=Maven%20Central)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.codehaus.mojo%22%20a%3A%22exec-maven-plugin%22)
[![Build Status](https://travis-ci.org/mojohaus/exec-maven-plugin.svg?branch=master)](https://travis-ci.org/mojohaus/exec-maven-plugin)
[![Build Status (AppVeyor)](https://ci.appveyor.com/api/projects/status/github/mojohaus/exec-maven-plugin?branch=master&svg=true)](https://ci.appveyor.com/project/khmarbaise/exec-maven-plugin)

## Releasing

* Make sure `gpg-agent` is running.
* Execute `mvn -B release:prepare release:perform`

For publishing the site do the following:

```
cd target/checkout
mvn verify site site:stage scm-publish:publish-scm
```
