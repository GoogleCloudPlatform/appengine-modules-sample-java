![status: inactive](https://img.shields.io/badge/status-inactive-red.svg)

This project is no longer actively developed or maintained.

For new work on this check out [java-docs-samples](https://github.com/GoogleCloudPlatform/java-docs-samples) and [getting-started-java](https://github.com/GoogleCloudPlatform/getting-started-java).


# appengine-modules-sample-java


It has 2 web apps each deployed to a different module: guestbook and shardedcounter.

Usage (After changing the app id in the appengine-modules-ear/src/main/application/META-INF/appengine-application.xml):

    git clone https://github.com/GoogleCloudPlatform/appengine-modules-sample-java.git
    cd appengine-modules-sample-java
    mvn install
    cd appengine-modules-ear
    #to test it locally:
    mvn appengine:devserver
    #or to deploy it:
    mvn appengine:update

=============================
