sequenceDiagram
    participant A as Car
    participant B as Engine
    A->>B: Do we need gas?
    alt Yes
        B-->>A: I am almost empty.
    else No
        B->A: I am full.
    end
