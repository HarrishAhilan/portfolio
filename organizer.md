# Personalized CSA Lesson Navigator

**My unicorn:** a personalized navigator for the AP CSA Unit 1-4 lessons. What actually slowed me down wasn't the material, it was digging through nested folders to find the next notebook. Everything lives here in one place now instead of being scattered across `_notebooks/AP_MCQ/...`.

## How to use this

1. Open this file in VS Code.
2. Press **`Cmd+Shift+V`** for Markdown Preview, or click the preview icon in the top-right of the editor.
3. Click a unit's title to expand it, then click any lesson to open its notebook directly.
4. Click a lesson's checkbox in the preview to mark it done. VS Code saves that change back into this file automatically, no need to edit the raw markdown.
5. Click "description" under a lesson for a short recap of what it covers, without reopening the notebook.

### Legend

| Status | Meaning |
|---|---|
| Done | Unit fully complete, every real lesson checked off |
| In progress | Unit partly done |
| Not started | Unit not started |
| Best evidence | Teacher-flagged lesson, from the GitHub Issue |
| Stub | Empty notebook, no assignment, nothing to do |

### Quick Jump

[Unit 1: 7 of 16 done, in progress](#unit-1) &nbsp;·&nbsp; [Unit 2: 0 of 7, not started](#unit-2) &nbsp;·&nbsp; [Unit 3: 0 of 3, not started](#unit-3) &nbsp;·&nbsp; [Unit 4: 0 of 6, not started](#unit-4)

---

<a id="unit-1"></a>
<details open>
<summary><h2>Unit 1: Primitive Types & Objects &nbsp;<code>15 / 16, in progress</code></h2></summary>

- [x] [1.1: Algorithms](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.1-algorithms.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** an unambiguous, ordered set of steps for solving a problem, usually sketched as pseudocode before any real code gets written.

  **Why it matters:** order matters. The exact same steps in a different sequence can produce a broken result, and a compiler's whole job is translating your finished algorithm into something the machine can execute.
  </details>

- [x] [1.2: Variables](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.2-variables.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** named storage for a value of a specific type, declared as `type name = value;`. Putting `final` before the type turns it into a constant that can't be reassigned after its first value.

  **Why it matters:** picking the right primitive type (`int` vs. `double` vs. `boolean`) avoids wasted precision or type mismatches later, and `final` protects values that should never change, like someone's name or a max score.
  </details>

- [ ] [1.3: Output](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.3-output.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-10-19-1.3-output-homework.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** expressions evaluate to a value, and `System.out.print` / `println` push that value to the console. Escape sequences like `\n` and `\t` control spacing without literally starting a new line of code.

  **Why it matters:** this is the plumbing behind everything menu-driven built later in the course; the lesson's `Menu.java` example wires print statements together into an interactive, Scanner-based menu.
  </details>

- [x] [1.4: Input](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.4-input.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** `Scanner` reads typed input from `System.in` using methods like `nextInt()` and `nextLine()`, letting a program react to a value it doesn't already know.

  **Why it matters:** without input, a program can only run on hardcoded data. Scanner is what turns a static program into something a user actually interacts with.
  </details>

- [x] [1.5: Casting](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.5-data_casting.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** converting a value from one type to another. Widening (`int` → `double`) happens automatically and loses nothing; narrowing (`double` → `int`) needs an explicit cast and can truncate or overflow.

  **Why it matters:** integer division and `%` behave differently than expected coming from math class (`7 / 2` is `3`, not `3.5`), and mixed-type expressions get promoted to the wider type before they're evaluated.
  </details>

- [x] [1.6: Compound Operators](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.6-operators-innovators.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** shorthand like `+=`, `-=`, `*=`, `/=`, `%=` that combine an operation and an assignment into one statement instead of writing `x = x + 1`.

  **Why it matters:** this is the standard way real Java code adjusts a counter or running total, and it shows up constantly once loops enter the picture.
  </details>

- [x] [1.7: APIs](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.7-grinders-apis.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.7-grinders-apis-homework.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a library is a collection of prewritten classes; an API is the documentation describing what those classes' attributes (data) and behaviors (methods) do, without needing to read their source.

  **Why it matters:** nearly every useful Java program leans on existing libraries (`Scanner`, `Math`, `ArrayList`) instead of writing everything from scratch. Reading documentation, not memorizing internals, is the actual skill.
  </details>

- [x] [1.8: Documentation](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.8.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** Javadoc comments (`/** ... */`) describe a method's precondition (what it expects) and postcondition (what it guarantees), plus tags like `@param` and `@return`.

  **Why it matters:** it lets someone use a method correctly by reading its contract instead of its implementation, and it's explicitly graded on the AP exam's FRQs.
  </details>

- [ ] [1.9: Method Signatures](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.9-method_signatures-applicators.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.9-Method_Signatures-Homework-applicators.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a method's name plus the number, order, and types of its parameters. Overloading lets multiple methods share a name as long as their signatures differ.

  **Why it matters:** which overload runs is decided at compile time based on the declared argument types, not at runtime, a common source of trick questions.
  </details>

- [ ] [1.10: Class Methods](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.10-class_methods.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.10-class_methods_homework.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a static method belongs to the class itself rather than to any object, called through the class name (`ClassName.method()`), and it can't access instance data directly.

  **Why it matters:** the static-vs-instance distinction is foundational for everything after this. `Math` class methods (1.11) are static for exactly this reason, they don't need an object to work.
  </details>

- [ ] [1.11: Math Class](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.11-math_class.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.11-math_classhw.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a built-in class of static utility methods (`Math.pow`, `Math.sqrt`, `Math.random`, `Math.round`, `Math.floor`), so common math operations don't have to be hand-written.

  **Why it matters:** `Math.random()` returns a double between 0.0 and 1.0, scaling and casting it is the standard pattern for generating a random int in a range, a trick that shows up constantly in game logic.
  </details>

- [ ] [1.12: Classes & Objects](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.12-classes_and_objects.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.12-hw.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a class is the blueprint; an object is one specific instance built from it with `new`. A reference variable doesn't hold the object's data directly, it points to where that object actually lives.

  **Why it matters:** because reference variables point rather than copy, two variables can reference the exact same object, and mutating through one is visible through the other. This is the root of aliasing behavior covered more in 1.13.
  </details>

- [ ] [1.13: Object Creation](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-10-12-1.13-object_creationGrinders.ipynb) (best evidence) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-10-12-1.13-homeworkGrinders.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** `new` allocates an object on the heap, while local primitive variables live on the stack. Passing an object into a method passes its reference, not a fresh copy of the object's data.

  **Why it matters:** explains why mutating an object inside a method affects the caller's copy too, while reassigning a primitive parameter inside a method does not.
  </details>

- [ ] [1.14: Instance Methods](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.14-callinginstances-innovators.ipynb) · [homework](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.14-callinginstances-homework-innovators.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a method that acts on a specific object's own data, invoked through that object (`obj.method()`). Void methods perform an action with no return value; non-void methods hand a value back to the caller.

  **Why it matters:** most real class design is instance methods manipulating instance data, this is the pattern behind nearly every custom class built for the rest of the course.
  </details>

- [ ] [1.15: String Manipulation](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-1.15.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** Strings are immutable, so methods like `substring()`, `indexOf()`, `length()`, and `charAt()` all return new information rather than modifying the original string.

  **Why it matters:** forgetting immutability is a common bug, `str.toUpperCase()` does nothing by itself unless you capture its return value, since it can't change `str` in place.
  </details>

- [ ] [Unit 1 Quiz](_notebooks/AP_MCQ/ap_mcq_lessons/unit_01/2025-09-21-u1quiz.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a cumulative check across primitive types, variables, casting, and basic class/object usage from the whole unit.

  **Why it matters:** its format (Hack cells plus a written FRQ plus a working `Account` class) mirrors the actual multiple-choice-and-FRQ structure of the real AP exam.
  </details>

</details>

---

<a id="unit-2"></a>
<details>
<summary><h2>Unit 2: Selection & Iteration &nbsp;<code>7 / 7, Completed</code></h2></summary>

- [ ] [2.3: if Statements](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.3.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** runs a block of code only when a boolean condition evaluates true; `else` provides the fallback path for when it's false.

  **Why it matters:** this is the first real branching logic in the course. Every conditional structure after this (else-if chains, loop conditions) builds on this single if/else pattern.
  </details>

- [ ] [2.4: Nested if Statements](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.4.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** `else if` chains test conditions in order and stop at the first one that matches, letting a program sort a value into one of several ranges.

  **Why it matters:** the classic use case is a grade evaluator, testing a score against thresholds top-down (A, then B, then C) instead of separate, unrelated if statements that could all fire at once.
  </details>

- [ ] [2.7: while Loops](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.7.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** repeats a block as long as a condition stays true, checked again before every pass.

  **Why it matters:** best when the number of repetitions isn't known ahead of time (waiting on user input, searching until something's found) versus a for loop where the count is fixed.
  </details>

- [ ] [2.8: for Loops](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.8.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** bundles a counter's start, continue-condition, and update into a single line (`for (int i = 0; i < n; i++)`) instead of managing all three separately like a while loop would.

  **Why it matters:** the standard tool whenever the number of repetitions is known in advance, iterating over an array or a fixed range.
  </details>

- [ ] [2.10: Implementing String Algorithms](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.10.ipynb) (best evidence)
  <details>
  <summary>description</summary>

  **What it is:** combining loops with String methods to process text character by character, scanning for a substring, counting vowels, validating input.

  **Why it matters:** reinforces that string traversal is just a loop over indices, `charAt(i)` inside a `for` loop is the core pattern behind nearly every string algorithm.
  </details>

- [ ] [2.11: Nested Iteration](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.11.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a loop inside another loop, where the inner loop runs all the way to completion for every single pass of the outer loop.

  **Why it matters:** total iterations multiply rather than add. A nested loop over an n-length and m-length range runs n × m times total, this is where run-time cost starts becoming visible.
  </details>

- [ ] [2.12: Informal Run-Time Analysis](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.12.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** counting how many times a piece of code actually executes based on its loops and conditions, without formal Big-O notation yet.

  **Why it matters:** it's an early, hands-on version of what Big-O later formalizes, worth building as a habit before it's ever given a name.
  </details>

<details>
<summary>Stub notebooks, skip these (click to expand anyway if you want to double-check)</summary>

- [2.1: Algorithms with Selection and Repetition](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.1.ipynb)
- [2.2: Boolean Expressions](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.2.ipynb)
- [2.5: Compound Boolean Expressions](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.5.ipynb)
- [2.6: Comparing Boolean Expressions](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.6.ipynb)
- [2.9: Implementing Selection and Iteration Algorithms](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-2.9.ipynb)
- [Unit 2 Quiz](_notebooks/AP_MCQ/ap_mcq_lessons/unit_02/2025-09-21-u2quiz.ipynb) (empty stub)

</details>

</details>

---

<a id="unit-3"></a>
<details>
<summary><h2>Unit 3: Classes &nbsp;<code>3 / 3, Completed</code></h2></summary>

- [ ] [3.3: Anatomy of a Class](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.3.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** identifies where in real code a class gets defined, where an object gets instantiated (`new`), where a method actually gets called, and where data gets mutated. Also covers the `Object` superclass every class implicitly extends, which is where `toString()`, `equals()`, and `getClass()` come from.

  **Why it matters:** if you override one of those inherited `Object` methods, it must stay `public`, since every `Object` method is public and access can only be widened when overriding, never narrowed.
  </details>

- [ ] [3.5: Methods: How to Write Them](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.5.ipynb) (best evidence)
  <details>
  <summary>description</summary>

  **What it is:** a subclass can override an inherited method to replace its behavior. `@Override` flags that intent so the compiler catches spelling mistakes instead of silently creating an unrelated new method.

  **Why it matters:** `super.method()` lets a subclass still call the parent's original version from inside its own override, useful for extending rather than fully replacing behavior. Calling a method inside itself without `super` causes infinite recursion.
  </details>

- [ ] [3.9: this Keyword](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.9.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a variable's static type is what it's declared as; its dynamic type is what object it actually references at runtime. Java always runs the dynamic type's overridden version of a method, that's polymorphism.

  **Why it matters:** a superclass-typed reference can't call subclass-only methods until it's down-cast back to the subclass type, and down-casting only works if the reference is actually pointing to that subclass underneath.
  </details>

<details>
<summary>Stub notebooks, skip these</summary>

- [3.1: Abstraction and Program Design](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.1.ipynb)
- [3.2: Impact of Program Design](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.2.ipynb)
- [3.4: Constructors](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.4.ipynb)
- [3.6: Methods: Passing and Returning References of an Object](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.6.ipynb)
- [3.7: Class Variables and Methods](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.7.ipynb)
- [3.8: Scope and Access](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-3.8.ipynb)
- [Unit 3 Quiz](_notebooks/AP_MCQ/ap_mcq_lessons/unit_03/2025-09-21-u3quiz.ipynb) (empty stub)

</details>

</details>

---

<a id="unit-4"></a>
<details>
<summary><h2>Unit 4: Arrays & ArrayList &nbsp;<code>0 / 6, not started</code></h2></summary>

- [ ] [4.3: Array Creation and Access](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.3.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** declaring a fixed-size array with `type[] name = new type[size]`, then reading or writing a single slot with `name[index]`, where indexing starts at 0.

  **Why it matters:** an out-of-bounds index (anything below 0 or at/above the array's length) throws `ArrayIndexOutOfBoundsException` at runtime, a very common source of bugs on the exam and in real code.
  </details>

- [ ] [4.4: Array Traversals](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.4.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** looping over every index of an array (usually with a `for` loop from `0` to `array.length - 1`) to read, sum, search, or modify its elements.

  **Why it matters:** almost every array-based FRQ is a traversal at its core, so getting the loop bounds and index math right here is what everything after this unit depends on.
  </details>

- [ ] [4.8: ArrayList Methods](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.8.ipynb) (best evidence) *(or 4.9, check with teacher which one to do, may be duplicates)*
  <details>
  <summary>description</summary>

  **What it is:** `ArrayList` is a resizable, object-only list backed by methods like `add()`, `get()`, `set()`, `remove()`, and `size()`, unlike a fixed-size array.

  **Why it matters:** it's the standard collection type once an array's fixed size becomes a problem, and its method-call syntax (`list.add(x)` instead of `arr[i] = x`) trips people up if they're used to array notation.
  </details>

- [ ] [4.9: ArrayList Traversals](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.9.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** looping over an `ArrayList` with `get(i)` and `size()`, or with an enhanced for-each loop when the index itself isn't needed.

  **Why it matters:** removing elements while traversing forward by index skips entries (the list shifts down after each removal), so traversing backward, or using an iterator, is the safe pattern.
  </details>

- [ ] [4.11: 2D Array Creation and Access](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.11.ipynb) *(or 4.12, check with teacher which one to do, may be duplicates)*
  <details>
  <summary>description</summary>

  **What it is:** an array of arrays, declared as `type[][] name = new type[rows][cols]`, accessed with two indices `name[row][col]`.

  **Why it matters:** rows can have different lengths (a jagged array), so always checking `name[row].length` rather than assuming a fixed column count avoids out-of-bounds errors.
  </details>

- [ ] [4.12: 2D Array Traversals](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.12.ipynb)
  <details>
  <summary>description</summary>

  **What it is:** a nested loop, outer over rows and inner over columns, to visit every cell of a 2D array in row-major order.

  **Why it matters:** it's the same nested-iteration cost from 2.11 applied to a grid, and swapping the loop order changes whether you traverse row-by-row or column-by-column.
  </details>

<details>
<summary>Stub notebooks, skip these</summary>

- [4.1: Ethical and Social Issues Around Data Collection](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.1.ipynb)
- [4.2: Introduction to Using Data Sets](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.2.ipynb)
- [4.5: Implementing Array Algorithms](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.5.ipynb)
- [4.6: Using Text Files](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.6.ipynb)
- [4.7: Wrapper Classes](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.7.ipynb)
- [4.10: Implementing ArrayList Algorithms](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-4.10.ipynb)
- [Unit 4 Quiz](_notebooks/AP_MCQ/ap_mcq_lessons/unit_04/2025-09-21-u4quiz.ipynb) (empty stub)

</details>

</details>

---

## Progress

`7 / 32` real lessons + quiz completed *(update this count yourself as you check boxes off, and nudge the fractions in the Quick Jump bar + each unit's `<summary>` to match)*
