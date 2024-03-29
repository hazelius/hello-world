## リンクされた文書
- 1
- 2


```mermaid
classDiagram
    classA -- classB
    classC *-- classD
    classE o-- classF
    classG <-- classH
    classI -- classJ
    classK <.. classL
    classM <|.. classN
    classO .. classP
```

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10
section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2              :         des4, after des3, 5d
```

```mermaid
flowchart TD
    classDef blue fill:#66deff,stroke:#000,color:#000,stroke:#66f
    classDef green fill:#6ad98b,stroke:#000,color:#000

subgraph house
    Fa("ふりがな
    Father
    1984"):::green --- G2((marry)):::blue
    Mo(Mother):::green --- G2
end
subgraph house2
    G2 --> Or(fa:fa-ban Root Person)
    Or --- G1((fa:fa-spinner Gen 1)):::blue
    Sp(Spouse fa:fa-camera-retro) --- G1
end
    G2 --> Or2(Root2 Person)
```