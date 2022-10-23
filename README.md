# CrazyAdvancementsAPI (Gradle)

CrazyAdvancementsAPI (Gradle) is a **fork** of [CrazyAdvancementsAPI](https://github.com/ZockerAxel/CrazyAdvancementsAPI) so that we can use **CrazyAdvancementsApi** as **Gradle/Maven dependency from Jitpack**.


### How to use it ?

You can add it like that :
 
- Add the Jitpack repository :

**Gradle :**
```
repositories {
    ...
    maven { url 'https://jitpack.io' }
}
```

**Maven :**
```
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

- Add the dependency :

**Gradle :**
```
dependencies {
    implementation 'com.github.Benco11-developement:CrazyAdvancementsAPI-Gradle:2.1.11'
}
```

**Maven :**
```
<dependency>
    <groupId>com.github.Benco11-developement</groupId>
    <artifactId>CrazyAdvancementsAPI-Gradle</artifactId>
    <version>2.1.11</version>
</dependency>
```

## Original

## About

CrazyAdvancementsAPI is an API for creating and managing Advancements programmatically on Minecraft Spigot Servers


## Documentation

The Official Documentation can be found [here][0]

There is also Javadoc available [here][1]

[0]: https://docs.crazyadvancements.endercentral.eu "Official Documentation"
[1]: https://javadoc.crazyadvancements.endercentral.eu "Javadoc"