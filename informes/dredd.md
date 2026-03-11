WARNING: A restricted method in java.lang.System has been called
WARNING: java.lang.System::load has been called by net.rubygrapefruit.platform.internal.NativeLibraryLoader in an unnamed module (file:/C:/Users/K1000/.gradle/wrapper/dists/gradle-9.3.1-bin/23ovyewtku6u96viwx3xl3oks/gradle-9.3.1/lib/native-platform-0.22-milestone-29.jar)
WARNING: Use --enable-native-access=ALL-UNNAMED to avoid a warning for callers in this module
WARNING: Restricted methods will be blocked in a future release unless native access is enabled


Welcome to Gradle 9.3.1!

Here are the highlights of this release:
- Test reporting improvements
- Error and warning improvements
- Build authoring improvements

For more details see https://docs.gradle.org/9.3.1/release-notes.html


> Task :checkstyleMain
[ant:checkstyle] [ERROR] D:\K1000\Carrera (ing. en computaci├│n)\Materias\Programaci├│n 2\Proyectos IDEA\tp1-2026-KaamilDebernardis\src\main\java\ar\unrn\DesordenadoApp.java:4:5: [0x1001] Falta documentaci├│n Javadoc para el atributo [JavadocVariable]
[ant:checkstyle] [ERROR] D:\K1000\Carrera (ing. en computaci├│n)\Materias\Programaci├│n 2\Proyectos IDEA\tp1-2026-KaamilDebernardis\src\main\java\ar\unrn\DesordenadoApp.java:6:5: [0x1001] Falta documentaci├│n Javadoc para el m├®todo [MissingJavadocMethod]
[ant:checkstyle] [ERROR] D:\K1000\Carrera (ing. en computaci├│n)\Materias\Programaci├│n 2\Proyectos IDEA\tp1-2026-KaamilDebernardis\src\main\java\ar\unrn\DesordenadoApp.java:13:5: [0x1001] Falta documentaci├│n Javadoc para el m├®todo [MissingJavadocMethod]
[ant:checkstyle] [ERROR] D:\K1000\Carrera (ing. en computaci├│n)\Materias\Programaci├│n 2\Proyectos IDEA\tp1-2026-KaamilDebernardis\src\main\java\ar\unrn\HolaApp.java:7:5: [0x1001] Falta documentaci├│n Javadoc para el m├®todo [MissingJavadocMethod]

> Task :checkstyleMain FAILED

[Incubating] Problems report is available at: file:///D:/K1000/Carrera%20(ing.%20en%20computaci%C3%B3n)/Materias/Programaci%C3%B3n%202/Proyectos%20IDEA/tp1-2026-KaamilDebernardis/build/reports/problems/problems-report.html

FAILURE: Build failed with an exception.

* What went wrong:
  Execution failed for task ':checkstyleMain'.
> A failure occurred while executing org.gradle.api.plugins.quality.internal.CheckstyleAction
> Checkstyle rule violations were found. See the report at: file:///D:/K1000/Carrera%20(ing.%20en%20computaci%C3%B3n)/Materias/Programaci%C3%B3n%202/Proyectos%20IDEA/tp1-2026-KaamilDebernardis/build/reports/checkstyle/main.html
Checkstyle files with violations: 2
Checkstyle violations by severity: [error:4]


* Try:
> Run with --scan to get full insights from a Build Scan (powered by Develocity).

Deprecated Gradle features were used in this build, making it incompatible with Gradle 10.

You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

For more on this, please refer to https://docs.gradle.org/9.3.1/userguide/command_line_interface.html#sec:command_line_warnings in the Gradle documentation.

BUILD FAILED in 16s
3 actionable tasks: 2 executed, 1 up-to-date