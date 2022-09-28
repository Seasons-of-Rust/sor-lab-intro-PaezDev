# Summer of Rust Intro Lab

Hello! 👋

In this intro lab, we're going to make sure we have our Rust environment set up
correctly, and make sure we can push code to Git. We'll fix a simple test, and
make sure that it runs properly both locally and with tests on Github.

**Note** ❗: There might be some new things here that you haven't tried before.
If you get stuck at all, please reach out to me! I'll be more than happy to help
you through the process 👍

## 1. Set up your environment

Follow this page of the Rust book:
https://doc.rust-lang.org/book/ch01-01-installation.html

In this course, we'll be using VS Code with Rust Analyzer. This might not be
your preferred editor, but it makes it easy for me to help fix issues with [Live
Share](https://code.visualstudio.com/learn/collaboration/live-share), and [Rust
Analyzer](https://rust-analyzer.github.io/) brings great code analysis and
refactoring ability to VS Code.

Install VS Code: https://code.visualstudio.com/download

Install Rust Analyzer: https://rust-analyzer.github.io/manual.html#vs-code

## 2. Clone this repository

Either clone this repository with [Github Desktop](https://desktop.github.com/),
or with a preferred Git tool.

If you need help with this, please reach out to me on Discord!

## 3. Fix the code

For right now, the only issue with the code is a failing test. To see it
failing, try running `cargo test` from the main directory.

![](https://i.imgur.com/Z7x7IYz.png)

Try making a fix in the file `src/main.rs`, and making sure it works by running
`cargo test`.

Also try running the program with `cargo run`. This should print out the classic
"Hello, world!" 😁

## 4. Commit your changes

Commit your changes, and make sure the tests pass. To check, you should be able
to see them at this link:

`https://github.com/Summer-of-Rust/sor-lab-intro-<username>/actions`

where \<username\> is your GitHub username.

![](https://i.imgur.com/ZHqq49V.png)

*I get to see how tests are passing for each student, so I'll be able to check
in easily!*

## License

The Summer of Rust Labs is duel-licensed under either:

* MIT License ([LICENSE-MIT](LICENSE-MIT) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))
* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0))