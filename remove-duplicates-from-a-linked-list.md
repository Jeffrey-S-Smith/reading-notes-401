# remove-duplicates-from-a-linked-list

## Problem Domain

Make a function that removes duplicates values from a linked list.

## EXAMPLE DATA

Head starts at 4

## input: 4 --> 3 --> 12 --> 3 --> 16 --> 9 --> 9

## output: 4 --> 3 --> 12 --> 16 --> 9

```mermaid
graph LR
                
    Head --> A[4] --> B[3]
    B --> C[12]
    C --> D[3]
    D --> E[16]
    E --> F[9]
    F --> G[9] --> Tail
   
```

### Removes duplicates

```mermaid
    graph LR
    A[4] --> B[3]
    B --> C[12]
    C --> D[3] --> Remove
    D --> E[16]
    E --> F[9]
    F --> G[9] --> Remove
    G --> H[null]
```

### What is current

```mermaid
    graph LR
  current --> A[4] --> B[3]
    B --> C[12]
    C --> D[3] 
    D --> E[16]
    E --> F[9]
    F --> G[9] 
    G --> H[null]
```

### What is current & current.next

```mermaid
    graph LR
  current --> A[4] --> B[3]
  current.next --> B --> C[12]
    C --> D[3] 
    D --> E[16]
    E --> F[9]
    F --> G[9] 
    G --> H[null]
```




```