# Data Models

```mermaid
classDiagram
    Podcast *-- Value
    Podcast "1" *-- "1..*" Episode
    Episode *-- Value
    Value "1" *-- "1..*" ValueRecipient

    class Value {
        +string method = amp or keysend
        +number suggested
    }

    class ValueRecipient {
        +string name
        +string type = node
        +string customKey
        +string customValue
        +number split
        +boolean fee
    }
```