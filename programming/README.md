## Programming

### Fundamentals

- 01 - [Values and information](fundamentals/values-and-information.md)
- 02 - [Variables and state](fundamentals/variables-and-state.md)
- 03 - [Expressions and operations](fundamentals/expressions-and-operations.md)
- 04 - [Control Flow](fundamentals/control-flow.md)
- 05 - [Functions/procedures](fundamentals/functions-procedures.md)

---

## Values and Information

- **Definition of Data:** What data is and how it represents the real world.
- **Concepts of Values:** The concept of an atomic piece of information.
- **Conceptual Value Types:** Categorizing data (Textual, Numeric, Binary) without language syntax.
- **The Concept of State:** The snapshot of all stored information at a given moment.
- **Immutability vs. Mutability:** Fixed constants versus changing values.
- **Representation of Information:** How abstract real-world concepts translate into digital tokens.

## Variables and State

- **Naming Information:** Identifiers, labeling, and assigning meaning to data.
- **Storing Information:** The concept of saving data into an allocated slot.
- **Reading Information:** Retrieving and accessing stored values via their identifiers.
- **Changing State:** Mutating and updating stored values over time.
- **Scope and Lifetime:** Where a variable exists and how long it survives during execution.
- **Value Semantics:** The structural difference between referencing a value versus copying it.

## Expressions and Operations

- **The Mechanics of Evaluation:** How a combination of values reduces down to a single result.
- **Operators:** Core symbols/actions that manipulate data (Arithmetic, Relational, Logical).
- **Combining Values:** Building complex evaluations from simple pieces.
- **Operator Precedence:** The universal rules governing the order of operations.
- **Side Effects:** How evaluating an expression can permanently alter state elsewhere.
- **Expressions vs. Statements:** Code that produces a value versus code that performs an action.

## Control Flow

- **Sequential Execution:** The default top-to-bottom step-by-step path.
- **Conditions & Predicates:** Evaluating true/false criteria to guide program decisions.
- **Branching Logic:** Diverging execution paths based on conditions (If/Else, Multi-way choices).
- **Repetition & Loops:** Automating repetitive tasks until goals are met.
- **Early Exit Mechanisms:** Short-circuiting loop execution or branching before completion.
- **Nested Control Flow:** Embedding decisions and loops inside one another.
- **Control-Flow Graphs:** Mapping the visual branches and pathways a program can take.

## Functions and Procedures

- **The Purpose of Functions:** Why functions exist and how they manage complexity.
- **Inputs & Outputs:** The boundary lines of a function's consumption and production.
- **Parameters vs. Arguments:** Defining expected inputs vs. passing actual values.
- **Return Values:** Explicitly passing a computed result back to the caller.
- **Local State & Function Scope:** Private data isolated inside the execution unit.
- **The Execution Call:** The mechanics of invoking a function.
- **The Call Stack:** How the system tracks active function layers.
- **Composition & Chaining:** Feeding the output of one function directly into another.

## Data Structures

- **The Collection Concept:** The broad theory of grouping individual items together.
- **Sequences & Lists:** Ordered arrangements where position matters.
- **Sets:** Unordered groupings enforced by element uniqueness.
- **Maps & Key-Value Associations:** Storing data as linked pairs (label \(\rightarrow \) value).
- **Stacks:** Last-In, First-Out (LIFO) linear access models.
- **Queues:** First-In, First-Out (FIFO) linear access models.
- **Trees:** Hierarchical parent-child relationships.
- **Graphs:** Networked relationships defined by nodes and connecting edges.
- **Records and Objects:** Structural blueprinted groupings of mixed data types.
- **Structural Trade-offs:** The conceptual reasons for choosing one arrangement over another.

## Algorithms

- **The Algorithm Definition:** What makes a process an algorithm.
- **Algorithmic Decomposition:** Breaking a raw problem down into concrete execution steps.
- **The Input \(\rightarrow \) Processing \(\rightarrow \) Output Lifecycle:** The journey of data through an algorithm.
- **Searching:** Locating specific items within a data structure.
- **Sorting:** Rearranging collections into a predictable order.
- **Traversal:** Visiting every single node or element within a structure.
- **Filtering:** Extracting elements that meet specific criteria.
- **Transformation:** Mapping a set of values into a new set of values.
- **Recursion:** Algorithms that solve problems by calling themselves on smaller subsets.
- **Divide and Conquer:** Splitting a problem down, solving the parts, and combining them.
- **Greedy Thinking:** Making the locally optimal choice at each stage.
- **Dynamic Programming:** Breaking problems down and caching sub-answers to avoid redundant work.

## Problem Decomposition

- **The Scale Dilemma:** Why massive goals (e.g., "Build a website") paralyze development.
- **Functional Dissection:** Splitting a monolithic concept into domain layers (Data \(\rightarrow \) Transform \(\rightarrow \) Output).
- **Atomic Task Refinement:** Continually breaking parts down until a task requires no further sub-steps.

## Abstraction

- **The Meaning of Abstraction:** Managing complexity by hiding unnecessary low-level details.
- **Interfaces & Contracts:** Establishing what an architectural piece does, not how it does it.
- **Responsibilities:** Defining the explicit job of a specific component.
- **Encapsulation:** Shielding internal states and restricting direct external access.
- **Architectural Composition:** Combining simple abstractions to build complex systems.
- **Reusability:** Designing code patterns that solve recurring problems across a system.
- **Coupling & Cohesion:** Minimizing interdependencies while maximizing internal focus.

## Errors and Failure

- **The Fallacy of the Happy Path:** Acknowledging that programs spend significant time failing.
- **Invalid Input & Missing Data:** Structuring code for bad, omitted, or malicious incoming items.
- **Unexpected State:** Defending against the system falling into unhandled configurations.
- **Failure Propagation:** How an unhandled error ripples upward through execution layers.
- **Error Handling & Recovery:** Intercepting faults gracefully to keep the system alive.
- **Validation & Defensive Programming:** Proactively checking data integrity before processing it.
- **Preconditions, Postconditions, and Invariants:** Defining rules for before execution, after execution, and truths that must never change.

## Memory and Execution

- **The Translation Stack:** The conceptual flow from Program \(\rightarrow \) Execution \(\rightarrow \) Instructions \(\rightarrow \) Memory.
- **Memory Anatomy:** How computers track values, call frames, and allocated data structures.
- **Addresses & References:** The concept of pointing to a location rather than holding the item.
- **The Stack vs. The Heap:** Short-term execution frame memory versus long-term dynamic allocation memory.
- **Allocation & Deallocation:** Claiming free space and returning it to the system.
- **Memory Lifetimes:** How long data safely survives in hardware before cleanup.
- **Mutable State Pitfalls:** The dangers of multiple system components modifying shared hardware addresses.

## Complexity

- **Static Reasoning:** Analyzing and evaluating code performance prior to execution.
- **Asymptotic Growth (Big O):** Measuring how resource usage scales as data input size grows (\(N\)).
- **Time Complexity:** The scaling of execution steps (e.g., Constant \(O(1)\), Linear \(O(n)\), Quadratic \(O(n^2)\)).
- **Space Complexity:** The scaling of additional memory hardware required by a process.
- **Case Boundaries:** Analyzing Best Case, Worst Case, and Average Case runtime behaviors.
- **Engineering Trade-offs:** Balancing raw performance speeds against code simplicity.

## Program Architecture

- **Structural Segmentation:** Grouping codebases cleanly (Data \(\rightarrow \) Logic \(\rightarrow \) Interfaces \(\rightarrow \) Infrastructure).
- **Separation of Concerns:** Ensuring distinct features or domains do not overlap.
- **Dependencies & Boundaries:** Managing how software segments communicate with each other.
- **Layering & Composition:** Structuring software in tiers where higher tiers rely on lower ones.
- **Dependency Direction:** Controlling the flow of reliance to keep core logic independent.

## Input and Output (I/O)

- **The Generalized I/O Lifecycle:** The universal chain of Input \(\rightarrow \) Process \(\rightarrow \) State \(\rightarrow \) Process \(\rightarrow \) Output.
- **Architectural Ubiquity:** How this model identically underpins CLIs, Web Backends, Compilers, and Database Engines.

## Systems Thinking

- **The Unified Pipeline:** Connecting Input, Data, State, Logic, Algorithms, and Output into a functional whole.
- **The Structural Hierarchy:** Understanding how Functions build Data Structures, which fuel Algorithms, which organize into Modules, which scale into complete Systems.