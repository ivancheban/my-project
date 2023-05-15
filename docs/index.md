# Introduction

This is Ivan Cheban's test MkDocs site. This is version 0.1.

!!! note

    This is work in progress.

![img](img/download-vscode.png)


## Tabs

=== "Windows"
    Markdown **content**.

    Multiple paragraphs.

=== "Linux"
    More Markdown **content**.

    - list item a
    - list item b

## Code blocks

```json
{
  "name": "Ivan",
  "last name": "Cheban",
  "age": 42
}
```

## Flow charts

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

## ERD diagrams

``` mermaid
erDiagram
  CUSTOMER ||--o{ ORDER : places
  ORDER ||--|{ LINE-ITEM : contains
  LINE-ITEM {
    string name
    int pricePerUnit
  }
  CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

## Sequence diagrams

``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```
