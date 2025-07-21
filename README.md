# Football
```mermaid
flowchart TD
    A([Start Application]) --> B{Are you at least 18 years old?}
    B -- No --> Z([Not Eligible])
    B -- Yes --> C{Do you have a valid Singapore driving license?}
    C -- No --> Z
    C -- Yes --> D{Did you pass the medical check-up?}
    D -- No --> Z
    D -- Yes --> E{Do you have a clean driving record?}
    E -- No --> Z
    E -- Yes --> F{Can you pass the background check?}
    F -- No --> Z
    F -- Yes --> G([Eligible to Apply])
