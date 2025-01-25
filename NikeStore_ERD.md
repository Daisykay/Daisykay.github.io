```mermaid
erDiagram
    Athletes }|..|{ Nike : "needs shoes"
    "Sports Enthusiasts" ||--o{ Nike : "needs shoes"
    "Sustainability Advocates" ||--o{ Nike : "needs shoes"
    Nike ||--o{ Online : shopping
    Nike ||--|{ Store : shopping
    Online ||--|{ Athletic : buys
    Online ||--|{ Casual : buys
    Store ||--o{ Athletic : buys
    Store ||--o{ Casual : buys
    Athletic ||--o{ Golf : purchase
    Athletic ||--o{ Pro : purchase
    Athletic ||--o{ Skate : purchase
    Athletic ||--o{ Running : purchase
    Casual ||--o{ Blazers : purchase
    Casual ||--o{ AirForce1 : purchase
    Casual ||--o{ Dunks : purchase
    Casual ||--o{ AirMax : purchase
    Casual ||--o{ Foamposite : purchase
```
