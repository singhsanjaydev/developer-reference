# Variables and state

### **Naming Information**

**Naming information is giving a specific memory label (an identifier) to a piece of data** so you can easily find and use it later. Instead of remembering exactly where data is physically stored, you give it a human-readable name.

- _Analogy:_ Labeling a cardboard box "Winter Clothes" so you know what is inside without opening it.

### **Storing Information**

**Storing is the act of putting a value into a named memory slot.** When you store data, you are saving a specific piece of information under the label you created, ready to be retrieved later.

- _Analogy:_ Placing a winter coat inside the "Winter Clothes" box.

### **Reading Information**

**Reading is looking up and using the value currently saved inside a named slot** without changing or destroying it. You simply check what is inside.

- _Analogy:_ Opening the "Winter Clothes" box to see what coat you have, then closing it back up.

### **Changing State**

**Changing state means replacing the old value in a memory slot with a brand-new value.** Because the system's "snapshot" relies on these stored values, updating even one value changes the overall state.

- _Analogy:_ Taking the coat out of the box and putting a heavy blanket in its place. The label stays the same, but the contents have changed.

### **Scope and Lifetime**

- **Scope (Where it lives):** The specific area of a system where a named value is visible and can be used. If a value is created inside a small, closed box, parts of the system outside that box cannot see or use it.
- **Lifetime (How long it lives):** The duration of time a value actually exists in memory. It starts when the value is created and ends when the system permanently deletes it to free up space.

### **References vs. Copies**

When you pass information around a system, it happens in one of two ways:

- **Copies:** You make an exact duplicate of the value. If you change the duplicate, the original remains completely untouched.
- **References:** You share a pointer or address to the _exact same_ memory slot. If you use a reference to change the value, anyone else looking at that same slot will see the change.

|Action|What happens?|Changing the new one...|
|---|---|---|
|**Copy**|Makes a brand-new clone.|Does **not** affect the original.|
|**Reference**|Shares a map/link to the original.|**Does** change the original.|
