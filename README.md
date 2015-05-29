Trail Drawing library
=====================

![drawing examples](https://github.com/Orange-OpenSource/trail-drawing/blob/master/demo/example.png)

A gesture trail drawing library for Android and Java applications

# Build the library

It is a maven build, so basically <pre><code>mvn install</pre></code> should do the job. It will install the library in your local repository. You can also retrieve the jar file under the target directory.

To use the library in a maven build:
<pre><code>
<dependency>
  <groupId>ccom.orange.dgil.trail</groupId>
  <artifactId>trail-core-lib</artifactId>
  <version>1.0-SNAPSHOT</version>
  <scope>compile</scope>
</dependency>
</pre></code>

In a gradle build:

<pre><code>
dependencies {
  compile "com.orange.dgil.trail:trail-core-lib:1.0-SNAPSHOT"
}
</pre></code>


The library will soon be published on maven central to ease developers' life.

# Demo applications
Can be found in the "demo" directory: android and javafx apps. Basically the javafx application is used to test and debug algorithms.
Above gestures where produced with the android "DroidTest" demo, whose prebuilt apk is here (click on "Raw" to save file): https://github.com/Orange-OpenSource/trail-drawing/blob/master/demo/DroidDrawingTest.apk

Happy testing!

# Authors
The library is born in 2014 at the Orange Labs in Meylan (french Alps). If Christophe Maldivi and Eric Petit practice cliff climbing together, they also sometimes write software together :)

# License
The trail drawing library is distributed under the terms and conditions of the Mozilla Public License v2.0, https://www.mozilla.org/MPL/2.0
