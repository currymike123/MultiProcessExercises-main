# MultiProcess Exercises

Exercises are in their respective packages.

If your version of Eclipse uses a different, incompatible version of JUnit:

- You can tell this happened if when you try to run a test, it crashes with `NoMethodDef`, `ClassNotFound` or similar error
- You can fix this by changing the version of JUnit in build.gradle to the version Eclipse wants, and then re-running `./gradlew eclipse` (or equivalent for your OS) from the repository folder on the command line
- You can find the version of JUnit that Eclipse wants by right-clicking on the project, navigating to Build Path > Add Library, select JUnit, and see what version it lists. **Do not add the Library, that can break things**. If you only see an option for 'Configure Build Path', select that, go to the Libraries tab, click on `Classpath` to un-grey-out the buttons, and then select 'Add Library'
