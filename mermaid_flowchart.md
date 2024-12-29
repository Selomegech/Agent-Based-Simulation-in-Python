```mermaid
    graph TD
    A(Start Agent Step) --> B(Generate Random Number (0-1))
    B --> C(Less Than Purchase Probability)
    C --> D(Increment Model's Total Purchases)
    B --> E(Greater Than or Equal To Purchase Probability)
    E --> D(End Agent Step)