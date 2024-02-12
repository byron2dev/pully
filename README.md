# pully

Used to explore pull request submits and merges.

This line was added by byerun on branch feature1.

2024-01-22-11-10 Making this change on branch4 if that's okay.

![image](image.png)

## Diagrams

```mermaid
flowchart LR
    subgraph subgraph1
        direction TB
        top1[top] --> bottom1[bottom]
    end
    subgraph subgraph2
        direction TB
        top2[top] --> bottom2[bottom]
    end
    %% ^ These subgraphs are identical, except for the links to them:

    %% Link *to* subgraph1: subgraph1 direction is maintained
    outside --> subgraph1
    %% Link *within* subgraph2:
    %% subgraph2 inherits the direction of the top-level graph (LR)
    outside ---> top2
```

PlantUML diagrams not support on GitHub as of 2024-02-02
```plantuml
@startuml

Student -o Room
Chair --* Room

@enduml
```
Time 2024-02-12-12-25
 
