# What is Programming?
Agenda:
- Part 1: Introduction
- Part 2: The Rules of Programming Languages
- Part 3: Working with Data
- Part 4: Managing Program Flow
- Part 5: Making Things Modular
- Part 6: Programming in the Real World

## Part 1: Introduction
Most courses start by teaching you a specific `Programming Language`, but before getting any of them - We need to learn more about `Programming` in general.

It's not about what Programming Language or Technology you use, it's all about **how you think**!

Why taking this course?
- You want to become A Programmer
- You don't want to become A Programmer (Curious about them, or even work with programmers)
- You aren't sure about being a programmer or not!

### What is a computer program?
A computer program is a list of instructions that we write using a Programming Language the computer understands. (Like a recipe)

> Complex results are made by Simple, Specific and Ordered Instructions

### Source Code
A collection of computer instructions written using some human-readable computer programming language, usually as plain text.

Most programmers use `Monospaced` Fonts (Menlo, Consolas, Courier) because every letter has the same space, unlike `Proportional` Fonts (Arial, Verdana, Times). Because we care about `indentation`, and it's important to let each letter takes the same space.

There's an incorrect part in our `Computer Program` definition; `Programming language that computer understands`, it's not entirely true. Because computers don't understand any of our Programming Languages, the `CPU` only understands `Machine Code` or `Machine Language`.

> The main purpose of `Programming Languages` is to DON'T write `Machine Code`

### Compilation Model
In order to convert our `Source Code` into `Machine Code` we use A `Compiler` or an `Interpreter`. The main difference is **when the `Source Code` is getting converted into `Machine Code`!**

**Compiler:** Create an executable file `.exe`, and give it to you.
**Interpreter:** Gives you my Source Code, and you will use an interpreter to convert it into Machine Code.

> Every browser has a JavaScript Interpreter

| Compiled Languages | Interpreted Language |
|--------------------|----------------------|
| Often faster | Often Slower |
| Platform-specific | Cross-platform |
| Source code not shared | Source Code is shared |
| Ready to run | Requires an Interpreter |
| C++, Switft, C | JavaScript, Python, PHP |

`Some Programming Languages` offers a 3rd option; To compile your code partially to an `Intermediate Language (Often called **Bytecode**)`, and _when needed_ it gets `Just-in-time` Compiling. Some of those `Hybrid Languages` are:
- Java
- ActionScript
- LISP

### What about `0` and `1`?
`CPUs` are made of Billions of Electrical Switches/Transistors, either `ON` or `OFF`. That's why it's known to be `0` and `1`, not `Machine Code`.

> Explanation of `Binary Code`; Instead of representing/visualizing `ON/OFF` switches, we might use `"on" or "off"` words. Or... Use `0` for `OFF` and `1` for `ON`.

So, the `0/1` is a way we used to `represent` the `ON/OFF` Switches. Not an actual `0/1` bouncing inside our `CPU`

**In the `Computer World`;** We don't call them `Switch`, we call them `Bit` ~ `Binary Digit`. Either `0` or `1`!

Here are some numbers:
- 8 bits: 256 Possible Values
- 16 bits: 65,000 Possible Values
- 32 bits: +4.3 Billion Possible Values!

The more `bits` the CPU deals with, the better performance. So, the `64-Bits` is better than the `32-Bits` Architecture.

We use different method to represent the exact information. For example; **How can we represent 27 bananas?**
- Twenty Seven
- 27
- XXVII
- //// //// /// /// /// //
- Using our hands
- Draw 27 banana shapes

`Machine Code` use Hexdecimal or Hex, to represent more `Binary Code` easily with a combination of numbers/letters

Example:
- `00000000` in binary, is `00` in hex
- `11111111` in binary, is `FF` in hex
- `10000000` in binary, is `80` in hex
- `01000000` in binary, is `40` in hex

`Hexdecimal` have 2 digits (0 through 9) and (A through F)

## Part 2: The Rules of Programming Languages
`Syntax` is the rules of a programming language. Rules aren't guidelines, YOU MUST follow them!

- Case Sensitivity; Almost all programming languages are `Case Sensitive`
- Statements (Write & End each instruction); Specific, Small, Self-Contained Instructions
- Whitespaces; Most programming languages don't care about it. But, it's very important for us - programmers - as identation, and it makes the code readable!
- Comments; Write comments even if you think it's only you who will read this code. Remember, not all code needs to be commented. Some programmers use comments as a way of `Reminding`! Ex.: `TODO: display custom graphic here`. Moreover, it's a great way to `Comment Out` your code, instead of deleting them.
- Keywords; `Java` has around `50 Keywords` only. All languages have a few keywords (Reserved Keywords for the Language). That's why we `Define our words` (i.e. Create Variables, Functions, Classes). So, a `Keyword` has a pre-defined and fixed meaning in the Programming Language.

### Using `Pseudocode`
It's a way of communicating, regardless what programming language you're using.

> Pseudocode isn't only for Beginners.

So many people underestimate Pseudocode and want to jump into the `Source Code`. Basically, The Pseudocode is all about how you think, and visualize your thinking quicker, instead of waiting infront of an editor asking yourself what I should be writing now?

It's not an actual language, there's no right/wrong here.

Why to use it?
- Communicate with non-programmers
- GREAT for planning; As it helps you get unstuck, and think of the next step
- Make progress & Fix a problem before actually writing any code
- Programming Languages/Syntax doesn't matter
- Think of a big problem, divide it into smaller ones, and it will saves you a lot of time

## Part 3: Working with Data
General info about the `Input/Inout` and `Data`.

Naming Variables:
- Rules:
    - No Reserved Words/Keywords (i.e. `var true`!)
    - No spaces
    - Don't start with a Digit

- Guidelines (Style):
    - `camelCase` / use an `underscore`. But `camelCase` seems to be the convention!

`Operator:` A shortcut to perform a specific task - one operation. Any operator that requires **two values** is called `Binary Operator` (i.e. +, -, *, /)

`Assignment Operator =`: The shortcut to assign (set) a new value

### Data Types
When dealing with names/numbers, we don't think of them the same way. The `Age` is only positive, within small range. Your `Bank Balance` is a number as well, but it might be a floated number (i.e. $140.20)!

Different Levels of Detail:
- C++, Swift, Java: Specifiy the variable `datatype` upfront.
- Python, JavaScript: More flexible, you can do it later or even don't do it at all.

Data Types:
- Numbers: Integer, Float
- Boolean: True/False
- Text: String (It's more complex for the computer, as it's not specified, how many characters it might contains, does it contains numbers? ... etc.)

Programming languages offer `Built-In "Primitive" Types`

`Constants`
- Introduction
- The convention is to use `ALL_CAPS` writing style

Programming Languages are divided into 2 categories, in terms of dealing with datatypes:
- Statically typed / Type Safe: Swift, C++ 
- Dynamically typed: JavaScript, Python