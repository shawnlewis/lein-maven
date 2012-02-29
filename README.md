# lein-mvn

A lein2 plugin for working with maven poms.

## Install

```clojure
:plugins [[lein-mvn "0.1.0-SNAPSHOT"]]
```
## Usage

To generate a project.clj from a pom, lein2 mvn in the directory with the pom file.

To use maven based project checkouts, add

```clojure
:middleware [leiningen.mvn/maven-checkouts]
```

## License

Copyright © 2012 Hugo Duncan

Distributed under the Eclipse Public License.