### Streamy Base Domain Associations Blueprint

```mermaid
classDiagram
    class Title {
        +String name
        +int releaseYear
        +playMedia() Boolean
    }

    class Genre {
        +String genreName
        +getMediaCatalog() List
    }

    Title -- Genre : categorized_under     
    