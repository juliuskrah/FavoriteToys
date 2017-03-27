# Favorite Toys
A simple Android app demonstrating list of favorite toys

# Quick Start guide
1.    In a command line, navigate to *android_sdk*/tools/ and list the AVDs:

```powershell
emulator -list-avds
```
2.    Next start the emulator:

<pre><code>
emulator -avd <i>avd_name</i>
</code></pre>

3.    Open another command line window and navigate to the root of the project. Invoke the `Gradle Wrapper` included to
      build the APK and immediately install it on a running emulator:

```powershell
gradlew installDebug
```

4.    Explore
