# EXAM FIRST TERM. 🚀

## Escuela Colombiana de Ingeniería - Enterprise Architectures(AREP).

_Spark trigonometric calculator: program used to calculate the sine, cosine and tangent of a number that is in radians._

- Second part: https://github.com/angiedanielar/PARCIAL1.2_AREP

- Third part: https://github.com/angiedanielar/PARCIAL1.3_AREP

## Getting Started

### Prerequisites

- [Maven](https://maven.apache.org/) - Dependency Management.

- [Java 8](https://www.oracle.com/co/java/technologies/javase/javase-jdk8-downloads.html) -  Development Environment.

- [Git](https://git-scm.com/) - Version Control System.

- [Spark](http://sparkjava.com/) - Micro framework for creating web applications in Java 8.

Make sure you have this programs installed correctly and the version that we need with the following commands:

```
mvn --version
```

```
git --version
```

```
java -showversion
```

### Installing

1. Clone the repository:

```
git clone https://github.com/angiedanielar/PARCIAL1_AREP
```

2. Compile the projet:

```
mvn package
```

3. Executing the program:

```
mvn exec:java -D "exec.mainClass"="com.mycompany.app.App"

And put this link in your browser: http://localhost:4567
```

- [Link to the deploy](https://parcialarep.herokuapp.com)


_Example to use: https://parcialarep.herokuapp.com/calculator/calculate?number=1&operation=cos


4. Generating the documentation:

```
mvn javadoc:javadoc
```

- [View Documentation Ubication](https://angiedanielar.github.io/PARCIAL1_AREP/apidocs)

## Running the unit tests

```
mvn test
```

## Built With

- [Maven](https://maven.apache.org/) - Dependency Management

- [Java 8](https://www.oracle.com/co/java/technologies/javase/javase-jdk8-downloads.html) -  Development Environment.

- [Git](https://git-scm.com/) - Version Control System.

- [CircleCI](https://circleci.com/) [![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/angiedanielar/LAB2_AREP) - Continuous Integration.

- [Spark](http://sparkjava.com/) - Micro framework for creating web applications in Java 8.

- [Heroku](https://www.heroku.com/platform) - Deploy platform.

## Author

- Angie Daniela Ruiz Alfonso.


## License

This project is under GNU General Public License - see the [LICENSE](LICENSE) file for details.

