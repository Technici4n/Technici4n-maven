# Technici4n-maven
My own Maven, for when Jitpack is not enough.

## api-provider setup

```groovy
repositories {
    maven {
        name = "Technici4n"
        url = "https://raw.githubusercontent.com/Technici4n/Technici4n-maven/master/"
        content {
            includeGroup "net.fabricmc.fabric-api"
        }
    }
}

dependencies {
    modApi "net.fabricmc.fabric-api:fabric-provider-api-v1:${project.api_provider_version}"
    include "net.fabricmc.fabric-api:fabric-provider-api-v1:${project.api_provider_version}"
}
```
In `gradle.properties`:
```properties
api_provider_version=0.3.0+58a1cb0d3a 
```

## FTL setup
Check [FTL's repository](https://github.com/Technici4n/FastTransferLib).
