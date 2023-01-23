SlickGrid-webjars
=================

- WebJar for SlickGrid
- More info:
- Upstream: http://github.com/6pac/SlickGrid

## Deploy to clojars as follows:
- Update groupId, artifactId and version as needed
- Run the following command
```console
mvn deploy:deploy-file -Dfile=target/SlickGrid-3.0.2.jar -DpomFile=pom.xml -DrepositoryId=clojars -Durl=https://clojars.org/repo/
```

You'll need to set up clojars credentials by following these instructions: https://cljdoc.org/d/com.github.seancorfield/depstar/2.1.303/doc/deployment#deploying-with-maven
