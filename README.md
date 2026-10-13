
<p align="center">
  <img width="820" alt="Zilch logo" src="https://github.com/user-attachments/assets/dd5ce377-d936-4165-971e-ce3cc8b3db68" />
</p>

<p align="center">
  <strong>A small language. Strong types. Native performance.</strong>
</p>

<p align="center">
  A statically typed, native-compiled programming language designed around type safety, performance, and simplicity.
</p>

---

## Overview

**Zilch** is a programming language built to make systems-level development straightforward without sacrificing type safety or performance.

Combining concise syntax inspired by **Odin** and **Luau** with static typing and native compilation, Zilch aims to provide a language that is expressive, predictable, and easy to work with.

Rather than relying on a large collection of language features, Zilch focuses on a small, coherent foundation that makes code easy to read, reason about, and maintain.

## Design Goals

- **Static typing** - Catch type errors during compilation and make data relationships explicit.
- **Native compilation** - Compile programs to native machine code instead of requiring a virtual machine at runtime.
- **Simplicity** - Favor straightforward language rules and a consistent syntax over unnecessary complexity.
- **Performance** - Keep runtime overhead low and give developers control over how their programs are structured.
- **Concise syntax** - Take inspiration from Odin's explicit declarations and Luau's approachable table and array syntax.
- **Predictability** - Design language behavior to be understandable, consistent, and easy to reason about.

## Language Design

Zilch draws inspiration from existing languages while aiming to establish its own identity.

| Influence | Design inspiration |
|---|---|
| Odin | Explicit declarations, readable syntax, and systems programming |
| Luau | Accessible syntax and expressive data constructors |
| Native compilation | Direct execution as compiled machine code |
| Static type systems | Compile-time type checking and predictable programs |

These influences inform the language's design without making Zilch a direct clone of any existing language.

## Example

The following illustrates the intended style of Zilch. Syntax and available features may change as the language develops.

```rust
// Example Zilch syntax — illustrative

import "zilch:std/io"

struct Player {
    name: string,
    health: i32,
}

main :: func() {
    player := Player{
        name = "Player",
        health = 100,
    }

    io.println(player.name)
}
```

## Current Status

Zilch is under active development. Its syntax, compiler implementation, standard library, and tooling may evolve as the language takes shape.

Not every planned feature is necessarily available yet. Check the repository for the current implementation and supported functionality.

## Roadmap

The following are potential development milestones, not a guarantee that every feature is already implemented.

- [ ] Finalize the core language specification
- [ ] Establish a robust static type checker
- [ ] Implement native code generation
- [ ] Develop the standard library
- [ ] Improve compiler diagnostics and error reporting
- [ ] Add a package and module workflow
- [ ] Introduce automated tests and language examples
- [ ] Improve developer tooling and editor support

## Philosophy

Zilch aims to strike a balance between **simplicity, explicitness, and performance**.

A language should make the common path straightforward without hiding important behavior. Types should communicate intent, syntax should remain readable, and the compiler should help developers identify mistakes before their programs run.

The goal is not to create a language with the most features. It is to create one where the features that exist work well together.

## Contributing

Contributions, ideas, bug reports, and discussions are welcome as the project develops.

Before proposing significant language changes, consider opening an issue to discuss the design and its implications for the language.

## License

See the repository's `LICENSE` file for licensing information.
