# Hello World Portfolio Activity

This project is a small C program used to practice Git, GitLens, and Live Share collaboration.

## Activity 1 - Development Environment Setup

I installed Visual Studio Code with the C/C++ extension and configured MinGW-w64 GCC as the C compiler. I verified the installation with `gcc --version`, compiled `hello.c`, and confirmed that the program ran successfully.

## Build and run

```text
gcc hello.c -o hello.exe
hello.exe
```

The program prints a basic Hello World message and a personalized greeting from `greet()`.

## Collaboration Log

- Pairing partner: kadalagichaitali9-ux
- GitHub username: `kadalagichaitali9-ux`
- Built together: added `greet(const char *name)` and called it from `main()` with `greet("Ada")`.
- What I learned: GitLens blame connects each line to the commit and author that last changed it, while Live Share lets both partners edit the same workspace in real time.

## Reflection

- GitLens blame makes unfamiliar code easier to understand because it shows who changed a line, when it changed, and which commit contains the explanation.
- Live Share makes pair programming convenient across different locations, but it depends on a reliable connection and can make it harder to communicate than working side by side.
- Employers value collaborative commit history because it provides evidence that a developer can communicate, review changes, and contribute safely with a team.
