[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

# awesome-java-modules
A curated list of resources related to the Java Module System ([JSR 376](https://www.jcp.org/en/jsr/detail?id=376))


## Contents

- [Official Links](#official-links)
- [Articles](#articles)
- [Blogs](#blogs)
- [Talks](#talks)
- [Literature](#literature)
- [Courses](#courses)
- [Tools](#tools)


## Official Links
- [Module Declarations](https://docs.oracle.com/javase/specs/jls/se9/html/jls-7.html#jls-7.7) - Java Language Specification for Modules
- [Project Jigsaw](https://openjdk.org/projects/jigsaw) - Lists primary goals + _Key documents, presentations, & other resources_
- [Module System Quick-Start Guide](https://openjdk.org/projects/jigsaw/quick-start) - Provides a few simple examples to get developers started with modules
- [JEP 511: Module Import Declarations](https://openjdk.org/jeps/511) - ... the ability to succinctly import all of the packages exported by a module


## Articles

### Basics
- [Java Modules on Maven Central](https://github.com/sormuras/modules) - Unique module names database of artifacts published on Maven Central
- [Code-First Java Module System Tutorial](https://blog.codefx.org/java/java-module-system-tutorial/)
- [Modules vs. Microservices](https://www.oreilly.com/ideas/modules-vs-microservices)
- [Java Modules Cheat Sheet](https://github.com/tfesenko/Java-Modules-JPMS-CheatSheet)


### Advanced
- [Automatic-Module-Name: Calling all Java Library Maintainers](http://branchandbound.net/blog/java/2017/12/automatic-module-name/)
- [Optional Dependencies with `requires static`](https://blog.codefx.org/java/module-system-optional-dependencies/)
- [Implied Readability With `requires transitive`](https://blog.codefx.org/java/implied-readability/)
- [Five Command Line Options To Hack The Java Module System](https://blog.codefx.org/java/five-command-line-options-hack-java-module-system/)


## Blogs
- [nipafx.dev](https://nipafx.dev/#channels~~articles~~~tags~~j_ms) - tag: `j_ms`
- [joda.org](https://blog.joda.org/search/label/modules) - label: `modules`


## Talks
- [Keeping Up with Java](https://www.youtube.com/watch?v=cF-rUNCOm2c) Sander Mak at GOTO Berlin 2018
- [Java Modularity: the Year After](https://www.youtube.com/watch?v=l4Dk7EF-oYc) Sander Mak at Devoxx BE 2018
- [Modules or Microservices?](https://www.youtube.com/watch?v=AJW2FAJGgVw) - Sander Mak at Devoxx PL 2018
- [Modules in One Lesson](https://www.youtube.com/watch?v=MGX-JfMl9-Y) - Mark Reinhold at JavaOne 2017
- [Modules and Services](https://www.youtube.com/watch?v=u8Hbdo-u-88) - Alex Buckley at JavaOne 2016
 

## Literature
- [The Java Module System](https://www.manning.com/books/the-java-module-system?a_aid=nipa&a_bid=869915cb) (Nicolai Parlog; Manning)
- [Java 9 Modularity](https://javamodularity.com) (Sander Mak & Paul Bakker; O'Reilly)


## Courses
- [Java 9 Modularity: First Look](https://www.pluralsight.com/courses/java-9-modularity-first-look) (Sander Mak; Pluralsight (subscription needed)


## Tools
- [Netflix Java Module System development tool](https://github.com/Netflix/ja) - Java module descriptor as the source of truth throughout development
- [Java Module Dependencies Gradle plugin](https://github.com/gradlex-org/java-module-dependencies) - Java modules as first-class dependencies for Gradle-based builds
