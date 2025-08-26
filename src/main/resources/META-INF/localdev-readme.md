idk anything about java build systems

- `./gradlew buildPlugin`
- `./gradlew compileJava`
- `./gradlew runIde`

^^^
The IntelliJ Gradle plugin **automatically downloads** a headless version of IntelliJ 2022.1
- Stored in Gradle cache: `~/.gradle/caches/modules-2/files-2.1/com.jetbrains.intellij.idea/ideaIC/2022.1/`
- This is what `./gradlew runIde` launches
