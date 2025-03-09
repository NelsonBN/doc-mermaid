# Documentation - Mermaid - Flowcharts - Arrows
[[Flowcharts]](./README.md) | [[Home]](/README.md)

Flowcharts can have various types of arrows and connections:



## Connection Types

### Undirected Arrow
```mermaid
flowchart LR
  A --- B
```

### Directed Arrow
```mermaid
flowchart LR
  A --> B
```

### Bi-directional
```mermaid
flowchart LR
  A <--> B
```



## Line Styles

### Dotted Line
```mermaid
flowchart LR
  A -.- B
```

### Thick Line
```mermaid
flowchart LR
  A === B
```



## Text Labels

### Line with Text
```mermaid
flowchart LR
  A ---|text| B
```



## Complex Connections

### Multiple Arrows from One Node
```mermaid
flowchart LR
  A --> B
  A --> C
  A --> D
```

### Chained Arrows
```mermaid
flowchart LR
  A --> B --> C --> D
```
