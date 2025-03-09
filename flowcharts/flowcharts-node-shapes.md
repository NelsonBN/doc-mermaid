# Documentation - Mermaid - Flowcharts - Node Shapes
[[Flowcharts]](./README.md) | [[Home]](/README.md)

Flowcharts can have nodes with various shapes:



## Basic Shapes

### Rectangle
```mermaid
flowchart LR
  A[A] --- B[B]
```

### Rounded Rectangle
```mermaid
flowchart LR
  A(A) --- B(B)
```

### Circle
```mermaid
flowchart LR
  A((A)) --- B((B))
```

### Double Circle
```mermaid
flowchart LR
  A(((A))) --- B(((B)))
```



## Special Purpose Shapes

### Stadium shape
```mermaid
flowchart LR
  A([A]) --- B([B])
```

### Subroutine
```mermaid
flowchart LR
  A[[A]] --- B[[B]]
```

### Database
```mermaid
flowchart LR
  A[(A)] --- B[(B)]
```



## Decision Shapes

### Diamond/Decision
```mermaid
flowchart LR
  A{A} --- B{B}
```

### Hexagon
```mermaid
flowchart LR
  A{{A}} --- B{{B}}
```



## Directional Shapes

### Asymmetric
```mermaid
flowchart LR
  A>A] --- B>B]
```

### Parallelogram
```mermaid
flowchart LR
  A[/A/] --- B[/B/]
```

### Parallelogram Alternative
```mermaid
flowchart LR
  A[\A\] --- B[\B\]
```

### Trapezoid
```mermaid
flowchart LR
  A[/A\] --- B[/B\]
```

### Trapezoid Alternative
```mermaid
flowchart LR
  A[\A/] --- B[\B/]
```
