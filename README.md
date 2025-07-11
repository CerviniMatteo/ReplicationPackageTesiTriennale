# Replication Package for Bachelor’s Thesis in Computer Science

## Thesis Title: Architectural Smell Refactoring in Microservice Projects

This replication package contains:
- A list of analyzed projects with the corresponding number of detected architectural smells: 📄 [Project List](./projects.csv)
- Results from the Arcan tool analysis: 📁 [Arcan Tool Analyses](./Arcan%20tool%20analyses/)

    Which has the following structure:

        Arcan tool analysis/
        ├── cangjingge project/
        │   └── <n>th analysis/
        │       ├── AS[-n].png
        │       └── project-card.png
        ├── grocery-micro-service project/
        │   └── <n>th analysis/
        │       ├── AS[-n].png
        │       └── project-card.png
        ├── microservice-recruit project/
        │   └── <n>th analysis/
        │       ├── AS[-n].png
        │       └── project-card.png

- Results from the Understand tool analysis: 📁 [Understand Tool Analyses](./Understand%20tool%20analyses/)

    Which has the following structure:

        Understand tool analysis/
        ├── cangjingge project/
        │   └── <n>th analysis/
        │       ├── cangjingge[-n].csv
        ├── grocery-micro-service project/
        │   └── <n>th analysis/
        │       ├── grocery-micro-service[-n].csv
        ├── microservice-recruit project/
        │   └── <n>th analysis/
        │       ├── microservice-recruit[-n].csv
- Scripts used to manage Understand tool analysis: 📄 [Script File](./understand_metrics_script.csv)
- Generated diagrams: 📁 [Diagrams](./Diagrams/)

    Which has the following structure:

        Diagrams/
        ├── cangjingge project/
        │   └── <n>th refactoring/
        │   │   ├── depencies-Cangjingge-R[-n].png
        │   └
        ├── grocery-micro-service project/
        │   └── <n>th refactoring/
        │       ├── depencies-GMS-R[-n].png
        |   └── NEW micro service
        │       ├── depencies-GMS-new-MS.png
        ├── microservice-recruit project/
        │   └── <n>th refactoring/
        │       ├── depencies-RC-R[-n].png
