```mermaid
gantt
    title Gantt Diagram
    dateFormat  YYYY-MM-DD

    .grid .tick {
    stroke: lightgrey;
     opacity: 0.3;
    shape-rendering: crispEdges;
}

    section Section
    A task           :a1, 2024-01-01, 30d
    section Another
    Task in sec      :2024-01-12  , 12d
    section project
    UI design        :2024-01-01, 365d

```