# Functions/procedures

### **Why Functions Exist**

**Functions exist to bundle a block of code together so it can be reused, organized, and simplified.** Instead of writing the same ten lines of code in multiple places, you write them once, give them a name, and reuse that name whenever needed.

### **Inputs**

**Inputs are the raw data pieces passed into a function so it can do its job.** They provide the external context the function needs to perform its calculation or action.

- _Analogy:_ Dropping fruit and yogurt into a blender to make a smoothie.

### **Outputs**

**Outputs are the results or changes produced by a function after it runs.** This can be a new piece of data sent back to the system, or a direct change made to the system's state.

### **Parameters vs. Arguments**

While often used interchangeably, they represent two sides of the same coin:

- **Parameters:** The **placeholder names** defined inside the function's blueprint. They declare what _kind_ of data the function expects.
- **Arguments:** The **actual, concrete values** you pass into those placeholders when you run the function.

|Term|What it is|Example|
|---|---|---|
|**Parameter**|The blueprint placeholder.|`box_width`, `box_height`|
|**Argument**|The real value used.|`5`, `10`|

### **Return Values**

**A return value is the specific piece of data a function hands back to the spot where it was called once it finishes.** Returning a value instantly exits the function.

- _Example:_ A function named `Add` takes `2` and `3` as arguments and sends back `5` as its return value.

### **Local State**

**Local state consists of the temporary variables created inside a function while it is executing.** This data only exists to help the function finish its current task and is completely wiped out once the function stops running.

### **Function Scope**

**Function scope is the privacy boundary around a function.** Any variables declared inside the function are completely invisible to the rest of the system outside. This prevents different parts of a program from accidentally messing with each other's data.

### **Calling a Function**

**Calling a function means telling the system to pause what it is currently doing, jump to that function's code, and execute it.** You "call" it by using its name and passing in any required arguments.

### **Call Stack**

**The call stack is the system's internal tracking mechanism for keeping track of active functions.** It works like a stack of dinner plates: when Function A calls Function B, B is placed on top of the stack. When B finishes, it is popped off the stack, and the system resumes exactly where it left off in Function A.

### **Composition**

**Composition is the practice of combining simple, small functions together to build more complex workflows.** You take the output of one function and immediately feed it as the input into another.

- _Example:_ `CalculateTax(CalculateTotal(ShoppingBag))` passes the bag's total price directly into the tax calculator.
