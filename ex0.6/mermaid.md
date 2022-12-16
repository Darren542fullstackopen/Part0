```mermaid
sequenceDiagram;
browser->>server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa;
server-->>browser: Status 201 {"message":"note created"};

note over browser: browser executes the event handler <br> that renders notes to display;
