This is a Kotlin Multiplatform project targeting Android, Web, Desktop.

You can open the web application by running the `:composeApp:wasmJsBrowserDevelopmentRun` Gradle task.

### Run app via CLI
```
Run desktop app:
./gradlew composeApp:run

Run web app:
./gradlew wasmJsBrowserRun -t --quiet
```


### This Gradle task ensures that the yarn.lock file is updated with the latest dependency versions.
```
./gradlew kotlinUpgradeYarnLock
```

