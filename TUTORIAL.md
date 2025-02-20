#### **2. Tutorial (TUTORIAL.md)**
Create a `TUTORIAL.md` file to teach users how to use Lexx. Here’s an outline:

```markdown
# Lexx Tutorial

Welcome to Lexx! This tutorial will guide you through the basics of the language.

## Table of Contents
1. [Variables](#variables)
2. [Input and Output](#input-and-output)
3. [Conditionals](#conditionals)
4. [Loops](#loops)
5. [Functions](#functions)
6. [Lists](#lists)
7. [File I/O](#file-io)

## Variables
Use `set` to create variables:
```lexx
set myAge to 10
set myName to "Alex"

## Input and Output
Ask for input with `ask` and print output with `say`:
```lexx
ask "What's your favorite color?" and save it as favoriteColor
say "Your favorite color is {favoriteColor}!"
```

## Conditionals
Use `if`, `otherwise if`, and `otherwise` for decision-making:
```lexx
if age > 12 then
    say "You're a teenager!"
otherwise
    say "You're still a kid!"
```

## Loops
Repeat code with `repeat` or `while`:
```lexx
repeat 5 times
    say "I love Lexx!"
```

## Functions
Define functions with `make` and call them with `do`:
```lexx
make greet with name
    say "Hello, {name}!"
end

do greet with "Alice"
```

## Lists
Store collections of items:
```lexx
set fruits to ["apple", "banana", "cherry"]
add "orange" to fruits
```

## File I/O
Read and write files:
```lexx
read file "data.txt" and save it as content
write "Hello, Lexx!" to file "output.txt"
```
## Next Steps
Try writing your own Lexx programs! For more examples, check out the [examples](examples/) folder.
```

#### **3. Contributing Guidelines (CONTRIBUTING.md)**
Create a `CONTRIBUTING.md` file to encourage contributions:
```markdown
# Contributing to Lexx

We welcome contributions from everyone! Here’s how you can help:

1. **Report Bugs**: Open an issue on GitHub.
2. **Suggest Features**: Share your ideas in the issues section.
3. **Submit Code**: Fork the repository, make your changes, and submit a pull request.

## Code Style
- Follow PEP 8 for Python code.
- Write clear, concise comments.

## Testing
Make sure your changes pass all tests. Add new tests if needed.

## License
By contributing, you agree to license your work under the MIT License.