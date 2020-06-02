# digilib-frontend-metadata

Customized digilib frontend with metadata display. Initial version by Gordon Fischer of BBAW.

## How to build and run digilib (using Java)

Requirements:
* [git](https://git-scm.com/)
* [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) version 8 or later
* [Maven](https://maven.apache.org/) version 3 or later

```
git clone https://github.com/robcast/digilib-frontend-metadata.git
cd digilib-frontend-template
mvn jetty:run-exploded
```
Then open http://localhost:8080/digilib/digilib.html?fn=17Juni.jpg&Juni17.json in your browser.

Please see the [configuration instructions](https://robcast.github.io/digilib/digilib-config.html)
and the full [build and install documentation](https://robcast.github.io/digilib/build-maven.html).
