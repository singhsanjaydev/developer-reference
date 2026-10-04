# Control flow

This is one of the most fundamental programming ideas.

### **Sequential Execution**

**Sequential execution is the default mode where a system runs instructions in order, from top to bottom, one after another.** It follows the list of commands exactly like a cooking recipe, never skipping a line unless explicitly told to do so.

### **Conditions**

**A condition is a true-or-false question that the system evaluates to make a decision.** It acts as a gatekeeper, checking the current state of data before allowing the system to proceed down a specific path.

- _Example:_ Checking if `user_age >= 18` to decide if access should be granted.

### **Branching**

**Branching occurs when a condition causes the system to split into different paths, executing one set of instructions while completely skipping another.** It creates "if-then-else" scenarios.

- _Example:_ **If** it is raining, take an umbrella; **else** (otherwise), wear sunglasses. The system only chooses one path.

### **Repetition**

**Repetition is the concept of running the exact same block of instructions multiple times.** Instead of writing out the same commands over and over, you tell the system to reuse them until a specific goal is reached.

### **Loops**

**Loops are the structural tools used to achieve repetition.** They keep executing a block of code as long as their controlling condition remains true.

- **Count-controlled loop:** Repeats a specific number of times (e.g., "Repeat 10 times").
- **Condition-controlled loop:** Repeats until a state changes (e.g., "Repeat while the battery is not full").

### **Early Exit**

**An early exit is breaking out of a loop or a sequence before it naturally finishes its planned run.** This happens when a specific condition is met mid-way, making the rest of the repetitions unnecessary.

- _Analogy:_ Searching a deck of cards for the Ace of Spades. Once you find it on the third card, you stop looking and put the deck down early.

### **Nested Control Flow**

**Nested control flow is placing one control structure inside another control structure.** This allows you to handle complex logic by stacking decisions or repetitions.

- _Example:_ Putting a _branch_ inside a _loop_ (e.g., looping through a list of numbers, and **if** a number is even, printing it).

### **Control-Flow Graphs**

**A control-flow graph is a visual map showing all possible paths a system can take during execution.** It uses boxes to represent blocks of code and arrows to show how the system moves between decisions, loops, and jumps.
