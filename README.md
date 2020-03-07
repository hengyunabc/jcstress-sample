

https://wiki.openjdk.java.net/display/CodeTools/jcstress 

```
mvn archetype:generate \
 -DinteractiveMode=false \
 -DarchetypeGroupId=org.openjdk.jcstress \
 -DarchetypeArtifactId=jcstress-java-test-archetype \
 -DarchetypeVersion=0.5 \
 -DgroupId=org.sample \
 -DartifactId=jcstress-sample \
 -Dversion=1.0
```

因为maven repository里只有 0.5版本的，所以要显式指定。

