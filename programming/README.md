### Information Storage: Variables, Constants, & Memory

Before a program can process anything, it must have a way to hold onto data.

- **Variables (Mutable Storage):** Temporary, named containers in the computer’s short-term memory (RAM). The values stored inside can change as the program runs (e.g., a player's score updating during a game).
- **Constants (Immutable Storage):** Named containers for values that are strictly set at the beginning and are forbidden from changing while the program runs (e.g., the value of Pi, a maximum speed limit, or an API server URL).
- **Declaration & Initialization:**
    - _Declaration:_ Telling the computer to reserve a spot in memory and give it a name.
    - _Initialization:_ Assigning the very first value to that reserved spot.
- **Memory References & Addresses:** How the computer assigns a unique physical hexadecimal address to every variable, allowing the program to locate where that specific data lives.


### Data Classification: Data Types & Type Systems

Computers treat a sequence of ones and zeros differently depending on its data type. A data type tells the system exactly how much memory to allocate and what operations are legally allowed on that data.

Primitive (Basic) Data Types

- **Integers:** Whole numbers without fractions or decimals (can be positive, negative, or zero).
- **Floating-Point Numbers (Floats/Doubles):**

  Numbers that contain decimal points or fractional parts (used for precise measurements, money, or scientific data).
- **Characters:** A single letter, digit, punctuation mark, or blank space enclosed as a single unit of text.
- **Booleans:** The simplest data type representing binary logic: either `True` or `False`.

Composite (Complex) Data Types

- **Strings:** A sequential chain of multiple characters linked together to form words, sentences, or paragraphs.
- **Null / Void / Undefined:** Special states used to represent the total absence of a value or an uninitialized variable.

Type Behaviors

- **Static vs. Dynamic Typing:** Whether a variable is permanently locked into one data type when created, or if it can change types freely later on.
- **Type Casting (Coercion):** The process of converting data from one type to another (e.g., turning the text string `"42"` into the actual mathematical integer `42`).

### Data Manipulation: Operators & Expressions

Operators are the action symbols that allow you to combine, compare, transform, and evaluate variables and values.

- **Arithmetic Operators:** The tools of standard math used to calculate values:
  - Addition (`+`) and Subtraction (`-`)
  - Multiplication (`*`) and Division (`/`)
  - Modulus (`%`): Finds the remaining remainder left over after dividing one whole number by another.
- **Assignment Operators:** The mechanisms used to store a calculated value into a variable (e.g., `=`, `+=`).

- **Comparison (Relational) Operators:** Evaluates the relationship between two values and always outputs a `True` or `False` boolean:
  - Equality (`==`) and Inequality (`!=`)
  - Greater than (`>`) and Less than (`<`)
  - Greater than or equal to (`>=`) and Less than or equal to (`<=`)
- **Logical Operators:** Used to combine multiple boolean conditions together to make complex decisions:
  - `AND`: Requires _every single_ condition to be true.
  - `OR`: Requires _at least one_ condition to be true.
  - `NOT`: Inverts the logic completely (turns true to false, and vice versa).
- **Operator Precedence:** The strict mathematical order of operations determining which calculations are executed first (e.g., multiplication happening before addition).