+++
title = "Idiomatic Rust: Resources And Learning Material"
date = 2024-01-28
draft = false
template = "wide_page.html"
[extra]
series = "Resources"
+++

Below is a list of resources that **help you to write ergonomic Rust code**.  

The references offer a wealth of information on how to write better Rust code,
including tutorials, workshops, and articles by Rust experts. Each piece in the
collection is peer-reviewed to adherence to Rust best practices.
You can filter, sort, and search by tags, year, and difficulty level.

The list is [maintained on GitHub](https://github.com/mre/idiomatic-rust). Contributions welcome.

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script src="//cdn.datatables.net/1.13.7/js/jquery.dataTables.min.js"></script>
<script>
    var data = [
  {
    "title": "Rust Anthology",
    "url": "https://github.com/brson/rust-anthology",
    "description": "The best short-form writing about Rust, collected.",
    "tags": [
      "anthology",
      "writing",
      "collection"
    ],
    "official": false,
    "year": 2018,
    "difficultyLevel": "all",
    "duration": null,
    "interactivityLevel": "low",
    "free": true,
    "category": "project"
  },
  {
    "title": "blessed.rs",
    "url": "https://blessed.rs",
    "description": "An unofficial guide to the Rust ecosystem. Suggestions for popular, well-maintained crates.",
    "tags": [
      "guide",
      "ecosystem",
      "crates"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "all",
    "duration": null,
    "interactivityLevel": "medium",
    "free": true,
    "category": "project"
  },
  {
    "title": "cheats.rs - Idiomatic Rust tips",
    "url": "https://cheats.rs",
    "description": "A list of quick tips to make your code more idiomatic.",
    "tags": [
      "tips",
      "idiomatic",
      "quick"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "all",
    "duration": null,
    "interactivityLevel": "low",
    "free": true,
    "category": "project"
  },
  {
    "title": "clippy",
    "url": "https://github.com/rust-lang/rust-clippy",
    "description": "A bunch of lints to catch common mistakes and improve your Rust code.",
    "tags": [
      "lints",
      "code-quality",
      "tool"
    ],
    "official": true,
    "year": 2015,
    "difficultyLevel": "all",
    "duration": null,
    "interactivityLevel": "low",
    "free": true,
    "category": "project"
  },
  {
    "title": "Patterns",
    "url": "https://rust-unofficial.github.io/patterns/",
    "description": "A catalogue of design patterns in Rust.",
    "tags": [
      "design-patterns",
      "catalogue",
      "best-practices"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": null,
    "interactivityLevel": "low",
    "free": true,
    "category": "project"
  },
  {
    "title": "Elements of Rust",
    "url": "https://github.com/ferrous-systems/elements-of-rust",
    "description": "A collection of software engineering techniques for effectively expressing intent with Rust.",
    "tags": [
      "software-engineering",
      "techniques",
      "best-practices"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "advanced",
    "duration": null,
    "interactivityLevel": "medium",
    "free": true,
    "category": "project"
  },
  {
    "title": "Possible Rust",
    "url": "https://www.possiblerust.com/",
    "description": "A blog for intermediate Rust programmers exploring real-world code and design patterns.",
    "tags": [
      "blog",
      "intermediate",
      "design-patterns"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": null,
    "interactivityLevel": "medium",
    "free": true,
    "category": "project"
  },
  {
    "title": "Rust API Guidelines",
    "url": "https://rust-lang.github.io/api-guidelines/",
    "description": "An extensive list of recommendations for idiomatic Rust APIs.",
    "tags": [
      "api",
      "guidelines",
      "best-practices"
    ],
    "official": true,
    "year": 2017,
    "difficultyLevel": "intermediate",
    "duration": null,
    "interactivityLevel": "low",
    "free": true,
    "category": "project"
  },
  {
    "title": "Rust by Example",
    "url": "https://doc.rust-lang.org/rust-by-example/",
    "description": "A community driven collection of example code which follow Rust best practices.",
    "tags": [
      "examples",
      "community",
      "best-practices"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "all",
    "duration": null,
    "interactivityLevel": "high",
    "free": true,
    "category": "project"
  },
  {
    "title": "Comprehensive Rust",
    "url": "https://github.com/google/comprehensive-rust",
    "description": "A four day Rust course developed by the Android team, covering all aspects of Rust.",
    "tags": [
      "course",
      "learning",
      "comprehensive"
    ],
    "official": true,
    "year": 2021,
    "difficultyLevel": "all",
    "duration": "4 days",
    "interactivityLevel": "high",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Build your own JIRA with Rust",
    "url": "https://github.com/LukeMathWalker/build-your-own-jira-with-rust/",
    "description": "A test-driven workshop to learn Rust by building your own JIRA clone!",
    "tags": [
      "test-driven",
      "project"
    ],
    "official": true,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Ferrous Systems Teaching Material",
    "url": "https://ferrous-systems.github.io/teaching-material/index.html",
    "description": "Free workshop material produced by Ferrous Systems for trainings.",
    "tags": [
      "material",
      "training"
    ],
    "official": true,
    "year": 2019,
    "difficultyLevel": "all",
    "duration": "3-4 days",
    "interactivityLevel": "medium",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "PingCAP talent plan",
    "url": "https://github.com/pingcap/talent-plan",
    "description": "A series of training courses about writing distributed systems in Rust.",
    "tags": [
      "training",
      "distributed-systems",
      "course"
    ],
    "official": true,
    "year": 2018,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Procedural Macros Workshop",
    "url": "https://github.com/dtolnay/proc-macro-workshop",
    "description": "A selection of projects designed to learn to write Rust procedural macros.",
    "tags": [
      "macros",
      "coding"
    ],
    "official": true,
    "year": 2019,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "rust-lang/rustlings",
    "url": "https://github.com/rust-lang/rustlings",
    "description": "Small exercises to get you used to reading and writing Rust code.",
    "tags": [
      "exercises",
      "learning",
      "beginner"
    ],
    "official": true,
    "year": 2018,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Rust Development at Sentry",
    "url": "https://develop.sentry.dev/rust/",
    "description": "A document containing useful resources for getting started with Rust and adhering to Sentry coding principles.",
    "tags": [
      "guide",
      "coding-principles",
      "development"
    ],
    "official": true,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Rust 101",
    "url": "https://101-rs.tweede.golf/",
    "description": "A Rust University course by tweede golf.",
    "tags": [
      "course",
      "university",
      "learning"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "workshop"
  },
  {
    "title": "Command Line Applications in Rust",
    "url": "https://rust-cli.github.io/book",
    "description": "A tutorial on how to write CLI apps in Rust, learning many aspects of the ecosystem.",
    "tags": [
      "tutorial",
      "cli",
      "ecosystem"
    ],
    "official": false,
    "year": 2024,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "book"
  },
  {
    "title": "Command-Line Rust",
    "url": "https://github.com/kyclark/command-line-rust",
    "description": "Learn the language by writing Rust versions of common Unix coreutils.",
    "tags": [
      "unix",
      "coreutils",
      "learning"
    ],
    "official": false,
    "year": 2022,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "book"
  },
  {
    "title": "Discover the world of microcontrollers through Rust!",
    "url": "https://rust-embedded.github.io/discovery/",
    "description": "An introductory course on microcontroller-based embedded systems using Rust.",
    "tags": [
      "embedded-systems",
      "microcontroller",
      "course"
    ],
    "official": false,
    "year": 2023,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "book"
  },
  {
    "title": "High Assurance Rust",
    "url": "https://highassurance.rs/",
    "description": "Developing secure and robust software, focusing on embedded-friendly data structures in Rust.",
    "tags": [
      "security",
      "robustness",
      "embedded"
    ],
    "official": false,
    "year": 2022,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "book"
  },
  {
    "title": "Rust Cookbook",
    "url": "https://github.com/rust-lang-nursery/rust-cookbook",
    "description": "Examples that demonstrate good practices to accomplish common programming tasks in Rust.",
    "tags": [
      "examples",
      "good-practices",
      "programming"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "book"
  },
  {
    "title": "Rust for Rustaceans",
    "url": "https://nostarch.com/rust-rustaceans",
    "description": "Covers how to design reliable, idiomatic, and ergonomic Rust programs based on best principles.",
    "tags": [
      "design",
      "idiomatic",
      "ergonomic"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": false,
    "category": "book"
  },
  {
    "title": "Programming Rust: Fast, Safe Systems Development",
    "url": "https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/",
    "description": "A comprehensive Rust Programming Guide that covers most of Rust's features in detail.",
    "tags": [
      "comprehensive",
      "features",
      "guide"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": false,
    "category": "book"
  },
  {
    "title": "Rust Atomics and Locks",
    "url": "https://marabos.nl/atomics/",
    "description": "Helps Rust programmers of all levels gain a clear understanding of low-level concurrency.",
    "tags": [
      "concurrency",
      "low-level",
      "understanding"
    ],
    "official": false,
    "year": 2023,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "book"
  },
  {
    "title": "Compile-Time Invariants in Rust",
    "url": "https://corrode.dev/blog/compile-time-invariants/",
    "description": "Shows how macros can be used to enforce invariants at compile-time.",
    "tags": [
      "macros",
      "invariants",
      "compile-time"
    ],
    "official": false,
    "year": 2023,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Aim For Immutability in Rust",
    "url": "https://corrode.dev/blog/immutability/",
    "description": "Explains why variables are immutable in Rust by default.",
    "tags": [
      "immutability",
      "variables",
      "rust-basics"
    ],
    "official": false,
    "year": 2023,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Naming Your Lifetimes",
    "url": "https://www.possiblerust.com/pattern/naming-your-lifetimes",
    "description": "Explains how using longer, declarative lifetime names can help to disambiguate which borrow is which.",
    "tags": [
      "lifetimes",
      "naming-conventions",
      "rust-patterns"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Aiming for idiomatic Rust",
    "url": "https://web.archive.org/web/20221203043933/https://shane-o.dev/blog/aiming-for-idiomatic-rust",
    "description": "Discusses different ways to solve a popular coding puzzle, 'balanced brackets', in Rust.",
    "tags": [
      "coding-puzzle",
      "best-practices"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Wrapping errors in Rust",
    "url": "https://edgarluque.com/blog/wrapping-errors-in-rust",
    "description": "Wrapping 'reqwest::Error' and a custom error type as an enum to make library usage easier.",
    "tags": [
      "error-handling",
      "rust-tips",
      "programming"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Hexagonal architecture in Rust",
    "url": "https://alexis-lozano.com/hexagonal-architecture-in-rust-1/",
    "description": "Describes how to build a Rust service using domain driven design and a test-first approach.",
    "tags": [
      "architecture",
      "domain-driven-design",
      "rust-service"
    ],
    "official": false,
    "year": 2021,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Context-preserving error handling",
    "url": "https://kazlauskas.me/entries/errors",
    "description": "Explains how to use crates like 'thiserror' in combination with 'map_err' to add context to errors.",
    "tags": [
      "error-handling",
      "crates",
      "rust-tips"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Refactoring Rust Transpiled from C",
    "url": "https://immunant.com/blog/2020/09/transpiled_c_safety/",
    "description": "Describes how to lift a C-project that was automatically converted to unsafe Rust to safer, more idiomatic Rust.",
    "tags": [
      "refactoring",
      "transpiling",
      "c-to-rust"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Learning Rust through open source and live code reviews",
    "url": "https://loige.co/learning-rust-through-open-source-and-live-code-reviews/",
    "description": "Covers patterns like 'FromStr' and exposing a CLI and a library in one crate.",
    "tags": [
      "open-source",
      "code-review",
      "rust-patterns"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Guide on how to write documentation for a Rust crate",
    "url": "https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate",
    "description": "Writing good documentation with rustdoc including many examples.",
    "tags": [
      "documentation",
      "rustdoc",
      "best-practices"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Are out parameters idiomatic in Rust?",
    "url": "https://steveklabnik.com/writing/are-out-paramters-idiomatic-in-rust",
    "description": "Discusses the pros and cons of functions returning a value vs. modifying a parameter in-place.",
    "tags": [
      "functions",
      "parameters"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Await a minute",
    "url": "https://docs.rs/dtolnay/0.0.3/dtolnay/macro._01__await_a_minute.html",
    "description": "Example code for moving from raw futures to async/await syntax to improve error handling.",
    "tags": [
      "async",
      "await",
      "error-handling"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Taking string arguments in Rust",
    "url": "http://xion.io/post/code/rust-string-args.html",
    "description": "Discussing how to avoid subtle issues with string handling and when to use 'str' vs 'String'.",
    "tags": [
      "strings",
      "arguments",
      "best-practices"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Rust Patterns: Enums Instead Of Booleans",
    "url": "http://blakesmith.me/2019/05/07/rust-patterns-enums-instead-of-booleans.html",
    "description": "Discusses how using enums instead of booleans can express intent more clearly in Rust.",
    "tags": [
      "enums",
      "booleans",
      "patterns"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Programming an ARM microcontroller in Rust at four different levels of abstraction",
    "url": "https://pramode.in/2018/02/20/programming-a-microcontroller-in-rust-at-four-levels-of-abstraction/",
    "description": "Demonstrates how Rust helps to move from low-level embedded code to high-level abstractions.",
    "tags": [
      "microcontroller",
      "arm",
      "abstraction"
    ],
    "official": false,
    "year": 2018,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "article"
  },
  {
    "title": "Iteration patterns for Result & Option",
    "url": "http://xion.io/post/code/rust-iter-patterns.html",
    "description": "Explores how to filter and partition iterators of Result and Option types idiomatically.",
    "tags": [
      "iterators",
      "result",
      "option"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Lessons learned redesigning and refactoring a Rust Library",
    "url": "https://web.archive.org/web/20220126172949/https://blog.mgattozzi.dev/refactor-rust/",
    "description": "'RefCell', the builder pattern and more.",
    "tags": [
      "refactoring",
      "design-patterns",
      "library"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Math with distances in Rust: safety and correctness across units",
    "url": "https://ferrisellis.com/content/rust-implementing-units-for-types/",
    "description": "How to create a system to cleanly and safely do arithmetic with lengths.",
    "tags": [
      "math",
      "safety",
      "type-system"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "The balance between cost, useability and soundness in C bindings, and Rust-SDL2's release",
    "url": "https://web.archive.org/web/20190509123207/https://cobrand.github.io/rust/sdl2/2017/05/07/the-balance-between-soundness-cost-useability.html",
    "description": "Writing safe, sound, idiomatic libraries despite the limitations of the borrow checker.",
    "tags": [
      "c-bindings",
      "sdl2",
      "borrow-checker"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Russian Dolls and clean Rust code",
    "url": "https://web.archive.org/web/20220126183049/https://blog.mgattozzi.dev/russian-dolls/",
    "description": "How to use the full power of 'Option' and 'Result' (especially 'and_then()' and 'unwrap_or()').",
    "tags": [
      "option",
      "result",
      "code-quality"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Elegant Library APIs in Rust",
    "url": "https://deterministic.space/elegant-apis-in-rust.html",
    "description": "Many helpful tips and tricks for writing libraries in Rust.",
    "tags": [
      "libraries",
      "api-design",
      "best-practices"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Teaching libraries through good documentation",
    "url": "https://deterministic.space/teaching-libraries.html",
    "description": "How to use the full power of Rust's documentation support (e.g. doc tests).",
    "tags": [
      "documentation",
      "libraries"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Pretty State Machine Patterns in Rust",
    "url": "https://hoverbear.org/2016/10/12/rust-state-machine-pattern/",
    "description": "How to represent a State Machine in an expressive and understandable way in Rust.",
    "tags": [
      "state-machine",
      "patterns"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Ripgrep Code Review",
    "url": "https://blog.mbrt.dev/posts/ripgrep/",
    "description": "An analysis of the popular 'ripgrep' tool's source code.",
    "tags": [
      "code-review",
      "ripgrep",
      "analysis"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Rustic Bits",
    "url": "https://llogiq.github.io/2016/02/11/rustic.html",
    "description": "Small things that make for rustic code.",
    "tags": [
      "best-practices",
      "code-quality"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "beginner",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Convenient and idiomatic conversions in Rust",
    "url": "https://ricardomartins.cc/2016/08/03/convenient_and_idiomatic_conversions_in_rust",
    "description": "Explains 'From<T>', 'Into<T>', 'TryFrom<T>', 'TryInto<T>', 'AsRef<T>' and 'AsMut<T>' with practical examples.",
    "tags": [
      "conversions",
      "examples"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Idiomatic tree and graph like structures in Rust",
    "url": "https://rust-leipzig.github.io/architecture/2016/12/20/idiomatic-trees-in-rust/",
    "description": "Introduction to safe, dynamic, arena based tree structures without using lifetimes.",
    "tags": [
      "tree-structures",
      "graphs"
    ],
    "official": false,
    "year": 2016,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Rust traits for developer friendly libraries",
    "url": "https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/",
    "description": "Thoughts about implementing good Rust libraries.",
    "tags": [
      "rust-traits",
      "libraries",
      "development"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "article"
  },
  {
    "title": "Error Handling in Rust",
    "url": "https://blog.burntsushi.net/rust-error-handling/",
    "description": "Understanding and handling errors in Rust in an idiomatic way.",
    "tags": [
      "error-handling"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Creating a Rust function that accepts String or &str",
    "url": "https://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html",
    "description": "How to make calling your code both ergonomic and fast (zero-allocation).",
    "tags": [
      "functions",
      "string-handling"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Creating a Rust function that returns a &str or String",
    "url": "https://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html",
    "description": "How 'Into' and 'Cow' (Clone-on-write) work together to avoid allocations for string types.",
    "tags": [
      "functions",
      "string-handling"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Effectively Using Iterators In Rust",
    "url": "https://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html",
    "description": "Explanation of the 'Iter' and 'IntoIter' traits and how loops actually work in Rust.",
    "tags": [
      "iterators",
      "traits"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Strategies for solving 'cannot move out of' borrowing errors in Rust",
    "url": "https://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html",
    "description": "Practical tips to help understand the borrow-checker and move semantics.",
    "tags": [
      "borrow-checker",
      "move-semantics"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Rayon: data parallelism in Rust",
    "url": "https://smallcultfollowing.com/babysteps/blog/2015/12/18/rayon-data-parallelism-in-rust/",
    "description": "Writing elegant parallel code in Rust.",
    "tags": [
      "parallelism",
      "rayon"
    ],
    "official": false,
    "year": 2015,
    "difficultyLevel": "advanced",
    "duration": "variable",
    "interactivityLevel": "medium",
    "free": true,
    "category": "article"
  },
  {
    "title": "Tricks of the Trait: Enabling Ergonomic Extractors",
    "url": "https://www.youtube.com/watch?v=7DOYtnCXucw",
    "description": "Rust Nation UK, Feb. 2023",
    "tags": [
      "traits",
      "ergonomics",
      "extractors"
    ],
    "official": false,
    "year": 2023,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Nine Rules for Elegant Rust Library APIs",
    "url": "https://www.youtube.com/watch?v=6-8-9ZV-2WQ",
    "description": "Seattle Rust Meetup, Sep. 2022",
    "tags": [
      "library-apis",
      "elegance"
    ],
    "official": false,
    "year": 2022,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Ergonomic APIs for hard problems",
    "url": "https://www.youtube.com/watch?v=Phk0C-kLlho",
    "description": "RustLab Conference, October 2022",
    "tags": [
      "apis",
      "ergonomics",
      "rust-conference"
    ],
    "official": false,
    "year": 2022,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Macros for a More Productive Rust",
    "url": "https://www.youtube.com/watch?v=dZiWkbnaQe8",
    "description": "RustConf 2020",
    "tags": [
      "macros",
      "productivity",
      "rustconf"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Making Rust Delightful",
    "url": "https://www.youtube.com/watch?v=YSEx8wtlPWc",
    "description": "RustCon Asia 2019",
    "tags": [
      "conference",
      "development"
    ],
    "official": false,
    "year": 2019,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Idiomatic Rust - Writing Concise and Elegant Rust Code",
    "url": "https://www.youtube.com/watch?v=P2mooqNMxMs",
    "description": "FOSDEM 2018",
    "tags": [
      "fosdem"
    ],
    "official": false,
    "year": 2018,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Idiomatic Rust Libraries",
    "url": "https://www.youtube.com/watch?v=0zOg8_B71gE",
    "description": "Rustfest Kiev",
    "tags": [
      "rust-libraries",
      "rustfest"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "low",
    "free": true,
    "category": "talk"
  },
  {
    "title": "Preferred way of passing `Path`-like types around?",
    "url": "https://www.reddit.com/r/rust/comments/cekeq9/preferred_way_of_passing_pathlike_types_around/",
    "description": "A Reddit discussion on the best practices for passing `Path`-like types in Rust.",
    "tags": [
      "discussion",
      "path-types",
      "best-practices"
    ],
    "official": false,
    "year": 2020,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "forum"
  },
  {
    "title": "Which is more idiomatic? Functional, imperative or a mix?",
    "url": "https://users.rust-lang.org/t/which-is-more-idiomatic-functional-imperative-or-a-mix/11278",
    "description": "A discussion on Rust's users forum about the idiomatic way to write Rust code: functional, imperative, or a mix of both.",
    "tags": [
      "functional",
      "imperative",
      "coding-style"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "all",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "forum"
  },
  {
    "title": "An idiomatic way to sum up values in a multidimensional Array",
    "url": "https://users.rust-lang.org/t/an-idiomatic-way-to-sum-up-values-in-a-multidimensional-array/9485",
    "description": "Forum discussion on idiomatic approaches to summing values in a multidimensional array in Rust.",
    "tags": [
      "arrays",
      "summing"
    ],
    "official": false,
    "year": 2017,
    "difficultyLevel": "intermediate",
    "duration": "variable",
    "interactivityLevel": "high",
    "free": true,
    "category": "forum"
  }
];

    // Formatting function for row details
    function format(d) {
        // `d` is the original data object for the row
        return (
            '<dl>' +
            '<dt></dt>' +
            '<dd>' +
            d.description +
            '</dd>' +
            '</dl>'
        );
    }

    function capitalizeFirstLetter(string) {
        return string.charAt(0).toUpperCase() + string.slice(1);
    }

    // Wait for dom content to be loaded with jquery
    $(document).ready(function () {
        const table = new DataTable('#data-table', {
            // Add dropdown filters for columns
            initComplete: function () {
                this.api()
                    .columns([1,7,9, 10])
                    .every(function () {
                        let column = this;
        
                        // Create select element
                        let select = document.createElement('select');
                        select.add(new Option(''));

                        // Add select element to the table header
                        $(column.header()).append(select);

        
                        // Apply listener for user change in value
                        select.addEventListener('change', function () {
                            var val = DataTable.util.escapeRegex(select.value);
        
                            column
                                .search(val ? '^' + val + '$' : '', true, false)
                                .draw();
                        });
        
                        // Add list of options
                        column.cells('', column[0]).render('display').sort().unique().each( function ( d, j ) { select.add(new Option(d)); });
                    });
            },
            paging: false,
            data: data,
            scrollCollapse: true,
            order: [[7, 'asc']],
            columns: [
                {
                    className: 'dt-control',
                    orderable: false,
                    data: null,
                    defaultContent: ''
                },
                {
                    data: 'category',
                    title: 'Category',
                    render: function (data, type, row) {
                        let symbol = data === 'article' ? '📝' : data === 'video' ? '📺' : data === 'guide' ? '📖' : data === 'forum' ? '💬' : data === 'talk' ? '🎤️': data === 'workshop' ? '🏋️' : data === 'project' ? '⚙'  : '📚';
                        return symbol + " " + capitalizeFirstLetter(data);
                    }
                },
                {
                    data: 'title',
                    title: 'Title',
                    render: function (data, type, row) {
                        return '<a target="_blank" rel="noopener noreferrer" href="' + row.url + '">' + row.title + '</a>';
                    }
                },
                {data: 'description', title: 'Description', visible: false},
                {
                    data: 'tags',
                    title: 'Tags',
                    // Format as `<code>` tags
                    render: function (data) {
                        return data.map((tag) => '<code style="margin:5px 0">' + tag + '</code>').join(' ');
                    },
                    visible: true
                },
                {data: 'official', title: 'Official', visible: false},
                {data: 'year', title: 'Year', visible: false},
                {
                    data: 'difficultyLevel',
                    title: 'Level',
                    // Render as emoji stars (beginner: 1, intermediate: 2, advanced: 3)
                    render (data) {
                        if (data === 'beginner' || data === 'all' || data === 'varied') {
                            return '⭐';
                        } else if (data === 'intermediate') {
                            return '⭐⭐';
                        } else if (data === 'advanced') {
                            return '⭐⭐⭐';
                        } else {
                            return data;
                        }
                    },

                },
                {data: 'duration', title: 'Duration', visible: false},
                {data: 'interactivityLevel', title: 'Interactivity',
                    render (data) {
                        if (data === 'low') {
                            return '⚙️';
                        } else if (data === 'medium') {
                            return '⚙️';
                        } else if (data === 'high') {
                            return '⚙️⚙️⚙️';
                        } else {
                            return data;
                        }
                    },
                },
                {
                   data: 'free',
                   title: 'Free',
                     render: function (data, type, row) {
                          return data ? '✅' : '❌';
                     }
                },
            ]
        });

        // Object to keep track of active filters
        var activeFilters = {};

        // Define a custom filtering function
        $.fn.dataTable.ext.search.push(function (settings, data, dataIndex) {
            // If no filters are active, show all rows
            if (Object.keys(activeFilters).length === 0) {
                return true;
            }

            // Get the tags for the current row (assuming they are in column 4)
            var tags = data[4];

            // All active filters must match
            return Object.keys(activeFilters).every(function (tag) {
                return tags.includes(tag);
            });
        });

        // Add event listener to code tags for toggling filter
        $('.dataTables_wrapper').on('click', 'code', function () {
            var tag = $(this).text();

            // Toggle the tag in active filters
            if (activeFilters[tag]) {
                delete activeFilters[tag];
                $('code').filter(function () {
                    return $(this).text().includes(tag);
                }).removeClass('active');
            } else {
                activeFilters[tag] = true;
                $('code').filter(function () {
                    return $(this).text().includes(tag);
                }).addClass('active');
            }

            if (Object.keys(activeFilters).length > 0) {
                /* set display: block to the reset button */
                $('.reset-filter').css('display', 'block');

            } else {
                /* set display: none to the reset button */
                $('.reset-filter').css('display', 'none');
            }

            // Trigger a redraw to apply the new filter
            table.draw();
        });

        // Add event listener for opening and closing details
        table.on('click', 'td.dt-control', function (e) {
            let tr = e.target.closest('tr');
            let row = table.row(tr);
        
            if (row.child.isShown()) {
                // This row is already open - close it
                row.child.hide();
            }
            else {
                // Open this row
                row.child(format(row.data())).show();
            }
        });

        // Reset all filters when clicking the reset button
        $('.reset-filter').on('click', function () {
            activeFilters = {};
            $('code').removeClass('active');
            $('.reset-filter').css('display', 'none');
            table.draw();
        });

        document.querySelectorAll('a.toggle-vis').forEach((el) => {
            el.addEventListener('click', function (e) {
                e.preventDefault();
        
                let columnIdx = e.target.getAttribute('data-column');
                let column = table.column(columnIdx);
        
                // Toggle the visibility
                column.visible(!column.visible());

                // Toggle the active class for the a.toggle-vis element
                e.target.classList.toggle('active');
            });
        });
    });

</script>


<div style="margin-bottom: 20px">
    <button class="reset-filter">Reset filters</button>
</div>

<div>
    Toggle column: 
    <a class="toggle-vis" data-column="4">Tags</a> - 
    <a class="toggle-vis" data-column="5">Official</a> - 
    <a class="toggle-vis" data-column="6">Year</a> - 
    <a class="toggle-vis" data-column="7">Level</a> - 
    <a class="toggle-vis" data-column="8">Duration</a> - 
    <a class="toggle-vis" data-column="9">Interactivity</a> - 
    <a class="toggle-vis" data-column="10">Access Type</a>
</div>

<table id="data-table" class="compact order-column hover stripe" style="width:100%">
</table>

<link rel="stylesheet" type="text/css" href="//cdn.datatables.net/1.13.7/css/jquery.dataTables.min.css" />

<style>
.dataTables_wrapper .dataTables_filter {
    margin: 20px 0 40px;
}

.dataTables_filter input[type="search"] {
    font-size: 18px;
    margin: 0 0 0 10px;
    padding: 8px;
    width: 350px;
    color: #111;
    border: 1px solid #111;
    background: rgb(255, 255, 255, 0.2);
}

.dataTables_wrapper code {
    cursor: pointer;
}

code {
    border-radius: 5px;
    padding: 5px;
    margin: 5px;
    font-size: 14px;
    font-family: monospace;
    color: #111;
    cursor: pointer;
}

code.active {
    color: white;
    background-color: #111;
}

.reset-filter {
    padding: 10px;
    display: none;
    margin-bottom: 20px;
    color: white;
    background-color: #111;
    border: none;
}

.toggle-vis.active {
    font-weight: bold;
}

/* If prefers color scheme is bright, change background color of code tags and filter input */
@media (prefers-color-scheme: dark) {

    .reset-filter {
        background-color: #ee3856;
    }

    /* border white with 20% opacity */
    .dataTables_filter input[type="search"] {
        border: 1px solid rgb(255, 255, 255, 0.6);
    }
}


</style>