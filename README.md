# Odin Advent of Code VS Code template

This is a basic template to get started with [Odin](https://odin-lang.org/) in VS Code. It's set up with Advent of Code in mind and makes use of these extensions:

* [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) (Linux or macOS)
* [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) (Windows)
* [Odin Language](https://marketplace.visualstudio.com/items?itemName=DanielGavin.ols)

Available tasks:

* **Init:** Create a package in the workspace with the provided directory name. This writes a `main.odin` with some boilerplate as well as an empty `input` file.
* **Build:** Build the package of the current file's directory.
* **Run:** Run the current file's package (must be built first with **Build**).
* **Test:** Build and run any tests available in the current file's package.

Available launch configurations:

* **Debug:** Build and debug the current file's package.
* **Debug tests:** Debug any tests available in the current file's package.

There are also Windows variants of the launch configurations using vsdbg.

> [!NOTE]
> The **Debug tests** launch configuration does not build the tests. This is because the only way to build the test executable is with `odin test`, which automatically executes the tests after building, meaning any test failures would prevent the debug adapter from starting a debug session.
>
> To work around this, you should manually run the **Test** task before using the **Debug tests** launch config to ensure it's using an up-to-date binary.

To get started, run the **Init** task to generate boilerplate for day 01.

Below is a template you can use for the readme contents.

# AoC 20XX

Solutions for [Advent of Code 20XX](https://adventofcode.com/20XX) in [Odin](https://odin-lang.org/).

| **Day** | **Part** | **Completed** |
|---------|----------|---------------|
| Day 1   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 2   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 3   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 4   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 5   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 6   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 7   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 8   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 9   | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 10  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 11  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 12  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 13  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 14  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 15  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 16  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 17  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 18  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 19  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 20  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 21  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 22  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 23  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 24  | Part 1   | ❌            |
|         | Part 2   | ❌            |
| Day 25  | Part 1   | ❌            |
|         | Part 2   | ❌            |
