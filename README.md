# Applitools Example: Selenium Java Basic with the Classic runner

This is the example project for the [Selenium Java Basic tutorial](https://applitools.com/tutorials/quickstart/web/selenium/java/basic).
It shows how to start automating visual tests
with [Applitools Eyes](https://applitools.com/platform/eyes/)
using [Selenium WebDriver](https://www.selenium.dev/) in Java.

It uses:

* [Java](https://www.java.com/) as the programming language
* [Selenium WebDriver](https://www.selenium.dev/) for browser automation
* [Google Chrome](https://www.google.com/chrome/downloads/) as the local browser for testing
* [Apache Maven](https://maven.apache.org/index.html) for dependency management
* [Applitools Eyes](https://applitools.com/platform/eyes/) for visual testing

To run this example project, you'll need:

1. An [Applitools account](https://auth.applitools.com/users/register), which you can register for free.
2. The [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/), version 8 or higher.
3. A good Java editor, such as [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/).
4. [Apache Maven](https://maven.apache.org/download.cgi) (typically bundled with IDEs).
5. An up-to-date version of [Google Chrome](https://www.google.com/chrome/downloads/).
6. A corresponding version of [ChromeDriver](https://chromedriver.chromium.org/downloads).

The main test case is [`AcmeBankTests.java`](src/test/java/com/applitools/example/AcmeBankTests.java).

To execute tests, set the `APPLITOOLS_API_KEY` environment variable
to your [account's API key](https://applitools.com/tutorials/guides/getting-started/registering-an-account).
You can launch the test from your IDE,
or you can run it from the command line with Maven like this:

```
mvn exec:exec@run-the-tests -Dexec.classpathScope=test
```

**For full instructions on running this project, take our
[Selenium Java Basic tutorial](https://applitools.com/tutorials/quickstart/web/selenium/java/basic)!**
