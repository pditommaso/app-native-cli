# Java native app cli

Proof of concept for Java native application user Micronaut Http client and Picocli library 
for command line parsing.

## Get started 

```
 ./gradlew nativeImage
```

then run 

```
./build/graal/mycli 
./build/graal/mycli -h
./build/graal/mycli -V
```


### Credits 

[Mitch Seymour's blog post](https://medium.com/@mitch.seymour/building-native-java-clis-with-graalvm-picocli-and-gradle-2e8a8388d70d)
