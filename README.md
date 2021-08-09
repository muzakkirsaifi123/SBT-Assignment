- Create a module namely, actor.

- Add library dependencies for akka-actor-typed, akka-persistence-typed and scalactic

- In the same module, add test dependencies for scalatest, akka-actor-testkit-typed and akka-persistence-testkit.

- Add another module namely, persistence.

- In the persistence module, add library dependency for slick and mysql database.

- Add test dependency for scalatest and h2 database.

- Add plugins to the project- codesquad-sbt-plugin and scalastyle-sbt-plugin

- Finally add one last module "root" and aggregate all other modules in this root module