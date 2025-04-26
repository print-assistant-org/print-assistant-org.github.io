---
layout: mermaid
title: test-mermaid
---

```mermaid
classDiagram
    class IPrinter{
        <<interface>>
    }

    class Printer{
    }
    IPrinter <|..  Printer

    class printer_config{
        +Printer printer
        +File file
    }
    printer_config --> Printer

    class printing_model{
        +File file
    }
```
