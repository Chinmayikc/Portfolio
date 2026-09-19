# Hello World Portfolio Activity

This project is a small C program used to practice Git, GitLens, and Live Share collaboration.

## Build and run

```text
gcc hello.c -o hello.exe
hello.exe
```

The program prints a basic Hello World message and a personalized greeting from `greet()`.

## Collaboration Log

- Pairing partner: Chaitali
- GitHub username: `chaitali` (the local activity files identify the partner only by this name; verify the handle before publishing)
- Built together: added `greet(const char *name)` and called it from `main()` with `greet("Ada")`.
- What I learned: GitLens blame connects each line to the commit and author that last changed it, while Live Share lets both partners edit the same workspace in real time.

## Reflection

- GitLens blame makes unfamiliar code easier to understand because it shows who changed a line, when it changed, and which commit contains the explanation.
- Live Share makes pair programming convenient across different locations, but it depends on a reliable connection and can make it harder to communicate than working side by side.
- Employers value collaborative commit history because it provides evidence that a developer can communicate, review changes, and contribute safely with a team.
