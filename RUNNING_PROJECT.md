FocusGuard run notes

VS Code:
1. Open this folder: Rehab semester project oop.
2. Run "Java: Clean Java Language Server Workspace" from the command palette.
3. Choose Reload and reopen the folder if VS Code asks.
4. Open Run and Debug, then choose "Run FocusGuard".

Terminal:
Run:

    bash build.sh
    bash run.sh

IntelliJ IDEA:
1. Open this folder as a project.
2. If IntelliJ asks, import it as Maven project.
3. Use main class: com.focusguard.app.MainApp.
4. VM options:

    --module-path /usr/share/openjfx/lib --add-modules javafx.controls

If imports are red, make sure OpenJFX is installed and this path exists:

    /usr/share/openjfx/lib
