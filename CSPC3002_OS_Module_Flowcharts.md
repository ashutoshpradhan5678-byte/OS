# CSPC3002 -- Operating Systems

## Complete Module-wise Syllabus Flowcharts

**Course:** CSPC3002 -- Operating Systems (3-0-0)\
**Total teaching hours:** 40

This document organizes every topic and subtopic explicitly listed in
the supplied BPUT syllabus into Mermaid flowcharts. The diagrams can be
viewed directly on GitHub.

------------------------------------------------------------------------

## Module I -- Introduction to Operating Systems (10 hours)

### Syllabus topics

-   **Introduction to OS:** About an OS, Simple batch system,
    Multiprogramming and time-sharing system.
-   **Operating system structure:** Operating system services, System
    components, Protection system, OS service, System call.
-   **Process management:** Process concepts, Process scheduling,
    Operation on process, IPC, Multi-threading models, Threading issues,
    Process scheduling algorithms.

### Flowchart

``` mermaid
flowchart TD
    A["MODULE I: INTRODUCTION TO OS"] --> B["Introduction to OS"]
    A --> C["Operating System Structure"]
    A --> D["Process Management"]

    B --> B1["About an OS"]
    B --> B2["Simple Batch System"]
    B --> B3["Multiprogramming System"]
    B --> B4["Time-Sharing System"]

    C --> C1["Operating System Services"]
    C --> C2["System Components"]
    C --> C3["Protection System"]
    C --> C4["OS Service"]
    C --> C5["System Call"]

    D --> D1["Process Concepts"]
    D --> D2["Process Scheduling"]
    D --> D3["Operation on Process"]
    D --> D4["IPC"]
    D --> D5["Multi-threading Models"]
    D --> D6["Threading Issues"]
    D --> D7["Process Scheduling Algorithms"]
```

------------------------------------------------------------------------

## Module II -- Process Coordination & Synchronization and Deadlocks (10 hours)

### Syllabus topics

-   **Process Coordination & Synchronization:** Critical section
    problem, Peterson's solution, Synchronization hardware, Semaphores,
    Classical problems of synchronization.
-   **Deadlocks:** System model, Deadlock characterization, Methods for
    handling deadlock, Deadlock prevention, Deadlock avoidance, Deadlock
    detection, Recovery from deadlock.

### Flowchart

``` mermaid
flowchart TD
    A["MODULE II"] --> B["Process Coordination & Synchronization"]
    A --> C["Deadlocks"]

    B --> B1["Critical Section Problem"]
    B1 --> B2["Peterson's Solution"]
    B2 --> B3["Synchronization Hardware"]
    B3 --> B4["Semaphores"]
    B4 --> B5["Classical Problems of Synchronization"]

    C --> C1["System Model"]
    C1 --> C2["Deadlock Characterization"]
    C2 --> C3["Methods for Handling Deadlock"]
    C3 --> C4["Deadlock Prevention"]
    C3 --> C5["Deadlock Avoidance"]
    C3 --> C6["Deadlock Detection"]
    C3 --> C7["Recovery from Deadlock"]
```

------------------------------------------------------------------------

## Module III -- Memory Management (08 hours)

### Syllabus topics

-   **Memory management:** Memory management strategies, Logical vs
    Physical address space, Swapping, Contiguous allocation, Paging,
    Segmentation.
-   **Virtual memory:** Background, Demand paging, Page replacement
    algorithm, Allocation of frame, Thrashing, Demand segmentation.

### Flowchart

``` mermaid
flowchart TD
    A["MODULE III: MEMORY MANAGEMENT"] --> B["Memory Management"]
    A --> C["Virtual Memory"]

    B --> B1["Memory Management Strategies"]
    B1 --> B2["Logical vs Physical Address Space"]
    B2 --> B3["Swapping"]
    B3 --> B4["Contiguous Allocation"]
    B4 --> B5["Paging"]
    B5 --> B6["Segmentation"]

    C --> C1["Background"]
    C1 --> C2["Demand Paging"]
    C2 --> C3["Page Replacement Algorithm"]
    C3 --> C4["Allocation of Frame"]
    C4 --> C5["Thrashing"]
    C5 --> C6["Demand Segmentation"]
```

------------------------------------------------------------------------

## Module IV -- Storage Management (08 hours)

### Syllabus topics

-   **File system:** File system concept, Access methods, File system
    structure, Implementation, Efficiency & performance, Recovery.
-   **Storage structure:** Overview of storage structure, Disk
    structure, Disk scheduling, Disk management, Swap space management.
-   **I/O system:** I/O system overview, I/O hardware, Application I/O
    interface, Kernel I/O subsystem, Transforming I/O request to H/W
    operation.

### Flowchart

``` mermaid
flowchart TD
    A["MODULE IV: STORAGE MANAGEMENT"] --> B["File System"]
    A --> C["Storage Structure"]
    A --> D["I/O System"]

    B --> B1["File System Concept"]
    B1 --> B2["Access Methods"]
    B2 --> B3["File System Structure"]
    B3 --> B4["Implementation"]
    B4 --> B5["Efficiency & Performance"]
    B5 --> B6["Recovery"]

    C --> C1["Overview of Storage Structure"]
    C1 --> C2["Disk Structure"]
    C2 --> C3["Disk Scheduling"]
    C3 --> C4["Disk Management"]
    C4 --> C5["Swap Space Management"]

    D --> D1["I/O System Overview"]
    D1 --> D2["I/O Hardware"]
    D2 --> D3["Application I/O Interface"]
    D3 --> D4["Kernel I/O Subsystem"]
    D4 --> D5["Transforming I/O Request to H/W Operation"]
```

------------------------------------------------------------------------

## Module V -- Distributed Systems (04 hours)

### Syllabus topics

-   Distributed file systems
-   Distributed operating systems
-   Real-time systems

### Flowchart

``` mermaid
flowchart TD
    A["MODULE V: DISTRIBUTED SYSTEMS"] --> B["Distributed File Systems"]
    A --> C["Distributed Operating Systems"]
    A --> D["Real-Time Systems"]
```

------------------------------------------------------------------------

## Complete syllabus overview

``` mermaid
flowchart TD
    OS["CSPC3002: OPERATING SYSTEMS"]

    OS --> M1["MODULE I: Introduction to OS"]
    OS --> M2["MODULE II: Synchronization & Deadlocks"]
    OS --> M3["MODULE III: Memory Management"]
    OS --> M4["MODULE IV: Storage Management"]
    OS --> M5["MODULE V: Distributed Systems"]

    M1 --> A1["OS Introduction"]
    M1 --> A2["OS Structure"]
    M1 --> A3["Process Management"]

    M2 --> A4["Process Coordination & Synchronization"]
    M2 --> A5["Deadlocks"]

    M3 --> A6["Memory Management"]
    M3 --> A7["Virtual Memory"]

    M4 --> A8["File System"]
    M4 --> A9["Storage Structure"]
    M4 --> A10["I/O System"]

    M5 --> A11["Distributed File Systems"]
    M5 --> A12["Distributed Operating Systems"]
    M5 --> A13["Real-Time Systems"]
```

------------------------------------------------------------------------

## Course objectives

1.  To provide knowledge about the services rendered by operating
    systems.
2.  To provide a detailed discussion of the various memory management
    techniques.
3.  To discuss the various file-system design and implementation issues.
4.  To discuss how the protection domains help to achieve security in a
    system.

## Course outcomes

-   **CO1:** Ability to comprehend the techniques used to implement the
    process manager.
-   **CO2:** Ability to comprehend virtual memory abstractions in
    operating systems.
-   **CO3:** Ability to design and develop file system interfaces, etc.
-   **CO4:** Ability to comprehend the techniques used to implement the
    process manager.
-   **CO5:** Ability to comprehend virtual memory abstractions in
    operating systems.

## Reference books

1.  Silberschatz, Galvin, Gagne, *Operating System Concepts*, John Wiley
    and Sons, 10th edition.
2.  Stallings, *Operating Systems -- Internals and Design Principles*,
    9th edition, Pearson Publications, 2018.
3.  Andrew S. Tanenbaum, *Modern Operating Systems*, 4th edition,
    Pearson Publications.

------------------------------------------------------------------------

*Prepared from the supplied CSPC3002 Operating Systems syllabus. The
flowcharts preserve the module headings and topic coverage in that
document.*
