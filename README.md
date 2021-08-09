I have complete this project as per requirements.Basically,in this project build.sbt contains three library dependencies and that are  akka-actor-typed, akka-persistence-typed, scalactic and  also contains three  test dependencies scalatest, akka-actor-testkit-typed and akka-persistence-testkit.

The plugin.sbt contains two plugins codesquad-sbt-plugin and scalastyle-sbt-plugin.


The process which I follow to complete this project  as below


- Create a module namely, actor.

- Add library dependencies for akka-actor-typed, akka-persistence-typed and scalactic

- In the same module, add test dependencies for scalatest, akka-actor-testkit-typed and akka-persistence-testkit.

- Add another module namely, persistence.

- In the persistence module, add library dependency for slick and mysql database.

- Add test dependency for scalatest and h2 database.

- Add plugins to the project- codesquad-sbt-plugin and scalastyle-sbt-plugin

- Finally add one last module "root" and aggregate all other modules in this root module
