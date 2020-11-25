# Technici4n-maven
My own Maven, when Jitpack is not enough.

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
```
