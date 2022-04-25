# Welcome to Beast API Documentation

Welcome to the documentation of the BEAST API project! 




## Getting Started

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout
    src/
        main/
            scala/
                StartApp.scala  # Main function and entry point to the server.
                actors  # Contains all the actors
                    Routes.scala       # ScalaDSL routing logic.
                    FileRegistry.scala  # Helper object for the HTTP routing Actor
                    HdfsActor.scala     # Actor for indexing and partitioning of data using BEAST 
                    TileActor.scala     # Actor for rendering tiles on the fly using index 
                models
                    DataFileDAL.scala   # Relational Mapping for H2 metadata database
                    DataFileDAO.scala
                Utils
                    JsonFormats.scala
        resources/
            application.conf #Configuration File for the server
    pom.xml # Maven dependencies  
## Additional Documentation