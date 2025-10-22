# Modular Media Streaming Suite (Structural Patterns)

This project is a small Java reference implementation demonstrating structural design patterns applied to a modular media streaming suite (Bridge, Adapter, Decorator, Composite, Proxy). It simulates playback via console output.

## How to run (VS Code)

1. Open this folder in Visual Studio Code.
2. Install the *Java Extension Pack* if prompted.
3. Run the configuration "Run Modular Media Suite" (Run ▶) or press **Ctrl+F5** while `Demo.java` is open.

## How to run (command-line)

From repository root:

```bash
mkdir -p out
javac -d out $(find src/main/java -name "*.java")
java -cp out com.example.media.Demo
```

(On Windows PowerShell, use an IDE or compile files via your editor if `find` is not available.)
