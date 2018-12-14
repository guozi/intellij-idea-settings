#### Plugins

+ Lombok Plugin

  > `Setting` ->  ***  ->   `Annotation Processors` -> `Enable annotation processing` ->  `ON`

+ Maven Helper

+ CodeGlance

+ GsonFormat

+ String Mainpulation

+ BaseSupport

+ .ignore

+ Alibaba Java Coding Guidelines



#### idea.vmpropertis

Performance tuning parameters for IntelliJ IDEA. Add these params in idea.vmoptions file in IntelliJ IDEA. If you are using JDK 8.x, please knock off PermSize and MaxPermSize parameters from the tuning configuration.

```
-server
-Xms2048m
-Xmx2048m
-XX:NewSize=512m
-XX:MaxNewSize=512m
-XX:PermSize=512m
-XX:MaxPermSize=512m
-XX:+UseParNewGC
-XX:ParallelGCThreads=4
-XX:MaxTenuringThreshold=1
-XX:SurvivorRatio=8
-XX:+UseCodeCacheFlushing
-XX:+UseConcMarkSweepGC
-XX:+AggressiveOpts
-XX:+CMSClassUnloadingEnabled
-XX:+CMSIncrementalMode
-XX:+CMSIncrementalPacing
-XX:+CMSParallelRemarkEnabled
-XX:CMSInitiatingOccupancyFraction=65
-XX:+CMSScavengeBeforeRemark
-XX:+UseCMSInitiatingOccupancyOnly
-XX:ReservedCodeCacheSize=240m
-XX:-TraceClassUnloading
-ea
-Dsun.io.useCanonCaches=false
```