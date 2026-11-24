# Gradle Compatibility Timeline

Every point since Gradle 2.0 where Java or Kotlin support changed, newest first:

- **Running Gradle**: which Java versions can run Gradle, and the newest Java usable as a toolchain
- **Build scripts**: the Kotlin version embedded in Gradle for `.gradle.kts` scripts
- **Your code**: the newest Kotlin Gradle Plugin (KGP) supported for that Gradle version

Live page: https://helpermethod.github.io/gradle-compatibility/

Data comes from the [Gradle compatibility matrix](https://docs.gradle.org/current/userguide/compatibility.html) and the [Kotlin Gradle plugin docs](https://kotlinlang.org/docs/gradle-configure-project.html). The whole page is the single file `index.html`; the source data lives in the arrays at the top of its script.
