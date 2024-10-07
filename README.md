# Odin Advent of Code VS Code template

This is a basic template to get started with [Odin](https://odin-lang.org/) in VS Code. It's set up with Advent of Code in mind.

You should have the **C/C++** and **Odin Language** extensions installed before using this.

Available tasks:

* **Init:** Create a package in the workspace with the provided directory name. This writes a `main.odin` with some boilerplate as well as an empty `input` file.
* **Build:** Build the package of the current file's package.
* **Test:** Build and run any tests available in the current file's package.

Available launch configurations:

* **Debug:** Build and debug the current file's package.
* **Debug tests:** Build and debug any tests available in the current file's package.

There are also Windows variants of the launch configurations using vsdbg.

> [!NOTE]
> The _Debug tests_ launch configuration will execute the tests twice - once without a debugger and again with, because `odin test` both builds and runs the tests. If I can figure out how to make it only build them, I'll update the config.

To get started, run the **Init** task to generate boilerplate for day 01.