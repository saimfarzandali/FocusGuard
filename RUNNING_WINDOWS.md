# FocusGuard — Windows / IntelliJ IDEA

## Requirements
- Windows 10/11
- JDK 21
- IntelliJ IDEA
- Internet access on the first Maven build (to download JavaFX/Maven dependencies)

## Open in IntelliJ
1. Open the `AntiProcrastinationApp` folder.
2. Let IntelliJ import the Maven project.
3. Set Project SDK to JDK 21.
4. Reload Maven.
5. Run `com.focusguard.app.MainApp`.

## Maven
From the project root:
- Build: `mvn clean package`
- Run: `mvn javafx:run`

JavaFX is downloaded by Maven. No Linux JavaFX path such as `/usr/share/openjfx/lib` is required.

## Data
The application uses local files under `data/`.
