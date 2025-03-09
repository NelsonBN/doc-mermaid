# Documentation - Mermaid - Flowcharts - Directions
[[Flowcharts]](./README.md) | [[Home]](/README.md)

You can specify different directions for your flowcharts:



## Top-Down (TD/TB)
This is the default direction. You can use either `TD` (top-down) or `TB` (top to bottom) - they're equivalent.

```mermaid
flowchart TD
  A[Top] --> B[Middle]
  B --> C[Bottom]
```

You can also omit the direction entirely for top-down flowcharts:

```mermaid
flowchart
  A[Top] --> B[Middle]
  B --> C[Bottom]
```



## Bottom-Up (BT)
```mermaid
flowchart BT
  A[Bottom] --> B[Middle]
  B --> C[Top]
```



## Left to Right (LR)
```mermaid
flowchart LR
  A[Left] --> B[Middle]
  B --> C[Right]
```



## Right to Left (RL)
```mermaid
flowchart RL
  A[Right] --> B[Middle]
  B --> C[Left]
```
