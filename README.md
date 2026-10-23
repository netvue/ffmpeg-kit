# FFmpegKit Next AAR

JitPack wrapper repository for the prebuilt Android AAR.

## Publish

1. Push this directory as a standalone GitHub repository.
2. Create a Git tag, for example `8.1.1`.
3. Request a build from JitPack.

Use the dependency with JitPack coordinates:

```kotlin
repositories {
    maven("https://jitpack.io")
}

dependencies {
    implementation("com.github.<github-user>:<repository>:8.1.1")
}
```

The published artifact includes the runtime dependency `com.arthenica:smart-exception-java:0.2.1`.
