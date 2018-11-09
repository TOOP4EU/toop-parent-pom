# toop-parent-pom

Shared Maven parent POM.
The latest version is **1.1.0**.

# How to use it
Include the following code in you pom.xml:

```xml
<parent>
  <groupId>eu.toop</groupId>
  <artifactId>parent-pom</artifactId>
  <version>1.1.0</version>
</parent>
```

## News and noteworthy

* v1.1.0 - 2018-11-09
    * Updated to parent POM 1.10.7
    * No more predefined JUnit
* v1.0.5 - 2018-08-07
    * Removed workaround for JUnit 5 and Surefire
* v1.0.4 - 2018-08-07
    * Updated to parent POM 1.10.3
* v1.0.3 - 2018-03-26
    * Fixed artifactID
    * Updated to parent POM 1.10.3
* v1.0.2 - 2018-03-06
    * Removed explicit dependencyManagement versions
* v1.0.1 - 2018-02-20
    * Initial version
* v1.0.0 - 2018-02-12
    * Initial version
 