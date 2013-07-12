appengine-modules-sample-java


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
