```mermaid
    graph TD
        A[Start Agent Step] --> B{Generate Random Number (0-1)};
        B --o|Less Than Purchase Probability|o--> C{Increment Model's Total Purchases};
        B --o|Greater Than or Equal To Purchase Probability|o--> D[End Agent Step];
        C --> D;