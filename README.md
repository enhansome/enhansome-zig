# Awesome Zig with stars

[<img src="https://ziglang.org/zig-logo-light.svg" align="right" width="100">](https://ziglang.org)

[Zig](https://en.wikipedia.org/wiki/Zig_\(programming_language\)) is a general-purpose programming language and toolchain for maintaining robust, optimal and reusable software.

> \[!IMPORTANT]
> Zig is a rapidly evolving language. Some projects listed here may require a specific version of the Zig compiler (e.g., the latest `master` or a stable release like `0.13.0`). Always check the project's repository for compatibility.

[Contributing](contributing.md)

## Contents

<!-- toc -->

* [Fundamentals](#fundamentals)
  * [Learning Resources](#learning-resources)
  * [Community](#community)
  * [Text Editors](#text-editors)
  * [Linters](#linters)
  * [Documentation and Testing](#documentation-and-testing)
  * [Package and Version Manager](#package-and-version-manager)
  * [Utility](#utility)
  * [Linker](#linker)
  * [Performance Benchmark](#performance-benchmark)
* [Language Essentials](#language-essentials)
  * [Memory Allocator and Management](#memory-allocator-and-management)
  * [Data Structure and Algorithm](#data-structure-and-algorithm)
  * [String Processing](#string-processing)
  * [Parser Library](#parser-library)
  * [Logging Processing](#logging-processing)
  * [File Format Processing](#file-format-processing)
  * [Date, Time and Timezones](#date-time-and-timezones)
  * [Command Line and Argument Parser](#command-line-and-argument-parser)
  * [Finite State Machine](#finite-state-machine)
* [Systems Programming](#systems-programming)
  * [Asynchronous Runtime](#asynchronous-runtime)
  * [Multithreading](#multithreading)
  * [Embedded Development](#embedded-development)
  * [Operating Systems](#operating-systems)
  * [Compilers and Interpreters](#compilers-and-interpreters)
  * [Emulators](#emulators)
  * [Kernel and Containers](#kernel-and-containers)
* [Network & Web](#network--web)
  * [Network](#network)
  * [Browser](#browser)
  * [Web Framework](#web-framework)
  * [Web3 Framework](#web3-framework)
  * [WebAssembly](#webassembly)
* [Data & Science](#data--science)
  * [Database](#database)
  * [Linear Algebra](#linear-algebra)
  * [Scientific Computation](#scientific-computation)
  * [Machine Learning Framework](#machine-learning-framework)
  * [Large Language Model](#large-language-model)
  * [Machine Learning](#machine-learning)
  * [Encryption](#encryption)
  * [Sensor and Communication Interface](#sensor-and-communication-interface)
* [Multimedia & Graphics](#multimedia--graphics)
  * [GPU Computing](#gpu-computing)
  * [Graphics Library](#graphics-library)
  * [GUI](#gui)
  * [Game Development](#game-development)
  * [Audio Processing](#audio-processing)
  * [Image and Video Processing](#image-and-video-processing)
* [Interoperability](#interoperability)
  * [FFI Bindings](#ffi-bindings)
  * [Build with Zig](#build-with-zig)

<!-- tocstop -->

## Fundamentals

### Learning Resources

* [Zig Language Reference](https://ziglang.org/documentation/master/) - An introduction to the language with examples.
* [Zig In-depth Overview](https://ziglang.org/learn/overview/) - In-depth Overview of the Zig philosophy.
* [Zig Guide](https://zig.guide) - Get started with the Zig programming language.
* [Zig cookbook](https://cookbook.ziglang.cc/) - A collection of simple Zig programs that demonstrate good practices to accomplish common programming tasks.
* [Zig in 30 minutes](https://gist.github.com/ityonemo/769532c2017ed9143f3571e5ac104e50) - A half-hour to learn Zig.
* [Ziglings](https://ziglings.org/) - Learn the Zig programming language by fixing tiny broken programs.
* [Learning Zig](https://www.openmymind.net/learning_zig/) - This guide aims to make you comfortable with Zig. It assumes prior programming experience, though not in any particular language.
* [Zig 圣经](https://course.ziglang.cc/) - Chinese 简单、快速地学习 Zig.
* [Изучаем язык программирования Zig](https://zig-lang.ru/) - Russian textbook and blog about Zig.
* [Introduction to Zig - a project based book](https://pedropark99.github.io/zig-book/) - This is an open book by author `Pedro Duarte Faria` that provides an introduction to the Zig programming language, which is a new general-purpose, and low-level language for building robust and optimal software.
* [Systems Programming with Zig](https://www.manning.com/books/systems-programming-with-zig) - This book teaches how to write quality, useful Zig applications without relying on libraries or frameworks.
* [Zen of Zig](https://zenofzig.com) - Interactive Zig book, teaching from beginner to intermediate level with playgrounds and illustrations. Also available on [Leanpub](https://leanpub.com/zenofzig).

### Community

* [Zigistry/Zigistry](https://github.com/Zigistry/Zigistry) ⭐ 708 | 🐛 5 | 🌐 Svelte | 📅 2026-08-23 - A place where you can find all the libraries that suit your Zig lang needs.
* [Ziggit](https://ziggit.dev/) - The Zig forum.
* [Discord](https://discord.gg/zig) - Official Zig Discord server.
* [ZigCC](https://ziglang.cc) - Chinese Zig community.
* [Reddit](https://www.reddit.com/r/Zig/) - The Zig subreddit.
* [Zig Monthly](https://zig.news/) - Articles and news from the community.

### Text Editors

* [zigtools/zls](https://github.com/zigtools/zls) ⭐ 5,093 | 🐛 168 | 🌐 Zig | 📅 2026-08-14 - The @ziglang language server for all your Zig editor tooling needs, from autocomplete to goto-def! [installation](https://zigtools.org/zls/install/).
* [neurocyte/flow](https://github.com/neurocyte/flow) ⭐ 2,198 | 🐛 80 | 🌐 Zig | 📅 2026-08-27 - Flow Control - a programmer's text editor written in Zig.
* [zed-extensions/Zig](https://github.com/zed-extensions/zig) ⭐ 88 | 🐛 15 | 🌐 Rust | 📅 2026-06-07 - Zig extension for Zed editor.
* [jinzhongjia/zig-lamp](https://github.com/jinzhongjia/zig-lamp) ⭐ 42 | 🐛 2 | 🌐 Lua | 📅 2026-05-04 - Improve the Zig development experience in Neovim.
* [jinzhongjia/znvim](https://github.com/jinzhongjia/znvim) ⭐ 29 | 🐛 1 | 🌐 Zig | 📅 2026-02-06 - Neovim remote rpc client implementation with Zig.
* [Tetralux/sublime-zig](https://github.com/Tetralux/sublime-zig) ⭐ 3 | 🐛 0 | 📅 2025-09-23 - My own, more lightweight, syntax highlighting for the Zig Programming Language.
* [FalsePattern/ZigBrains](https://codeberg.org/FalsePattern/ZigBrains) - JetBrains IDEs (CLion, IntelliJ IDEA and others) plugin for Zig.
* [ziglang/sublime-zig-language](https://codeberg.org/ziglang/sublime-zig-language) - Zig language support for Sublime Text.
* [ziglang/vscode-zig](https://codeberg.org/ziglang/vscode-zig) - Zig language support for VSCode.
* [ziglang/zig.vim](https://codeberg.org/ziglang/zig.vim) - Vim configuration for Zig.
* [ziglang/zig-mode](https://codeberg.org/ziglang/zig-mode) - Zig mode for Emacs.

### Linters

* [DonIsaac/zlint](https://github.com/DonIsaac/zlint) ⭐ 307 | 🐛 35 | 🌐 Zig | 📅 2026-08-23 - Linter for the Zig programming language.
* [KurtWagner/zlinter](https://github.com/KurtWagner/zlinter) ⭐ 90 | 🐛 5 | 🌐 Zig | 📅 2026-08-20 - Zig linter that is integrated from source into your `build.zig`.
* [forketyfork/zwanzig](https://github.com/forketyfork/zwanzig) ⭐ 28 | 🐛 1 | 🌐 Zig | 📅 2026-08-28 - Static analyzer for Zig with CFG-based checks (leaks, double-free, optional unwrap, stack escapes).
* [mstdokumaci/zsort](https://github.com/mstdokumaci/zsort) ⭐ 23 | 🐛 0 | 🌐 Zig | 📅 2026-08-11 - Import sorter/organizer with pre-commit hook support.

### Documentation and Testing

* [kristoff-it/zig-doctest](https://github.com/kristoff-it/zig-doctest) ⭐ 79 | 🐛 1 | 🌐 Zig | 📅 2024-05-27 - A tool for testing snippets of code, useful for websites and books that talk about Zig.
* [sb2bg/marionette](https://github.com/sb2bg/marionette) ⭐ 79 | 🐛 1 | 🌐 Zig | 📅 2026-08-24 - Deterministic simulation testing for Zig with a `std.Io` implementation, letting you inject faults and replay failures from seeds.
* [ryo-zen/zig-docs-mcp](https://github.com/ryo-zen/zig-docs-mcp) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2026-06-04 - MCP server providing access to Zig language docs, stdlib references, and working code examples.

### Package and Version Manager

* [marler8997/zigup](https://github.com/marler8997/zigup) ⭐ 1,126 | 🐛 54 | 🌐 Zig | 📅 2025-06-14 - Download and manage Zig compilers.
* [justrach/nanobrew](https://github.com/justrach/nanobrew) ⭐ 1,111 | 🐛 12 | 🌐 Zig | 📅 2026-08-15 - A fast macOS package manager written in Zig.
* [tristanisham/zvm](https://github.com/tristanisham/zvm) ⭐ 1,052 | 🐛 2 | 🌐 Go | 📅 2026-08-27 - Lets you easily install/upgrade between different versions of Zig. ZLS install can be included. (written in Go).
* [nektro/zigmod](https://github.com/nektro/zigmod) ⭐ 941 | 🐛 19 | 🌐 Zig | 📅 2026-06-10 - A package manager for the Zig programming language.
* [mitchellh/zig-overlay](https://github.com/mitchellh/zig-overlay) ⭐ 542 | 🐛 10 | 🌐 Nix | 📅 2026-08-28 - Nix flake for the Zig compiler.
* [mlugg/setup-zig](https://github.com/mlugg/setup-zig) ⭐ 236 | 🐛 2 | 🌐 JavaScript | 📅 2026-01-19 - Install a Zig compiler for usage in GitHub Actions workflows.
* [Cloudef/zig2nix](https://github.com/Cloudef/zig2nix) ⭐ 188 | 🐛 7 | 🌐 Zig | 📅 2026-08-28 - Flake for packaging, building and running Zig projects.
* [indaco/malt](https://github.com/indaco/malt) ⭐ 157 | 🐛 1 | 🌐 Zig | 📅 2026-08-28 - Homebrew's whole ecosystem, none of its weight: a single Zig binary with native post\_install and a themeable TUI and CLI.
* [nix-community/zon2nix](https://github.com/nix-community/zon2nix) ⭐ 127 | 🐛 13 | 🌐 Zig | 📅 2026-06-19 - Convert dependencies in build.zig.zon files to Nix expressions.
* [vezel-dev/zig-sdk](https://github.com/vezel-dev/zig-sdk) ⭐ 110 | 🐛 18 | 🌐 C# | 📅 2026-08-15 - An MSBuild SDK for building Zig, C, and C++ projects using the Zig compiler.
* [zigtools/zpm](https://github.com/zigtools/zpm) ⭐ 104 | 🐛 0 | 🌐 Nix | 📅 2024-05-29 - Zig package manager helper.
* [asdf-community/asdf-zig](https://github.com/asdf-community/asdf-zig) ⭐ 81 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - Zig plugin for the [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,551 | 🐛 151 | 🌐 Go | 📅 2026-08-28 version manager.
* [hendriknielaender/zvm](https://github.com/hendriknielaender/zvm) ⭐ 73 | 🐛 4 | 🌐 Zig | 📅 2026-08-08 - A fast and simple Zig version manager written in Zig.
* [weezy20/zv](https://github.com/weezy20/zv) ⭐ 55 | 🐛 0 | 🌐 Rust | 📅 2026-06-11 - Fast Zig/ZLS version manager + project starter kit written in Rust. Binaries available for macOS/Windows/Linux.
* [Cloudef/nix-zig-stdenv](https://github.com/Cloudef/nix-zig-stdenv) ⚠️ Archived - Zig based cross-compiling toolchain.
* [jsomedon/night.zig](https://github.com/jsomedon/night.zig) ⭐ 33 | 🐛 1 | 🌐 Shell | 📅 2023-05-31 - Simple tool that just install & update Zig nightly.
* [lispking/zvm](https://github.com/lispking/zvm) ⭐ 33 | 🐛 5 | 🌐 Zig | 📅 2026-04-30 - A fast, dependency-free version manager for Zig written in Zig.
* [Getzig](https://github.com/matklad/hello-getzig) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2023-06-02 - An idea for a Zig version manager along the lines of gradle wrapper.
* [joachimschmidt557/zigpkgs](https://github.com/joachimschmidt557/zigpkgs) ⚠️ Archived - A collection of Zig packages built with Nix.
* [rosarp/nu-zigup](https://github.com/rosarp/nu-zigup) ⭐ 1 | 🐛 0 | 🌐 Nushell | 📅 2025-10-18 - Download & manage Zig compilers & zls binaries. Script is written in nushell.

### Utility

* [ghostty](https://github.com/ghostty-org/ghostty) ⭐ 60,386 | 🐛 239 | 🌐 Zig | 📅 2026-08-28 - Modern terminal emulator written in Zig.
* [NilsIrl/dockerc](https://github.com/NilsIrl/dockerc) ⭐ 4,915 | 🐛 25 | 🌐 Zig | 📅 2025-01-02 - Container image to single executable compiler.
* [zmx](https://github.com/neurosnap/zmx) ⭐ 2,089 | 🐛 29 | 🌐 Zig | 📅 2026-08-27 - Session persistence for terminal processes.
* [Illusionna/LocalTransfer](https://github.com/Illusionna/LocalTransfer) ⭐ 580 | 🐛 0 | 🌐 Zig | 📅 2026-08-09 - A fast cross-platform HTTP file server.
* [Arnau478/hevi](https://github.com/Arnau478/hevi) ⚠️ Archived - A minimalistic and modernized hex viewer, written in Zig.
* [BrookJeynes/jido](https://github.com/BrookJeynes/jido) ⭐ 82 | 🐛 2 | 🌐 Zig | 📅 2026-01-30 - Jido (formerly known as zte) is a small terminal file explorer, written in Zig.
* [midasdf/zt](https://github.com/midasdf/zt) ⭐ 62 | 🐛 0 | 🌐 Zig | 📅 2026-07-04 - Ultra-fast, minimal terminal emulator written in Zig with fbdev, X11, Wayland, and macOS backends.
* [zlist](https://github.com/here-Leslie-Lau/zlist) ⭐ 58 | 🐛 4 | 🌐 Zig | 📅 2026-08-28 - A simple, colorful alternative to ls built with Zig.
* [forketyfork/architect](https://github.com/forketyfork/architect) ⭐ 50 | 🐛 10 | 🌐 Zig | 📅 2026-08-28 - A flexible terminal grid for multi-agent AI workflows.
* [rockorager/zzdoc](https://github.com/rockorager/zzdoc) ⭐ 37 | 🐛 0 | 🌐 Zig | 📅 2026-05-01 - A scdoc-compatible manpage compiler for use in build.zig.
* [xcaeser/zig-dotenv](https://github.com/xcaeser/zig-dotenv) ⭐ 28 | 🐛 0 | 🌐 Zig | 📅 2026-08-21 - A powerful Zig library for loading, parsing, and managing environment variables from .env files.
* [Decryptu/zigdex](https://github.com/Decryptu/zigdex) ⭐ 22 | 🐛 0 | 🌐 Zig | 📅 2026-02-12 - Display Pokémon sprites in your terminal. A Zig rewrite of pokeget.
* [gaskam/workspace](https://github.com/gaskam/workspace) ⭐ 18 | 🐛 9 | 🌐 Zig | 📅 2025-07-05 - A powerful Zig-based tool to manage all your GitHub repositories with ease.
* [gauravnumber/move.zig](https://github.com/gauravnumber/move.zig) ⭐ 6 | 🐛 1 | 🌐 Zig | 📅 2025-05-28 - Zig-based mv with auto conflict resolution.
* [hspak/geteltorito-zig](https://github.com/hspak/geteltorito-zig) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2026-08-23 - Re-write of geteltorito in Zig.
* [mtxr/claude-switch](https://github.com/mtxr/claude-switch) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2026-06-11 - Swap between Claude (Code + Desktop) accounts on macOS with a single command. Credentials stored securely in macOS Keychain. Fully offline.
* [ktarasov/zigrep](https://github.com/ktarasov/zigrep) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2026-03-10 - A training project on the implementation of the similarity of the grep utility in Linux in the Zig language.
* [zdu](https://github.com/mjgil-zig/zdu) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2026-06-08 - A fast, low-memory TUI disk usage analyzer written in Zig.
* [ghext](https://github.com/charlesrocket/ghext) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2026-07-06 - A small library for extracting head commits from Git repositories.
* [deatil/zig-dotenv](https://github.com/deatil/zig-dotenv) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2026-06-19 - A parse and set env library for Zig.
* [bare-devcontainer/templates](https://github.com/bare-devcontainer/templates/tree/main/src/zig) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2026-08-28 - Security-focused Zig dev container with zls integration and a persistent build cache. The base image is available at [bare-devcontainer/images](https://github.com/bare-devcontainer/images/tree/main/zig) ⭐ 2 | 🐛 3 | 🌐 Shell | 📅 2026-08-28.
* [copyleftdev/whatthediff](https://github.com/copyleftdev/whatthediff) ⭐ 0 | 🐛 0 | 🌐 Zig | 📅 2026-07-19 - Deterministic semantic diff across many files at once — finds consensus, drift, and outliers with inspectable evidence, from configs and JSON/YAML/XML/PDF to executables (SSDeep-style fuzzy analysis). Zero dependencies.
* [fearedbliss/Honeydew](https://codeberg.org/fearedbliss/Honeydew) - A simple snapshot cleaner for OpenZFS written in Zig.
* [fearedbliss/Cantaloupe](https://codeberg.org/fearedbliss/Cantaloupe) - A simple backup replication tool for OpenZFS written in Zig.
* [rockorager.dev/lsr](https://tangled.sh/@rockorager.dev/lsr) - Efficient and fast `ls` alternative, written in Zig.
* [shepherdjerred/macos-cross-compiler](https://github.com/shepherdjerred/macos-cross-compiler) - Cross-compilation toolchain for Zig users to compile binaries for macOS on Linux.
* [nrdmn/ilo\_license\_key](https://github.com/nrdmn/ilo_license_key) - This library validates HP iLO license keys.
* [xsawyerx/vind](https://codeberg.org/xsawyerx/vind) - A tiny embeddable full-text search engine that also has a CLI app and a built-in service.

### Linker

* [kubkon/bold](https://github.com/kubkon/bold) ⚠️ Archived - A drop-in replacement for Apple’s system linker `ld`.

### Performance Benchmark

* [andrewrk/poop](https://github.com/andrewrk/poop) ⭐ 2,032 | 🐛 29 | 🌐 Zig | 📅 2026-05-04 - CLI Performance Observer written in Zig.
* [ziglang/gotta-go-fast](https://github.com/ziglang/gotta-go-fast) ⚠️ Archived - Performance Tracking for Zig.
* [hendriknielaender/zBench](https://github.com/hendriknielaender/zBench) ⭐ 223 | 🐛 8 | 🌐 Zig | 📅 2026-06-24 - Simple benchmarking library.
* [zackradisic/rust-vs-zig](https://github.com/zackradisic/rust-vs-zig) ⭐ 211 | 🐛 2 | 🌐 Rust | 📅 2023-06-21 - This is an experiment to evaluate Rust vs. Zig by writing a bytecode interpreter with GC in both languages and comparing them.
* [CoalNova/BasicCompare](https://github.com/CoalNova/BasicCompare) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2023-05-23 - A basic comparative analysis of C, C++, Rust, and Zig.
* [lucascompython/zigXrustXc](https://github.com/lucascompython/zigXrustXc) ⭐ 4 | 🐛 0 | 🌐 Zig | 📅 2025-05-08 - Performance of Zig vs Rust vs C.

## Language Essentials

### Memory Allocator and Management

* [DutchGhost/zorrow](https://github.com/DutchGhost/zorrow) ⭐ 119 | 🐛 0 | 🌐 Zig | 📅 2023-02-04 - Borrowchecker in Zig. This is a userlevel implementation of borrowchk in Zig.
* [fengb/zee\_alloc](https://github.com/fengb/zee_alloc) ⚠️ Archived - Tiny Zig allocator primarily targeting WebAssembly.
* [Aandreba/zigrc](https://github.com/Aandreba/zigrc) ⭐ 92 | 🐛 0 | 🌐 Zig | 📅 2026-04-24 - Zig reference-counted pointers inspired by Rust's Rc and Arc. [aandreba.github.io/zigrc/](https://aandreba.github.io/zigrc/).
* [suirad/adma](https://github.com/suirad/adma) ⭐ 66 | 🐛 0 | 🌐 Zig | 📅 2021-01-27 - A general purpose, multithreaded capable slab allocator for Zig.
* [dweiller/zimalloc](https://github.com/dweiller/zimalloc) ⭐ 48 | 🐛 7 | 🌐 Zig | 📅 2025-10-07 - A general purpose allocator for Zig, inspired by [mimalloc](https://github.com/microsoft/mimalloc) ⭐ 13,333 | 🐛 318 | 🌐 C | 📅 2026-08-22.
* [Hejsil/zig-gc](https://github.com/Hejsil/zig-gc) ⚠️ Archived - A super simple mark-and-sweep garbage collector written in Zig.
* [rdunnington/zig-stable-array](https://github.com/rdunnington/zig-stable-array) ⭐ 31 | 🐛 0 | 🌐 Zig | 📅 2026-05-22 - Address-stable array with a max size that allocates directly from virtual memory.
* [mdsteele/ziegfried](https://github.com/mdsteele/ziegfried) ⭐ 28 | 🐛 0 | 🌐 Zig | 📅 2021-07-21 - A general-purpose memory allocator for Zig.
* [dweiller/zig-composable-allocators](https://github.com/dweiller/zig-composable-allocators) ⭐ 21 | 🐛 0 | 🌐 Zig | 📅 2025-12-07 - Comptime-generic composable allocators.
* [hmusgrave/zcirc](https://github.com/hmusgrave/zcirc) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2022-02-13 - A dynamic circular buffer allocator for Zig.
* [bcrist/Zig-TempAllocator](https://github.com/bcrist/Zig-TempAllocator) ⭐ 9 | 🐛 0 | 🌐 Zig | 📅 2026-06-27 - Arena allocator for interactive programs and simulations.
* [suirad/Seal](https://github.com/suirad/Seal) ⭐ 8 | 🐛 0 | 📅 2018-11-26 - An allocator that wraps another allocator and detects if memory is leaked after usage.
* [nsmryan/zig\_sealed\_and\_compact](https://github.com/nsmryan/zig_sealed_and_compact) ⭐ 7 | 🐛 2 | 🌐 Zig | 📅 2024-11-04 - Zig functions for memory management.
* [rvcas/mpool](https://github.com/rvcas/mpool) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2021-08-30 - A memory pool library written in Zig.
* [DutchGhost/maybeuninit](https://github.com/DutchGhost/maybeuninit) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2020-09-30 - MaybeUninit in Zig.

### Data Structure and Algorithm

* [TheAlgorithms/Zig](https://github.com/TheAlgorithms/Zig) ⭐ 406 | 🐛 0 | 🌐 Zig | 📅 2026-08-15 - Collection of Algorithms implemented in Zig.
* [yamafaktory/hypergraphz](https://github.com/yamafaktory/hypergraphz) ⭐ 130 | 🐛 0 | 🌐 Zig | 📅 2026-05-17 - HypergraphZ - A Hypergraph Implementation in Zig.
* [mitchellh/zig-graph](https://github.com/mitchellh/zig-graph) ⭐ 123 | 🐛 1 | 🌐 Zig | 📅 2022-09-13 - Directed graph data structure for Zig.
* [deckarep/ziglang-set](https://github.com/deckarep/ziglang-set) ⭐ 107 | 🐛 4 | 🌐 Zig | 📅 2026-04-23 - A generic and general purpose Set implementation for the Zig language.
* [williamw520/toposort](https://github.com/williamw520/toposort) ⭐ 97 | 🐛 0 | 🌐 Zig | 📅 2025-12-13 - Topological sort library that produces topological ordered nodes and dependence-free subsets.
* [kristoff-it/zig-cuckoofilter](https://github.com/kristoff-it/zig-cuckoofilter) ⭐ 83 | 🐛 0 | 🌐 Zig | 📅 2023-01-10 - Production-ready Cuckoo Filters for any C ABI compatible target.
* [hello-algo-zig](https://github.com/codingonion/hello-algo-zig) ⭐ 82 | 🐛 0 | 🌐 Zig | 📅 2023-07-16 - Zig programming language codes for the famous public project [《Hello, Algorithm》|《 Hello，算法 》](https://github.com/krahets/hello-algo) ⭐ 129,654 | 🐛 42 | 🌐 Java | 📅 2026-08-17 about data structures and algorithms.
* [Srekel/zig-sparse-set](https://github.com/Srekel/zig-sparse-set) ⭐ 81 | 🐛 1 | 🌐 Zig | 📅 2024-06-15 - Sparse sets for Zig, supporting both SOA and AOS style.
* [alichraghi/zort](https://github.com/alichraghi/zort) ⭐ 80 | 🐛 1 | 🌐 Zig | 📅 2026-08-13 - Zort: Sorting algorithms in Zig.
* [BraedonWooding/Lazy-Zig](https://github.com/BraedonWooding/Lazy-Zig) ⭐ 48 | 🐛 2 | 🌐 Zig | 📅 2023-12-08 - Linq in Zig.
* [CogitatorTech/ordered](https://github.com/CogitatorTech/ordered) ⭐ 38 | 🐛 4 | 🌐 Zig | 📅 2026-06-27 - A sorted collection library (sorted sets and sorted maps) for Zig.
* [OrlovEvgeny/lo.zig](https://github.com/OrlovEvgeny/lo.zig) ⭐ 36 | 🐛 1 | 🌐 Zig | 📅 2026-07-10 - A Lodash-style utility library for Zig with zero hidden allocations and lazy iterator-first design.
* [ramsyana/Zig-Math-Algorithms](https://github.com/ramsyana/Zig-Math-Algorithms) ⭐ 21 | 🐛 0 | 🌐 Zig | 📅 2025-08-05 - A collection of math algorithms in Zig—primes, Fibonacci, GCD, Euler's Totient, & more! Perfect for learning Zig & math.
* [Sahnvour/zig-containers](https://github.com/Sahnvour/zig-containers) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2021-05-12 - A set of containers for Zig.
* [DutchGhost/ArrayVec](https://github.com/DutchGhost/ArrayVec) ⭐ 17 | 🐛 0 | 🌐 Zig | 📅 2020-07-14 - A library with an ArrayList-like API, except its a static array.
* [emekoi/deque.zig](https://github.com/emekoi/deque.zig) ⚠️ Archived - A lock free chase-lev deque for Zig.
* [booniepepper/zig-data-structures](https://github.com/booniepepper/zig-data-structures) ⭐ 17 | 🐛 1 | 🌐 Zig | 📅 2023-07-29 - Home to some experiments in Zig data structures.
* [jakubgiesler/VecZig](https://github.com/jakubgiesler/VecZig) ⚠️ Archived - Vector implementation in Zig.
* [BarabasGitHub/LZig4](https://github.com/BarabasGitHub/LZig4) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2025-09-23 - Implementing lz4 in Zig.
* [marijnfs/zigtimsort](https://github.com/marijnfs/zigtimsort) ⭐ 8 | 🐛 0 | 🌐 Zig | 📅 2020-06-24 - TimSort implementation for Zig.
* [JacobCrabill/btree.zig](https://github.com/JacobCrabill/btree.zig) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2023-05-23 - Behavior Tree library written in Zig.
* [ok-ryoko/multiring.zig](https://github.com/ok-ryoko/multiring.zig) - Singly linked, cyclic and hierarchical abstract data type in Zig.
* [kobolds-io/stdx](https://gitlab.com/kobolds-io/stdx) - Helpful extensions to the Zig standard library.

### String Processing

* [JakubSzark/zig-string](https://github.com/JakubSzark/zig-string) ⭐ 576 | 🐛 2 | 🌐 Zig | 📅 2026-06-24 - Zig String (A UTF-8 String Library). This library is a UTF-8 compatible string library for the Zig programming language.
* [jecolon/zigstr](https://github.com/jecolon/zigstr) ⭐ 114 | 🐛 0 | 📅 2023-10-01 - Zigstr is a UTF-8 string type for Zig programs.
* [ziglibs/string-searching](https://github.com/ziglibs/string-searching) ⭐ 27 | 🐛 1 | 🌐 Zig | 📅 2026-06-28 - String(not limited to \[]const u8)-searching algorithms in Zig.
* [hwu1001/zig-string](https://github.com/hwu1001/zig-string) ⭐ 21 | 🐛 6 | 🌐 Zig | 📅 2021-02-01 - A String struct made for Zig.
* [shaik-abdul-thouhid/ezi-code](https://github.com/shaik-abdul-thouhid/ezi-code) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2026-08-23 - A comprehensive Unicode library for Zig covering UTF-8/16/32 encoding, normalization (NFC/NFD/NFKC/NFKD), segmentation (grapheme/word/sentence/line), casing, BiDi, collation (UCA/DUCET), and character properties. No dependencies.
* [atman/zg](https://codeberg.org/atman/zg) - Provides Unicode text processing for Zig projects. It works correctly with the Russian language and other languages.

### Parser Library

* [tree-sitter/zig-tree-sitter](https://github.com/tree-sitter/zig-tree-sitter) ⭐ 121 | 🐛 0 | 🌐 Zig | 📅 2026-06-27 - Zig bindings to the [Tree-sitter](https://tree-sitter.github.io/zig-tree-sitter/) parsing library.
* [OrlovEvgeny/zigquery](https://github.com/OrlovEvgeny/zigquery) ⭐ 12 | 🐛 1 | 🌐 Zig | 📅 2026-07-17 - Zig HTML parser and CSS selector engine for DOM querying and manipulation.
* [eoan-ermine/zig-strparse](https://github.com/eoan-ermine/zig-strparse) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2026-07-18 - Generic string parsing library for Zig.

### Logging Processing

* [chrischtel/nexlog](https://github.com/chrischtel/nexlog) ⭐ 110 | 🐛 0 | 🌐 Zig | 📅 2026-01-15 - A modern, feature-rich logging library for Zig with thread-safety, file rotation, and colorized output.
* [muhammad-fiaz/logly.zig](https://github.com/muhammad-fiaz/logly.zig) ⭐ 69 | 🐛 5 | 🌐 Zig | 📅 2026-08-07 - A modern, production-grade, high-performance structured logging library for Zig, built for speed and scalability.
* [emekoi/log.zig](https://github.com/emekoi/log.zig) ⭐ 28 | 🐛 2 | 🌐 Zig | 📅 2020-05-07 - A thread-safe logging library for Zig.
* [ross-weir/logex](https://github.com/ross-weir/logex) ⭐ 15 | 🐛 6 | 🌐 Zig | 📅 2026-06-08 - A library that enriches `std.log` logging with additional functionality and features.
* [sam701/slog](https://github.com/sam701/slog) ⭐ 12 | 🐛 5 | 🌐 Zig | 📅 2025-09-07 - A configurable, structured logging package for Zig with support for hierarchical loggers.
* [g41797/syslog](https://github.com/g41797/syslog) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2025-12-25 - A [syslog](https://en.wikipedia.org/wiki/Syslog) RFC5424 client library.

### File Format Processing

* [Arwalk/zig-protobuf](https://github.com/Arwalk/zig-protobuf) ⭐ 429 | 🐛 21 | 🌐 Zig | 📅 2026-07-14 - A protobuf 3 implementation for Zig.
* [ziglibs/known-folders](https://github.com/ziglibs/known-folders) ⭐ 321 | 🐛 2 | 🌐 Zig | 📅 2026-07-21 - Provides access to well-known folders across several operating systems.
* [kubkon/zig-yaml](https://github.com/kubkon/zig-yaml) ⭐ 295 | 🐛 35 | 🌐 Zig | 📅 2026-01-13 - YAML parser for Zig.
* [tiehuis/zig-regex](https://github.com/tiehuis/zig-regex) ⭐ 250 | 🐛 9 | 🌐 Zig | 📅 2026-01-18 - A regex implementation for the Zig programming language.
* [jecolon/ziglyph](https://github.com/jecolon/ziglyph) ⭐ 214 | 🐛 0 | 📅 2023-10-01 - Unicode text processing for the Zig programming language.
* [karlseguin/log.zig](https://github.com/karlseguin/log.zig) ⭐ 193 | 🐛 0 | 🌐 Zig | 📅 2026-06-20 - A structured logger for Zig.
* [ezequielramis/zimdjson](https://github.com/ezequielramis/zimdjson) ⭐ 173 | 🐛 8 | 🌐 Zig | 📅 2026-04-18 - Parsing gigabytes of JSON per second. Zig port of simdjson with fundamental features.
* [ziglibs/s2s](https://github.com/ziglibs/s2s) ⭐ 163 | 🐛 3 | 🌐 Zig | 📅 2026-05-03 - A Zig binary serialization format.
* [kivikakk/koino](https://github.com/kivikakk/koino) ⭐ 158 | 🐛 6 | 🌐 Zig | 📅 2026-02-26 - CommonMark + GFM compatible Markdown parser and renderer.
* [sam701/zig-toml](https://github.com/sam701/zig-toml) ⭐ 131 | 🐛 4 | 🌐 Zig | 📅 2026-08-07 - Zig TOML (v1.0.0) parser.
* [aeronavery/zig-toml](https://github.com/aeronavery/zig-toml) ⭐ 116 | 🐛 5 | 🌐 Zig | 📅 2024-08-18 - A TOML parser written in Zig.
* [mitchellh/zig-libxml2](https://github.com/mitchellh/zig-libxml2) ⭐ 87 | 🐛 1 | 🌐 Zig | 📅 2023-08-02 - Libxml2 built using Zig build system.
* [OrlovEvgeny/serde.zig](https://github.com/OrlovEvgeny/serde.zig) ⭐ 83 | 🐛 3 | 🌐 Zig | 📅 2026-08-11 - Comptime serialization framework for Zig supporting JSON, MessagePack, TOML, YAML, ZON, and CSV.
* [travisstaloch/protobuf-zig](https://github.com/travisstaloch/protobuf-zig) ⚠️ Archived - A protocol buffers implementation in Zig.
* [mattyhall/tomlz](https://github.com/mattyhall/tomlz) ⭐ 48 | 🐛 5 | 🌐 Zig | 📅 2024-09-28 - A well-tested TOML parsing library for Zig.
* [kivikakk/libpcre.zig](https://github.com/kivikakk/libpcre.zig) ⭐ 37 | 🐛 0 | 🌐 Zig | 📅 2026-02-04 - Zig bindings to libpcre.
* [rawC1nnamon/elfy.zig](https://github.com/rawC1nnamon/elfy.zig) ⭐ 21 | 🐛 1 | 🌐 Zig | 📅 2026-06-30 - Tiny and fast ELF parsing library for Zig.
* [nektro/zig-json](https://github.com/nektro/zig-json) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2026-08-24 - A JSON library for inspecting arbitrary values.
* [peymanmortazavi/csv-zero](https://github.com/peymanmortazavi/csv-zero) ⭐ 16 | 🐛 6 | 🌐 Zig | 📅 2026-07-29 - Zero allocation, SIMD-accelerated CSV iterator and emitter for Zig.
* [vi/zigmkv](https://github.com/vi/zigmkv) ⭐ 13 | 🐛 0 | 🌐 Zig | 📅 2025-09-27 - A (WIP) Matroska/webm (mkv) parser in Zig.
* [xcaeser/glob.zig](https://github.com/xcaeser/glob.zig) ⭐ 11 | 🐛 0 | 🌐 Zig | 📅 2025-10-31 - Fast and reliable glob pattern matching in pure Zig.
* [nDimensional/zig-flatbuffers](https://github.com/nDimensional/zig-flatbuffers) ⭐ 11 | 🐛 0 | 🌐 Zig | 📅 2026-06-01 - FlatBuffers codegen for Zig, in Zig.
* [thejoshwolfe/hexdump-zip](https://github.com/thejoshwolfe/hexdump-zip) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2025-03-30 - Produce an annotated hexdump of a zipfile.
* [goto-bus-stop/ziguid](https://github.com/goto-bus-stop/ziguid) ⭐ 7 | 🐛 0 | 🌐 Zig | 📅 2023-06-25 - GUID parsing/stringifying with Zig.
* [zoptia/zoptia0regex](https://github.com/zoptia/zoptia0regex) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2026-07-12 - A regular-expression (regex) library — a faithful, linear-time port of Go's regexp (RE2), proven byte-for-byte identical to Go via \~30k differential tests.
* [MahBestBro/regex](https://github.com/MahBestBro/regex) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2023-04-12 - A single file regex library written in and for Zig.
* [shaik-abdul-thouhid/ezi-gex](https://github.com/shaik-abdul-thouhid/ezi-gex) ⭐ 4 | 🐛 0 | 🌐 Zig | 📅 2026-08-23 - Unicode-aware regex engine for Zig with runtime and comptime compilation, full \p{} Unicode property support, named captures, and custom pluggable backends (engines).
* [winksaville/zig-parse-number](https://github.com/winksaville/zig-parse-number) ⭐ 2 | 🐛 1 | 🌐 Zig | 📅 2019-03-05 - Implement ParseNumber which can parse any TypeId.Int or TypeId.Float.
* [demizer/markzig](https://github.com/demizer/markzig) - Pure Zig Markdown Parser.
* [javiorfo/prettizy](https://github.com/javiorfo/prettizy) - Zig library to prettify JSON and XML strings.
* [javiorfo/zig-epub](https://github.com/javiorfo/zig-epub) - Minimal Zig library for creating EPUB files.
* [kobolds-io/gnoll](https://gitlab.com/kobolds-io/gnoll) - Zig application configuration handled well.
* [mattnite/protobuf](https://github.com/mattnite/protobuf) - A pure-Zig Protocol Buffers library with a standalone .proto parser, build-time code generator, and transport-agnostic RPC stub generation. Supports proto2 and proto3.
* [MASS4/MEGA4/KTX2](https://gitlab.com/mass4org/mega4/ktx2) - Engine-independent KTX2 texture reader for Zig, decoding compressed and Basis Universal textures to GPU-ready images.
* [MASS4/MEGA4/GUID](https://gitlab.com/mass4org/mega4/guid) - Standalone GUID/UUID library supporting `RFC 4122` v4 and `RFC 9562` v6 (time-ordered) with optional `serde` integration.

### Date, Time and Timezones

* [karlseguin/zul](https://github.com/karlseguin/zul) ⭐ 306 | 🐛 1 | 🌐 Zig | 📅 2026-05-24 - Some date/time handling functionality among the other functionality.
* [rockorager/zeit](https://github.com/rockorager/zeit) ⭐ 233 | 🐛 5 | 🌐 Zig | 📅 2026-08-17 - Generic date/time library, including time zone loading and conversion.
* [frmdstryr/zig-datetime](https://github.com/frmdstryr/zig-datetime) ⭐ 119 | 🐛 4 | 🌐 Zig | 📅 2026-03-09 - A datetime module for Zig with an API similar to Python's Arrow.
* [nektro/zig-time](https://github.com/nektro/zig-time) ⭐ 76 | 🐛 1 | 🌐 Zig | 📅 2026-08-24 - A date and time parsing and formatting library for Zig.
* [clickingbuttons/datetime](https://github.com/clickingbuttons/datetime) ⭐ 18 | 🐛 2 | 🌐 Zig | 📅 2025-05-09 - Generic Date, Time, and DateTime library.
* [deatil/zig-time](https://github.com/deatil/zig-time) ⭐ 11 | 🐛 0 | 🌐 Zig | 📅 2026-07-04 - A date and time parse and format library for Zig.
* [leroycep/zig-tzif](https://github.com/leroycep/zig-tzif) ⭐ 9 | 🐛 0 | 🌐 Zig | 📅 2024-07-26 - [TZif](https://datatracker.ietf.org/doc/html/rfc8536) parser that also handles POSIX timezone strings.
* [scento/zig-date](https://github.com/scento/zig-date) ⭐ 7 | 🐛 0 | 🌐 Zig | 📅 2023-03-26 - Time and date for Zig. Zig-date is a date and time library for the Zig, inspired by the popular Rust library [chrono](https://github.com/chronotope/chrono) ⭐ 3,901 | 🐛 197 | 🌐 Rust | 📅 2026-08-03.
* [leroycep/chrono-zig](https://github.com/leroycep/chrono-zig) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2024-04-24 - Zig port of the Rust chrono crate.
* [travisstaloch/date-zig](https://github.com/travisstaloch/date-zig) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2023-12-17 - Fast calendar algorithms ported to Zig (Cassio Neri's [EAF](https://github.com/cassioneri/eaf) ⭐ 59 | 🐛 0 | 🌐 C++ | 📅 2026-06-27).
* [FObersteiner/zdt](https://github.com/FObersteiner/zdt) - Timezoned Datetime in Zig. For learning purposes.

### Command Line and Argument Parser

* [Hejsil/zig-clap](https://github.com/Hejsil/zig-clap) ⭐ 1,604 | 🐛 7 | 🌐 Zig | 📅 2026-06-13 - A simple and easy to use command line argument parser library for Zig.
* [sam701/zig-cli](https://github.com/sam701/zig-cli) ⭐ 351 | 🐛 7 | 🌐 Zig | 📅 2026-06-11 - A simple package for building command line apps in Zig.
* [xcaeser/zli](https://github.com/xcaeser/zli) ⭐ 333 | 🐛 1 | 🌐 Zig | 📅 2026-08-19 - Zig command-line interfaces made easy. A blazing fast CLI framework. Build ergonomic, high-performance command-line tools with Zig.
* [MasterQ32/zig-args](https://github.com/MasterQ32/zig-args) ⭐ 307 | 🐛 10 | 🌐 Zig | 📅 2026-05-21 - Simple-to-use argument parser with struct-based config.
* [PrajwalCH/yazap](https://github.com/PrajwalCH/yazap) ⭐ 209 | 🐛 9 | 🌐 Zig | 📅 2026-02-01 - The ultimate Zig library for seamless command line parsing. Effortlessly handles options, subcommands, and custom arguments with ease. [prajwalch.github.io/yazap](https://prajwalch.github.io/yazap).
* [00JCIV00/cova](https://github.com/00JCIV00/cova) ⭐ 151 | 🐛 11 | 🌐 Zig | 📅 2026-05-22 - Commands, Options, Values, Arguments. A simple yet robust cross-platform command line argument parsing library for Zig.
* [jiacai2050/zigcli](https://github.com/jiacai2050/zigcli) ⭐ 136 | 🐛 8 | 🌐 Zig | 📅 2026-07-19 - A toolkit for building command lines programs in Zig.
* [CogitatorTech/chilli](https://github.com/CogitatorTech/chilli) ⭐ 57 | 🐛 2 | 🌐 Zig | 📅 2026-07-19 - Chilli 🌶️ is a minimalistic CLI framework for Zig.
* [judofyr/parg](https://github.com/judofyr/parg) ⭐ 51 | 🐛 0 | 🌐 Zig | 📅 2026-01-11 - Lightweight argument parser for Zig.
* [BanchouBoo/accord](https://github.com/BanchouBoo/accord) ⭐ 42 | 🐛 0 | 🌐 Zig | 📅 2025-08-07 - A simple argument parser for Zig.
* [kioz-wang/zargs](https://github.com/kioz-wang/zargs) ⭐ 32 | 🐛 7 | 🌐 Zig | 📅 2026-05-05 - Another Comptime-argparse for Zig.
* [GabrieleInvernizzi/zig-prompter](https://github.com/GabrieleInvernizzi/zig-prompter) ⭐ 26 | 🐛 0 | 🌐 Zig | 📅 2025-07-11 - A flexible library for building interactive command line prompts.
* [muhammad-fiaz/args.zig](https://github.com/muhammad-fiaz/args.zig) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2026-08-12 - Fast, powerful, and developer-friendly CLI argument parsing library for Zig.
* [plutowang/zlap](https://github.com/plutowang/zlap) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2026-05-03 - A declarative, fluent, and type-safe command-line argument parser for Zig with subcommand support, inspired by Rust's clap.

### Finite State Machine

* [cryptocode/zigfsm](https://github.com/cryptocode/zigfsm) ⭐ 196 | 🐛 0 | 🌐 Zig | 📅 2026-04-17 - Zigfsm is a [finite state machine](https://en.wikipedia.org/wiki/Finite-state_machine) library for Zig.

## Systems Programming

### Asynchronous Runtime

* [mitchellh/libxev](https://github.com/mitchellh/libxev) ⭐ 3,577 | 🐛 60 | 🌐 Zig | 📅 2026-07-17 - A cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io\_uring or epoll), macOS (kqueue), and WebAssembly + WASI. Available as both a Zig and C API.
* [kprotty/zap](https://github.com/kprotty/zap) ⭐ 551 | 🐛 1 | 🌐 Zig | 📅 2025-01-02 - An asynchronous runtime with a focus on performance and resource efficiency.
* [lithdew/pike](https://github.com/lithdew/pike) ⭐ 143 | 🐛 13 | 🌐 Zig | 📅 2023-03-25 - Async I/O for Zig.
* [Thomvanoorschot/backstage](https://github.com/Thomvanoorschot/backstage) ⭐ 46 | 🐛 3 | 🌐 Zig | 📅 2025-08-08 - Concurrent Actor framework.
* [neurocyte/thespian](https://github.com/neurocyte/thespian) ⭐ 34 | 🐛 0 | 🌐 C++ | 📅 2026-08-16 - An actor library for Zig, C & C++ applications.
* [floscodes/coroutinez](https://github.com/floscodes/coroutinez) ⭐ 8 | 🐛 0 | 🌐 Zig | 📅 2026-05-28 - A small runtime for running tasks using coroutines in Zig.

### Multithreading

* [g41797/mailbox](https://github.com/g41797/mailbox) ⭐ 121 | 🐛 0 | 🌐 Zig | 📅 2026-06-06 - A convenient inter-thread communication mechanism.

### Embedded Development

* [ZigEmbeddedGroup/microzig](https://github.com/ZigEmbeddedGroup/microzig) ⭐ 2,265 | 🐛 79 | 🌐 Zig | 📅 2026-08-18 - Unified abstraction layer and HAL for several microcontrollers.
* [markfirmware/zig-bare-metal-raspberry-pi](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) ⭐ 106 | 🐛 6 | 🌐 Zig | 📅 2020-01-19 - Bare metal raspberry pi program written in Zig.
* [lupyuen/pinephone-nuttx](https://github.com/lupyuen/pinephone-nuttx) ⭐ 102 | 🐛 0 | 🌐 Zig | 📅 2026-08-28 - Apache NuttX RTOS for PinePhone. Apache NuttX is a lightweight Real-Time Operating System (RTOS) that runs on PINE64 PinePhone. [lupyuen.github.io/articles/what](https://lupyuen.github.io/articles/what).
* [ZigEmbeddedGroup/raspberrypi-rp2040](https://github.com/ZigEmbeddedGroup/raspberrypi-rp2040) ⚠️ Archived - MicroZig Hardware Support Package for Raspberry Pi RP2040.
* [ZigEmbeddedGroup/regz](https://github.com/ZigEmbeddedGroup/regz) ⚠️ Archived - Generate Zig code from ATDF or SVD files for microcontrollers.
* [tralamazza/embedded\_zig](https://github.com/tralamazza/embedded_zig) ⭐ 83 | 🐛 3 | 🌐 Zig | 📅 2020-10-29 - A minimal Zig embedded ARM example (STM32F103 blue pill).
* [lupyuen/zig-bl602-nuttx](https://github.com/lupyuen/zig-bl602-nuttx) ⭐ 40 | 🐛 0 | 🌐 Zig | 📅 2022-10-18 - Zig on RISC-V BL602 with Apache NuttX RTOS and LoRaWAN.
* [markfirmware/zig-bare-metal-microbit](https://github.com/markfirmware/zig-bare-metal-microbit) ⭐ 38 | 🐛 4 | 🌐 Zig | 📅 2021-10-24 - Bare metal microbit program written in Zig.
* [nmeum/zig-riscv-embedded](https://github.com/nmeum/zig-riscv-embedded) ⭐ 35 | 🐛 0 | 🌐 Zig | 📅 2023-11-23 - Experimental Zig-based CoAP node for the HiFive1 RISC-V board.
* [justinbalexander/svd2zig](https://github.com/justinbalexander/svd2zig) ⭐ 32 | 🐛 5 | 🌐 Zig | 📅 2021-04-04 - Convert System View Description (svd) files to Zig headers for baremetal development.
* [mqttiotstuff/iotmonitor](https://github.com/mqttiotstuff/iotmonitor) ⭐ 25 | 🐛 2 | 🌐 Zig | 📅 2024-04-21 - PainLess, Monitor and State server for iot mqtt devices, and software agents. This daemon permit to maintain the execution of constellations of mqtt devices and associated agents.
* [Elara6331/zig-gpio](https://github.com/Elara6331/zig-gpio) ⭐ 25 | 🐛 1 | 🌐 Zig | 📅 2024-08-19 - A Zig library for controlling GPIO lines on Linux systems.
* [eastonman/zesty-core](https://github.com/eastonman/zesty-core) ⭐ 23 | 🐛 0 | 🌐 Zig | 📅 2021-12-21 - A RISC-V OS written in Zig.
* [leecannon/zig-sbi](https://github.com/leecannon/zig-sbi) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2026-06-23 - Zig wrapper around the RISC-V SBI specification.
* [ringtailsoftware/zeptolibc](https://github.com/ringtailsoftware/zeptolibc) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2025-10-23 - Essential libc functions in Zig for freestanding targets.
* [ZigEmbeddedGroup/stmicro-stm32](https://github.com/ZigEmbeddedGroup/stmicro-stm32) ⚠️ Archived - HAL for stm32 (STMicro) devices.
* [yvt/zig-armv8m-test](https://github.com/yvt/zig-armv8m-test) ⚠️ Archived - Example Zig-based app for Armv8-M + TrustZone.
* [hspak/brightnessztl](https://github.com/hspak/brightnessztl) ⭐ 10 | 🐛 1 | 🌐 Zig | 📅 2026-08-23 - A CLI to control device backlight.

### Operating Systems

* [ZystemOS/Pluto](https://github.com/ZystemOS/pluto) ⭐ 737 | 🐛 34 | 🌐 Zig | 📅 2024-01-03 - An x86 kernel written in Zig.
* [AndreaOrru/zen](https://github.com/AndreaOrru/zen) ⭐ 533 | 🐛 1 | 🌐 Zig | 📅 2025-09-21 - Experimental operating system written in Zig.
* [marlersoft/zigwin32](https://github.com/marlersoft/zigwin32) ⭐ 449 | 🐛 30 | 🌐 Zig | 📅 2026-07-23 - A complete autogenerated set of Zig bindings for the Win32 API.
* [jzck/kernel-zig](https://github.com/jzck/kernel-zig) ⭐ 438 | 🐛 2 | 🌐 Zig | 📅 2023-08-21 - Hobby x86 kernel Zig.
* [TalonFloof/zorroOS](https://github.com/TalonFloof/zorroOS) ⭐ 152 | 🐛 1 | 🌐 Zig | 📅 2025-03-16 - Hobby operating system written in Zig.
* [b0bleet/zvisor](https://github.com/b0bleet/zvisor) ⭐ 147 | 🐛 1 | 🌐 Zig | 📅 2024-08-13 - Zvisor is an open-source hypervisor written in the Zig programming language, which provides a modern and efficient approach to systems programming.
* [CascadeOS/CascadeOS](https://github.com/CascadeOS/CascadeOS) ⭐ 127 | 🐛 13 | 🌐 Zig | 📅 2026-08-15 - General purpose operating system targeting standard desktops and laptops.
* [pbui-project/pbui-main](https://github.com/pbui-project/pbui-main) ⭐ 100 | 🐛 19 | 🌐 Zig | 📅 2021-07-14 - The PBUI (POSIX-compliant BSD/Linux Userland Implementation) project is a free and open source project intended to implement some standard library toolsets in the Zig programming language.
* [nrdmn/uefi-examples](https://github.com/nrdmn/uefi-examples) ⭐ 84 | 🐛 2 | 🌐 Zig | 📅 2023-08-22 - UEFI examples in Zig.
* [davidgm94/birth](https://github.com/davidgm94/birth) ⚠️ Archived - Rise: an attempt to write a better operating system.
* [rafaelbreno/zig-os](https://github.com/rafaelbreno/zig-os) ⭐ 56 | 🐛 0 | 🌐 Zig | 📅 2026-06-09 - A simple OS written in Zig following Philipp Oppermann's posts [Writing an OS in Rust](https://os.phil-opp.com/).
* [sjdh02/trOS](https://github.com/sjdh02/trOS) ⭐ 55 | 🐛 0 | 🌐 Zig | 📅 2019-03-14 - Tiny aarch64 baremetal OS thingy.
* [iguessthislldo/georgios](https://github.com/iguessthislldo/georgios) ⭐ 53 | 🐛 1 | 🌐 Zig | 📅 2025-10-26 - Hobby Operating System.
* [nrdmn/uefi-paint](https://github.com/nrdmn/uefi-paint) ⭐ 50 | 🐛 0 | 🌐 Zig | 📅 2019-09-20 - UEFI-bootable touch paint app.
* [momumi/x86-zig](https://github.com/momumi/x86-zig) ⭐ 31 | 🐛 1 | 🌐 Zig | 📅 2021-04-30 - Library for assembling x86 in Zig (WIP).
* [DorianXGH/Lukarnel](https://github.com/DorianXGH/Lukarnel) ⭐ 23 | 🐛 1 | 🌐 Zig | 📅 2020-06-12 - A microkernel in Zig with rust microservices.
* [liampwll/zig-efi-os](https://github.com/liampwll/zig-efi-os) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2020-05-22 - Zig-efi-os.
* [jacobperron/rclzig](https://github.com/jacobperron/rclzig) ⭐ 15 | 🐛 1 | 🌐 Zig | 📅 2022-05-16 - ROS 2 client library in Zig.
* [ZeeBoppityZagZiggity/ZBZZ.OS](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS) ⭐ 14 | 🐛 1 | 🌐 Zig | 📅 2020-04-26 - An operating system built with RISCV and Zig.
* [coderonion/MinimalRoboticsPlatform](https://github.com/coderonion/MinimalRoboticsPlatform) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2023-05-20 - MRP is a minimal microkernel that supports the most fundamental robotic domains. It's thought for highly integrated robotics development.
* [a1393323447/zcore-os](https://github.com/a1393323447/zcore-os) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2024-04-15 - A RISC-V OS written in Zig. rCore-OS translated in Zig language.
* [javiorfo/zig-syslinfo](https://github.com/javiorfo/zig-syslinfo) - Linux sysinfo Zig library.

### Compilers and Interpreters

* [Aro](https://github.com/Vexu/arocc) ⭐ 1,802 | 🐛 47 | 🌐 Zig | 📅 2026-08-18 - A C compiler with the goal of providing fast compilation and low memory usage with good diagnostics.
* [buzz](https://github.com/buzz-language/buzz) ⭐ 1,529 | 🐛 80 | 🌐 Zig | 📅 2026-08-27 - A small/lightweight statically typed scripting language.
* [fubark/cyber](https://github.com/fubark/cyber) ⭐ 1,518 | 🐛 37 | 🌐 Zig | 📅 2025-12-21 - Fast and concurrent scripting.
* [Vexu/bog](https://github.com/Vexu/bog) ⭐ 603 | 🐛 6 | 🌐 Zig | 📅 2025-03-10 - Small, strongly typed, embeddable language.
* [squeek502/zua](https://github.com/squeek502/zua) ⭐ 212 | 🐛 0 | 🌐 Zig | 📅 2024-03-10 - An implementation of Lua 5.1 in Zig, for learning purposes.
* [Element 0](https://github.com/Element0Lang/element-0) ⭐ 29 | 🐛 3 | 🌐 Zig | 📅 2026-05-16 - A small embeddable Lisp dialect written in Zig.
* [Fun](https://github.com/omdxp/fun) ⭐ 25 | 🐛 1 | 🌐 Zig | 📅 2026-08-28 - A statically-typed language that transpiles to C, combining safety and performance with C's efficiency.
* [fury](https://github.com/fury-lang/fury) ⭐ 15 | 🐛 10 | 🌐 Zig | 📅 2025-03-11 - A gradual, safe systems language.
* [zish](https://github.com/rotkonetworks/zish) ⭐ 7 | 🐛 0 | 🌐 Zig | 📅 2026-08-28 - An opinionated shell written in Zig.
* [dawk](https://codeberg.org/triallax/dawk) - Reasonably fast POSIX-compliant AWK implementation with good diagnostics.

### Emulators

* [fengb/fundude](https://github.com/fengb/fundude) ⚠️ Archived - Gameboy emulator: Zig -> WebAssembly.
* [Ronsor/riscv-zig](https://github.com/Ronsor/riscv-zig) ⭐ 54 | 🐛 0 | 🌐 Zig | 📅 2025-11-13 - A RISC-V emulator written in Zig.
* [paoda/zba](https://github.com/paoda/zba) ⭐ 48 | 🐛 0 | 🌐 Zig | 📅 2026-03-02 - Game Boy Advance Emulator. Yes, I'm awful with project names.
* [ringtailsoftware/zig-minirv32](https://github.com/ringtailsoftware/zig-minirv32) ⭐ 41 | 🐛 0 | 🌐 Zig | 📅 2025-10-26 - Zig RISC-V emulator with Linux and baremetal examples.
* [isaachier/gbemu](https://github.com/isaachier/gbemu) ⭐ 25 | 🐛 0 | 🌐 Zig | 📅 2019-09-25 - Zig Game Boy emulator.
* [leecannon/zriscv](https://github.com/leecannon/zriscv) ⚠️ Archived - RISC-V emulator in Zig.
* [tiehuis/zig-gameboy](https://github.com/tiehuis/zig-gameboy) ⭐ 14 | 🐛 0 | 🌐 Zig | 📅 2019-05-29 - A gameboy emulator in Zig.
* [GrooveStomp/chip8-zig](https://github.com/GrooveStomp/chip8-zig) ⭐ 9 | 🐛 0 | 🌐 Zig | 📅 2020-04-22 - A CHIP-8 emulator written in Zig.
* [jtgoen/zig-chip-8](https://github.com/jtgoen/zig-chip-8) ⭐ 3 | 🐛 1 | 🌐 Zig | 📅 2024-12-30 - Zig Implementation of a Chip-8 Emulator.
* [emekoi/c8](https://github.com/emekoi/c8) ⚠️ Archived - Chip 8 emulator in Zig.
* [omdxp/chip8](https://github.com/omdxp/chip8) ⭐ 0 | 🐛 0 | 🌐 Zig | 📅 2025-06-21 - Chip8 Emulator in Zig.

### Kernel and Containers

* [zbpf](https://github.com/tw4452852/zbpf) ⭐ 277 | 🐛 5 | 🌐 Zig | 📅 2026-04-19 - Writing eBPF in Zig.
* [oci-spec-zig](https://github.com/navidys/oci-spec-zig) ⭐ 13 | 🐛 0 | 🌐 Zig | 📅 2026-06-22 - OCI (Open Container Initiative) runtime, image and distribution spec in Zig.

## Network & Web

### Network

* [karlseguin/http.zig](https://github.com/karlseguin/http.zig) ⭐ 1,591 | 🐛 15 | 🌐 Zig | 📅 2026-08-26 - An HTTP/1.1 server for Zig.
* [sleep3r/mtproto.zig](https://github.com/sleep3r/mtproto.zig) ⭐ 1,472 | 🐛 0 | 🌐 Zig | 📅 2026-08-27 - High-performance Telegram MTProto proxy written in Zig.
* [tardy-org/zzz](https://github.com/tardy-org/zzz) ⭐ 774 | 🐛 17 | 🌐 Zig | 📅 2026-08-24 - A framework for writing performant and reliable networked services in Zig. Supports HTTP and HTTPS.
* [Vexu/routez](https://github.com/Vexu/routez) ⚠️ Archived - HTTP server for Zig.
* [ducdetronquito/h11](https://github.com/ducdetronquito/h11) ⚠️ Archived - I/O-free HTTP/1.1 implementation inspired by hyper/h11.
* [muhammad-fiaz/httpx.zig](https://github.com/muhammad-fiaz/httpx.zig) ⭐ 86 | 🐛 6 | 🌐 Zig | 📅 2026-08-28 - Production-ready HTTP/1.x/2/3 client and server runtime for Zig with proxy support, concurrency, and protocol primitives.
* [YUX/floo](https://github.com/YUX/floo) ⭐ 61 | 🐛 1 | 🌐 Zig | 📅 2026-08-19 - High-throughput, token-authenticated tunneling built in Zig. Multiplexes TCP and UDP services through a Noise-protected transport with 29+ Gbit/s encrypted throughput.
* [Vexu/zuri](https://github.com/Vexu/zuri) ⚠️ Archived - URI parser for Zig.
* [williamw520/zigjr](https://github.com/williamw520/zigjr) ⭐ 50 | 🐛 1 | 🌐 Zig | 📅 2025-12-19 - A lightweight Zig library for building JSON-RPC 2.0 applications.
* [lun-4/zigdig](https://github.com/lun-4/zigdig) ⭐ 44 | 🐛 1 | 🌐 Zig | 📅 2026-02-20 - Naive dns client library in Zig.
* [Nyarum/zigtgshka](https://github.com/Nyarum/zigtgshka) ⭐ 36 | 🐛 13 | 🌐 Zig | 📅 2025-05-27 - Memory-safe, high-performance Telegram Bot API library for Zig with zero-cost abstractions and comprehensive examples.
* [rktr1998/zig-wol](https://github.com/rktr1998/zig-wol) ⭐ 35 | 🐛 9 | 🌐 Zig | 📅 2026-07-19 - Wake-on-lan CLI written in Zig.
* [ringtailsoftware/misshod](https://github.com/ringtailsoftware/misshod) ⭐ 32 | 🐛 0 | 🌐 Zig | 📅 2025-01-06 - Experimental minimalist SSH client and server in Zig.
* [Thomvanoorschot/wire](https://github.com/Thomvanoorschot/wire) ⭐ 25 | 🐛 0 | 🌐 Zig | 📅 2025-05-27 - Basic TCP Server/Client able to run concurrently on a single thread.
* [lun-4/ziget](https://github.com/lun-4/ziget) ⭐ 24 | 🐛 0 | 🌐 Zig | 📅 2026-06-29 - Simple wget in Zig without libc.
* [vascocosta/zircon](https://github.com/vascocosta/zircon) ⭐ 24 | 🐛 2 | 🌐 Zig | 📅 2026-05-14 - A simple IRC library written in Zig.
* [euantorano/ip.zig](https://github.com/euantorano/ip.zig) ⭐ 22 | 🐛 0 | 🌐 Zig | 📅 2019-10-31 - A Zig library for working with IP Addresses.
* [marler8997/netpunch](https://github.com/marler8997/netpunch) ⭐ 21 | 🐛 0 | 🌐 Zig | 📅 2024-10-06 - Punch Protocol.
* [zquic](https://github.com/ch4r10t33r/zquic) ⭐ 17 | 🐛 3 | 🌐 Zig | 📅 2026-07-10 - QUIC transport protocol (RFC 9000/9001/9002) with HTTP/3 and QPACK support, written in pure Zig with zero C dependencies.
* [cocky-punch/raft](https://github.com/cocky-punch/raft) ⭐ 13 | 🐛 0 | 🌐 Zig | 📅 2025-11-24 - Raft consensus algorithm implemented in Zig.
* [connectFree/ZigZag](https://github.com/connectFree/ZigZag) ⭐ 12 | 🐛 0 | 📅 2018-10-16 - Noise Framework implementation in Zig Language for use in EVER/IP and WireGuard.
* [Thomvanoorschot/async\_zocket](https://github.com/Thomvanoorschot/async_zocket) ⭐ 12 | 🐛 0 | 🌐 Zig | 📅 2025-07-31 - Async WebSocket library for Zig, able to run concurrently on a single thread.
* [zig-nostr/nostr](https://github.com/zig-nostr/nostr) ⭐ 8 | 🐛 5 | 🌐 Zig | 📅 2026-08-28 - The Nostr protocol natively in Zig: secp256k1/Schnorr keys, events, relay transport with the outbox model, a local-first LMDB event store, NIP-46 remote signing, and more.
* [gernest/url](https://github.com/gernest/url) ⭐ 7 | 🐛 0 | 🌐 Zig | 📅 2019-10-24 - This is RFC 3986 compliant url parser for Zig.
* [g41797/beanstalkz](https://github.com/g41797/beanstalkz) ⭐ 7 | 🐛 0 | 🌐 Zig | 📅 2026-06-18 - Thread-safe client library for [beanstalkd](https://pmatseykanets.github.io/beanstalkd-docs/), a queue for background job processing.
* [zigtls](https://github.com/Geun-Oh/zigtls) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2026-03-04 - Zig-native TLS Implementation library for edge/load-balancer event loops, with BoGo strict, interop, and reliability gates.
* [remeh/statsd-zig](https://github.com/remeh/statsd-zig) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2025-03-19 - Basic DogStatsD UDP/UDS server supporting gauges and counters and sending these metrics to Datadog.
* [mstroecker/zig-robotstxt](https://github.com/mstroecker/zig-robotstxt) ⭐ 2 | 🐛 1 | 🌐 Zig | 📅 2019-11-09 - Lightweight Docker image for serving a disallow robots.txt file using the Zig programming language.
* [zora](https://github.com/user529/zora) ⭐ 0 | 🐛 0 | 🌐 Zig | 📅 2026-07-20 - Telegram bot server that runs hot-reloadable Lua 5.4 rules, with coroutine-based async I/O, SQLite-backed state, and a durable scheduler. Targets Linux and FreeBSD.
* [zat.dev/zat](https://tangled.org/zat.dev/zat) - AT Protocol building blocks for zig.
* [zigcord](https://codeberg.org/lipfang/zigcord) - Typed Discord API for Zig.

### Browser

* [lightpanda-io/browser](https://github.com/lightpanda-io/browser) ⭐ 34,296 | 🐛 104 | 🌐 Zig | 📅 2026-08-28 - Headless browser designed for AI and automation.

### Web Framework

* [zigzap/zap](https://github.com/zigzap/zap) ⭐ 3,413 | 🐛 28 | 🌐 C | 📅 2026-06-01 - Blazingly fast web backends in Zig.
* [kristoff-it/zine](https://github.com/kristoff-it/zine) ⭐ 1,549 | 🐛 54 | 🌐 Zig | 📅 2026-08-12 - Static Site Generator written in Zig.
* [jetzig-framework/jetzig](https://github.com/jetzig-framework/jetzig) ⭐ 1,508 | 🐛 40 | 🌐 Zig | 📅 2026-06-12 - Jetzig is a web framework written in Zig.
* [cztomsik/tokamak](https://github.com/cztomsik/tokamak) ⭐ 632 | 🐛 5 | 🌐 Zig | 📅 2026-08-28 - Web framework that leverages dependency injection for clean, modular application development.
* [karlseguin/websocket.zig](https://github.com/karlseguin/websocket.zig) ⭐ 517 | 🐛 10 | 🌐 Zig | 📅 2026-08-23 - A WebSocket implementation for Zig.
* [nurulhudaapon/zx](https://github.com/nurulhudaapon/zx) ⭐ 327 | 🐛 32 | 🌐 Zig | 📅 2026-08-13 - A full-stack web framework for Zig.
* [zon-dev/zinc](https://github.com/zon-dev/zinc) ⭐ 184 | 🐛 2 | 🌐 Zig | 📅 2026-04-15 - Zinc is a web framework written in pure Zig with a focus on high performance, usability, security, and extensibility.
* [nikneym/ws](https://github.com/nikneym/ws) ⭐ 71 | 🐛 5 | 🌐 Zig | 📅 2024-02-22 - WebSocket library for Zig ⚡.
* [floscodes/zerve](https://github.com/floscodes/zerve) ⭐ 68 | 🐛 0 | 🌐 Zig | 📅 2026-04-06 - A simple framework for writing web services in Zig.
* [llllOllOOll/spider](https://github.com/llllOllOOll/spider) ⭐ 46 | 🐛 0 | 🌐 C | 📅 2026-08-07 - A web framework for Zig with a focus on ergonomics and performance.
* [shritesh/zigfmt-web](https://github.com/shritesh/zigfmt-web) ⭐ 43 | 🐛 2 | 🌐 HTML | 📅 2020-01-07 - Zig fmt on the web.
* [leroycep/zig-jwt](https://github.com/leroycep/zig-jwt) ⭐ 42 | 🐛 2 | 🌐 Zig | 📅 2025-08-21 - JSON Web Tokens for Zig.
* [uzyn/passcay](https://github.com/uzyn/passcay) ⭐ 37 | 🐛 0 | 🌐 Zig | 📅 2026-06-23 - Secure Passkey authentication (WebAuthn) library for Zig.
* [by-nir/aws-lambda-zig](https://github.com/by-nir/aws-lambda-zig) ⭐ 21 | 🐛 1 | 🌐 Zig | 📅 2026-08-26 - Super-fast AWS Lambda runtime for Zig.
* [deatil/zig-jwt](https://github.com/deatil/zig-jwt) ⭐ 21 | 🐛 0 | 🌐 Zig | 📅 2026-08-25 - A JWT(JSON Web Token) library for Zig.
* [im-ng/zero](https://github.com/im-ng/zero) ⭐ 21 | 🐛 3 | 🌐 Zig | 📅 2026-08-28 - Simple and opinionated web framework written in Zig and aims to make microservices development in Zig easier.
* [kivikakk/htmlentities.zig](https://github.com/kivikakk/htmlentities.zig) ⭐ 14 | 🐛 0 | 🌐 Zig | 📅 2026-02-01 - HTML entity data for Zig.
* [deatil/zig-totp](https://github.com/deatil/zig-totp) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2026-07-02 - A TOTP(Time-based One-Time Password) library for Zig.
* [deatil/zig-paseto](https://github.com/deatil/zig-paseto) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2026-08-25 - A PASETO (Platform-Agnostic SEcurity TOkens) library for Zig.
* [GuneshRaj/zigar](https://github.com/GuneshRaj/zigar) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2025-12-13 - Zigar is a web application framework for Zig that supports ASP / JSP-like template syntax with ASP-style tags.
* [weebsocket](https://codeberg.org/lipfang/weebsocket) - WebSocket client for Zig, with minimal allocation and a `std.http`-like API.
* [brmassa/liquidz](https://gitlab.com/brmassa/liquidz) - A [Liquid template language](https://shopify.github.io/liquid/) implementation in Zig.

### Web3 Framework

* [Syndica/sig](https://github.com/Syndica/sig) ⭐ 403 | 🐛 93 | 🌐 Zig | 📅 2026-07-31 - A Solana Zig RPC Client implementation.
* [lithdew/rheia](https://github.com/lithdew/rheia) ⭐ 292 | 🐛 6 | 🌐 Zig | 📅 2022-02-28 - A Blockchain written in Zig.
* [Raiden1411/zabi](https://github.com/Raiden1411/zabi) ⭐ 116 | 🐛 8 | 🌐 Zig | 📅 2026-05-26 - Zabi aims to add support for interacting with Ethereum or any compatible EVM based chain.
* [blockblaz/zeam](https://github.com/blockblaz/zeam) ⭐ 97 | 🐛 105 | 🌐 Zig | 📅 2026-07-23 - A [Beam Chain](https://github.com/blockblaz/zeam/blob/main/resources/beam.md) ⭐ 97 | 🐛 105 | 🌐 Zig | 📅 2026-07-23 written in Zig.
* [keep-starknet-strange/ziggy-starkdust](https://github.com/keep-starknet-strange/ziggy-starkdust) ⭐ 88 | 🐛 18 | 🌐 Zig | 📅 2024-08-20 - A Zig implementation of Cairo VM for Cairo, the STARK powered provable language.
* [StrobeLabs/eth.zig](https://github.com/StrobeLabs/eth.zig) ⭐ 82 | 🐛 16 | 🌐 C | 📅 2026-08-19 - Pure Zig Ethereum client library. Zero dependencies, comptime-first.
* [jsign/verkle-crypto](https://github.com/jsign/verkle-crypto) ⭐ 42 | 🐛 0 | 🌐 Zig | 📅 2024-06-14 - Cryptography for Ethereum Verkle Trees.
* [zen-eth/zig-libp2p](https://github.com/zen-eth/zig-libp2p) ⭐ 39 | 🐛 7 | 🌐 Zig | 📅 2026-07-27 - Zig implementation of [libp2p](https://libp2p.io/), a modular network stack that allows you to build your own peer-to-peer applications.
* [blockblaz/ssz.zig](https://github.com/blockblaz/ssz.zig) ⭐ 34 | 🐛 16 | 🌐 Zig | 📅 2026-08-11 - A Zig implementation of the [SSZ serialization protocol](https://github.com/ethereum/eth2.0-specs/blob/dev/ssz/simple-serialize.md) ⭐ 3,957 | 🐛 62 | 🌐 Python | 📅 2026-08-28.
* [iskyd/walle](https://github.com/iskyd/walle) ⭐ 25 | 🐛 5 | 🌐 Zig | 📅 2025-04-11 - A Bitcoin Wallet written in Zig.
* [ch4r10t33r/zigeth](https://github.com/ch4r10t33r/zigeth) ⭐ 21 | 🐛 16 | 🌐 Zig | 📅 2026-07-07 - Zig package to interact with Ethereum (inspired from alloy-rs).
* [blockblaz/hash-zig](https://github.com/blockblaz/hash-zig) ⭐ 11 | 🐛 2 | 🌐 Zig | 📅 2026-03-06 - A pure Zig implementation of hash based signatures inspired from the rust implementation.
* [zen-eth/multiformats-zig](https://github.com/zen-eth/multiformats-zig) ⭐ 9 | 🐛 4 | 🌐 Zig | 📅 2026-06-29 - This is the Zig implementation of the multiformats [spec](https://github.com/multiformats/multiformats) ⭐ 580 | 🐛 20 | 📅 2025-04-28.
* [Ultra-Code/recblock](https://github.com/Ultra-Code/recblock) ⭐ 9 | 🐛 1 | 🌐 Zig | 📅 2026-04-23 - Blockchain for a record management and money transfer system.
* [cryptuon/zig-evm](https://github.com/cryptuon/zig-evm) ⭐ 8 | 🐛 1 | 🌐 Zig | 📅 2026-07-16 - A high-performance, embeddable EVM with wave-based parallel transaction execution, work-stealing thread pool, 96+ opcodes, and precompiles (blake2f, BN254, ripemd160). Targets L2/Rollup execution with C/Python/Rust/JS FFI bindings.
* [ryo-zen/zeicoin](https://github.com/ryo-zen/zeicoin) ⭐ 3 | 🐛 1 | 🌐 Zig | 📅 2026-05-22 - A fast and lightweight Layer 1 Blockchain written in Zig.
* [EclesioMeloJunior/libp2p-zig](https://github.com/EclesioMeloJunior/libp2p-zig) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2023-08-19 - A [libp2p](https://libp2p.io/) written in Zig.
* [gballet/zevem](https://github.com/gballet/zevem/) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2025-12-12 - Ethereum Virtual Machine written in Zig.

### WebAssembly

* [zware](https://github.com/malcolmstill/zware) ⭐ 413 | 🐛 17 | 🌐 Zig | 📅 2026-06-21 - Zig WebAssembly Runtime Engine. zware is a library for executing WebAssembly embedded in [Zig](https://ziglang.org/) programs.
* [mitchellh/zig-js](https://github.com/mitchellh/zig-js) ⭐ 286 | 🐛 5 | 🌐 Zig | 📅 2026-04-17 - Access the JS host environment from Zig compiled to WebAssembly.
* [zwasm](https://github.com/zwasm/zwasm) ⭐ 170 | 🐛 48 | 🌐 Zig | 📅 2026-08-28 - From-scratch WebAssembly runtime in Zig. Full WebAssembly 3.0 with 100% spec conformance, WASI 0.1/0.2/0.3, and interpreter + JIT (arm64/x86\_64) + AOT backends.
* [zig-wasm-dom](https://github.com/shritesh/zig-wasm-dom) ⭐ 165 | 🐛 3 | 🌐 Zig | 📅 2023-01-05 - Zig + WebAssembly + JS + DOM.
* [wazm](https://github.com/fengb/wazm) ⚠️ Archived - WebAssembly Zig Machine.
* [sleibrock/zigtoys](https://github.com/sleibrock/zigtoys) ⭐ 120 | 🐛 0 | 🌐 Zig | 📅 2024-07-08 - All about Zig + WebAssembly and seeing what we can do. [sleibrock.github.io/zigtoys/](https://sleibrock.github.io/zigtoys/).
* [zig-wasi](https://github.com/andrewrk/zig-wasi) ⭐ 115 | 🐛 0 | 🌐 C | 📅 2023-04-06 - Minimal WASI Interpreter.
* [zigwasm/wasmtime-zig](https://github.com/zigwasm/wasmtime-zig) ⭐ 86 | 🐛 4 | 🌐 Zig | 📅 2022-08-19 - Zig embedding of Wasmtime.
* [ringtailsoftware/zig-wasm-audio-framebuffer](https://github.com/ringtailsoftware/zig-wasm-audio-framebuffer) ⭐ 80 | 🐛 0 | 🌐 C++ | 📅 2025-10-24 - Examples of integrating Zig and WebAssembly (and C) for audio and graphics on the web (including DOOM).
* [meheleventyone/zig-wasm-test](https://github.com/meheleventyone/zig-wasm-test) ⭐ 57 | 🐛 2 | 🌐 Zig | 📅 2024-07-03 - A minimal WebAssembly example using Zig's build system.
* [andrewrk/lua-in-the-browser](https://github.com/andrewrk/lua-in-the-browser) ⭐ 36 | 🐛 2 | 🌐 C | 📅 2019-05-16 - Using Zig to build lua for webassembly.
* [zigwasm/wasm-zig](https://github.com/zigwasm/wasm-zig) ⭐ 29 | 🐛 2 | 🌐 Zig | 📅 2023-08-22 - Common WebAssembly runtime binding to C API.
* [oltdaniel/zig-js-interplay](https://github.com/oltdaniel/zig-js-interplay) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-17 - Seamless integration of Zig and JavaScript in WebAssembly.

## Data & Science

### Database

* [tigerbeetle](https://github.com/tigerbeetle/tigerbeetle) ⭐ 16,916 | 🐛 107 | 🌐 Zig | 📅 2026-08-25 - The distributed financial accounting database designed for mission critical safety and performance. [tigerbeetle.com](https://tigerbeetle.com/).
* [vrischmann/zig-sqlite](https://github.com/vrischmann/zig-sqlite) ⭐ 617 | 🐛 6 | 🌐 C | 📅 2026-07-24 - Zig-SQLite is a small wrapper around SQLite's C API, making it easier to use with Zig.
* [karlseguin/pg.zig](https://github.com/karlseguin/pg.zig) ⭐ 590 | 🐛 4 | 🌐 Zig | 📅 2026-08-26 - Native PostgreSQL driver / client for Zig.
* [kristoff-it/zig-okredis](https://github.com/kristoff-it/zig-okredis) ⭐ 292 | 🐛 3 | 🌐 Zig | 📅 2026-07-18 - Zero-allocation Client for Redis 6+.
* [kristoff-it/redis-cuckoofilter](https://github.com/kristoff-it/redis-cuckoofilter) ⭐ 233 | 🐛 4 | 🌐 Zig | 📅 2020-03-05 - Hashing-function agnostic Cuckoo filters for Redis.
* [karlseguin/zuckdb.zig](https://github.com/karlseguin/zuckdb.zig) ⭐ 188 | 🐛 2 | 🌐 C | 📅 2026-04-20 - A DuckDB driver for Zig.
* [speed2exe/myzql](https://github.com/speed2exe/myzql) ⭐ 74 | 🐛 4 | 🌐 Zig | 📅 2026-08-19 - MySQL and MariaDB driver in native Zig.
* [leroycep/sqlite-zig](https://github.com/leroycep/sqlite-zig) ⭐ 69 | 🐛 2 | 🌐 C | 📅 2024-04-23 - This repository has Zig bindings for SQLite. It tries to make the SQLite c API more Ziggish.
* [seqor/seqor](https://github.com/seqor/seqor) ⭐ 59 | 🐛 0 | 🌐 Zig | 📅 2026-08-21 - Seqor is a cost-effective, Loki compatible database for logs.
* [nDimensional/zig-sqlite](https://github.com/nDimensional/zig-sqlite) ⭐ 52 | 🐛 3 | 🌐 Zig | 📅 2026-08-25 - Simple, low-level, explicitly-typed SQLite bindings for Zig.
* [mailmug/zentropy](https://github.com/mailmug/zentropy) ⭐ 50 | 🐛 5 | 🌐 Zig | 📅 2025-11-18 - High-performance, lightweight key-value store (Redis alternative).
* [mjoerussell/zdb](https://github.com/mjoerussell/zdb) ⭐ 27 | 🐛 6 | 🌐 Zig | 📅 2024-02-15 - A library for interacting with databases in Zig.
* [zeno-core/zeno](https://github.com/zeno-core/zeno) ⭐ 26 | 🐛 0 | 🌐 Zig | 📅 2026-03-19 - High-performance embedded key-value storage engine with ART index, WAL, and sharded concurrency.
* [Axion](https://github.com/YUX/axion) ⭐ 25 | 🐛 2 | 🌐 Zig | 📅 2025-12-03 - High-Performance, Embeddable Storage Engine for Zig & SQLite.
* [lispking/kvdb](https://github.com/lispking/kvdb) ⭐ 19 | 🐛 1 | 🌐 Zig | 📅 2026-04-06 - A lightweight, high-performance embedded key-value database written in Zig.
* [vrischmann/zig-cassandra](https://github.com/vrischmann/zig-cassandra) ⭐ 16 | 🐛 1 | 🌐 Zig | 📅 2026-04-13 - Client for Cassandra 2.1+.
* [thanos/couchbase-zig-client](https://github.com/thanos/couchbase-zig-client) ⭐ 2 | 🐛 11 | 🌐 Zig | 📅 2026-01-22 - A wrapper around Couchbase's c library libcoucbase.

### Linear Algebra

* [kooparse/zalgebra](https://github.com/kooparse/zalgebra) ⭐ 327 | 🐛 1 | 🌐 Zig | 📅 2026-07-28 - Linear algebra library for games and real-time graphics.
* [ziglibs/zlm](https://github.com/ziglibs/zlm) ⭐ 281 | 🐛 7 | 🌐 Zig | 📅 2025-10-29 - Zig linear mathematics.
* [Laremere/alg](https://github.com/Laremere/alg) ⭐ 33 | 🐛 0 | 🌐 Zig | 📅 2022-01-19 - Algebra for Zig.
* [omaraaa/VecFns](https://github.com/omaraaa/VecFns) ⭐ 29 | 🐛 0 | 🌐 Zig | 📅 2025-08-28 - Automatic Vector Math Functions In Zig.
* [pblischak/zprob](https://github.com/pblischak/zprob) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2025-09-01 - A Zig Library for Probability Distributions.
* [BanchouBoo/algae](https://github.com/BanchouBoo/algae) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2022-01-19 - Zig math library focused on game development.
* [JungerBoyo/zmath](https://github.com/JungerBoyo/zmath) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2023-04-02 - Simple linear algebra library written in Zig.
* [MASS4/MEGA4/Math-3D](https://gitlab.com/mass4org/mega4/math-3d) - Multi-precision 3D math library (f16/f32/f64) with vectors, matrices, quaternions, rays, and 2D collision primitives.

### Scientific Computation

* [attron/astroz](https://github.com/ATTron/astroz) ⭐ 274 | 🐛 6 | 🌐 Zig | 📅 2026-04-23 - Spacecraft and Astronomical Toolkit.

### Machine Learning Framework

* [zml](https://github.com/zml/zml) ⭐ 4,007 | 🐛 43 | 🌐 Zig | 📅 2026-08-28 - A high performance machine learning stack for Zig.
* [Zigrad](https://github.com/Marco-Christiani/zigrad) ⭐ 196 | 🐛 14 | 🌐 Zig | 📅 2026-08-16 - A deep learning framework built on an autograd engine with high level abstractions and low level control. Trains neural networks 2.5x faster than PyTorch on Apple Silicon and 1.5x faster on CPU.
* [SilasMarvin/dnns-from-scratch-in-zig](https://github.com/SilasMarvin/dnns-from-scratch-in-zig) ⭐ 80 | 🐛 1 | 🌐 Zig | 📅 2024-08-25 - A very simple implementation of deep neural networks written in the Zig programming language.
* [andrewCodeDev/ZEIN](https://github.com/andrewCodeDev/ZEIN) ⭐ 60 | 🐛 0 | 🌐 Zig | 📅 2024-10-29 - Zig-based implementation of tensors.
* [recursiveGecko/onnxruntime.zig](https://github.com/recursiveGecko/onnxruntime.zig) ⭐ 36 | 🐛 0 | 🌐 Zig | 📅 2026-03-30 - Experimental Zig wrapper for ONNX Runtime with examples (Silero VAD, NSNet2).
* [candrewlee14/zgml](https://github.com/candrewlee14/zgml) ⭐ 12 | 🐛 3 | 🌐 Zig | 📅 2026-06-28 - Tensor library for machine learning, inspired by ggml.
* [maihd/zten](https://github.com/maihd/zten) ⭐ 6 | 🐛 0 | 🌐 Zig | 📅 2025-01-16 - Tensor library for Zig, based on ggml.
* [ggml-zig](https://github.com/codingonion/ggml-zig) - A replacement for [ggml: Tensor library for machine learning](https://github.com/ggerganov/ggml) ⭐ 15,251 | 🐛 352 | 🌐 C++ | 📅 2026-08-25 written in Zig.

### Large Language Model

* [nullclaw/nullclaw](https://github.com/nullclaw/nullclaw) ⭐ 8,051 | 🐛 93 | 🌐 Zig | 📅 2026-07-19 - Fastest, smallest, and fully autonomous AI assistant infrastructure written in Zig.
* [ddalcu/mlx-serve](https://github.com/ddalcu/mlx-serve) ⭐ 861 | 🐛 38 | 🌐 Zig | 📅 2026-08-28 - Native LLM inference server for Apple Silicon (MLX + GGUF) with OpenAI- and Anthropic-compatible APIs; ships MLX Core, a macOS menu-bar app. MIT.
* [cgbur/LLaMa2.zig](https://github.com/cgbur/llama2.zig) ⭐ 219 | 🐛 2 | 🌐 Zig | 📅 2026-08-02 - Inference LLaMA 2 in one file of pure Zig.
* [renerocksai/gpt4all.zig](https://github.com/renerocksai/gpt4all.zig) ⭐ 95 | 🐛 0 | 🌐 C | 📅 2023-08-11 - Zig build for a terminal-based chat client for an assistant-style large language model with \~800k GPT-3.5-Turbo Generations based on LLaMA.
* [CogitatorTech/zigformer](https://github.com/CogitatorTech/zigformer) ⭐ 52 | 🐛 0 | 🌐 Zig | 📅 2025-11-27 - ZigFormer is a transformer-based LLM implemented in pure Zig.
* [clebert/LLaMa2.zig](https://github.com/clebert/llama2.zig) ⚠️ Archived - Inference LLaMA 2 in pure Zig.
* [EugenHotaj/zig\_gpt2](https://github.com/EugenHotaj/zig_gpt2) ⭐ 40 | 🐛 0 | 🌐 Zig | 📅 2023-07-24 - Neural Network Inference Engine in Zig. GPT2 inference engine written in Zig. The inference engine can run [NanoGPT](https://github.com/karpathy/nanoGPT) ⭐ 62,549 | 🐛 351 | 🌐 Python | 📅 2025-11-12.
* [ollama-zig](https://github.com/dravenk/ollama-zig) ⭐ 39 | 🐛 0 | 🌐 Zig | 📅 2025-06-29 - Ollama Zig library.
* [cognisoc/zigllm](https://github.com/cognisoc/zigllm) ⭐ 10 | 🐛 1 | 🌐 Zig | 📅 2026-07-02 - Educational: build an LLM in Zig from scratch — tensors to text generation.
* [cztomsik/clown-code](https://codeberg.org/cztomsik/clown-code) - AI Coding assistant.
* [SMC17/faiss-zig](https://github.com/SMC17/faiss-zig) - Pure-Zig vector similarity search; Flat + HNSW + IVFFlat + IVFPQ. AGPL-3.0.
* [SMC17/safetensors-zig](https://github.com/SMC17/safetensors-zig) - Pure-Zig Hugging Face safetensors reader; \~5x faster than the Rust upstream on Llama-shape parse fixtures. AGPL-3.0.
* [SMC17/tokenizers-zig](https://github.com/SMC17/tokenizers-zig) - Pure-Zig Hugging Face tokenizers covering BPE / WordPiece / Unigram with full HF Encoding parity, sub-token offsets, and a 600-iter property fuzz. AGPL-3.0.
* [SMC17/vllm-zig](https://github.com/SMC17/vllm-zig) - LLM serving substrate. Real TinyLlama forward pass through Zig kernels: RoPE + GQA + KV cache + multi-thread SIMD matmul + streaming. AGPL-3.0.

### Machine Learning

* [zerotech-studio/zack](https://github.com/zerotech-studio/zack) ⭐ 151 | 🐛 0 | 🌐 Zig | 📅 2025-11-01 - Backtesting engine for trading strategies, written in Zig.
* [Thomvanoorschot/zigma](https://github.com/Thomvanoorschot/zigma) ⭐ 101 | 🐛 1 | 🌐 Zig | 📅 2025-08-03 - Algorithmic trading framework leveraging Actor based concurrency and a WebAssembly client.

### Encryption

* [gernest/base32](https://github.com/gernest/base32) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2025-12-24 - Base32 encoding/decoding for Ziglang.
* [deatil/zig-md2](https://github.com/deatil/zig-md2) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2026-06-06 - A MD2 hash function library for Zig.
* [deatil/zig-md4](https://github.com/deatil/zig-md4) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2026-06-06 - A MD4 hash function library for Zig.
* [deatil/zpem](https://github.com/deatil/zpem) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2026-07-18 - A pem parse and encode library for Zig.
* [deatil/zig-sm3](https://github.com/deatil/zig-sm3) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2026-06-06 - A SM3 hash function library for Zig.

### Sensor and Communication Interface

* [MasterQ32/zig-network](https://github.com/MasterQ32/zig-network) ⭐ 640 | 🐛 17 | 🌐 Zig | 📅 2025-12-23 - A smallest-common-subset of socket functions for crossplatform networking, TCP & UDP.
* [ZigEmbeddedGroup/serial](https://github.com/ZigEmbeddedGroup/serial) ⭐ 97 | 🐛 15 | 🌐 Zig | 📅 2026-05-30 - Serial port configuration library for Zig.
* [ringtailsoftware/commy](https://github.com/ringtailsoftware/commy) ⭐ 53 | 🐛 0 | 🌐 Zig | 📅 2026-03-11 - Serial terminal monitor for Linux, Mac and Windows.
* [kdchambers/reel](https://github.com/kdchambers/reel) ⭐ 38 | 🐛 15 | 🌐 Zig | 📅 2024-03-21 - Screen capture software for Linux / Wayland.
* [tetsu-koba/v4l2capture](https://github.com/tetsu-koba/v4l2capture) ⭐ 7 | 🐛 3 | 🌐 Zig | 📅 2025-03-06 - v4l2 video capturer written in Zig.

## Multimedia & Graphics

### GPU Computing

* [Snektron/vulkan-zig](https://github.com/Snektron/vulkan-zig) ⭐ 903 | 🐛 25 | 🌐 Zig | 📅 2026-08-23 - Vulkan binding generator for Zig.
* [hexops/mach-gpu](https://github.com/hexops/mach-gpu) ⭐ 205 | 🐛 0 | 🌐 Zig | 📅 2024-07-08 - Provides a truly cross-platform graphics API for Zig (desktop, mobile, and web) with unified low-level graphics & compute backed by Vulkan, Metal, D3D12, and OpenGL (as a best-effort fallback).
* [hexops/mach-gpu-dawn](https://github.com/hexops/mach-gpu-dawn) ⭐ 149 | 🐛 0 | 🌐 Zig | 📅 2024-07-08 - Google's Dawn WebGPU implementation, cross-compiled with Zig into a single static library.
* [akhildevelops/cudaz](https://github.com/akhildevelops/cudaz) ⭐ 142 | 🐛 1 | 🌐 Zig | 📅 2026-05-04 - Cuda wrapper for interacting with GPUs in Zig.
* [gwenzek/cudaz](https://github.com/gwenzek/cudaz) ⭐ 86 | 🐛 0 | 🌐 C | 📅 2025-11-26 - Toy Cuda wrapper for Zig.
* [Avokadoen/zig\_vulkan](https://github.com/Avokadoen/zig_vulkan) ⭐ 60 | 🐛 93 | 🌐 Zig | 📅 2025-08-15 - Voxel ray tracing using Vulkan compute.
* [ckrowland/simulations](https://github.com/ckrowland/simulations) ⭐ 45 | 🐛 0 | 🌐 Zig | 📅 2025-12-14 - GPU accelerated visual simulations.
* [lennyerik/cutransform](https://github.com/lennyerik/cutransform) ⭐ 31 | 🐛 0 | 🌐 Rust | 📅 2023-09-06 - CUDA kernels in any language supported by LLVM.
* [e253/zig-ocl](https://github.com/e253/zig-ocl) ⭐ 1 | 🐛 0 | 🌐 Zig | 📅 2024-06-15 - Static Zig Build of the OpenCL ICD Loader from Khronos Group.
* [MASS4/MEGA4/GPU](https://gitlab.com/mass4org/mega4/gpu) - Minimal window + GPU device platform layer for Zig built on `SDL3`'s GPU API (`Vulkan`/`Metal`/`D3D12`).

### Graphics Library

* [anomalyco/opentui](https://github.com/anomalyco/opentui) ⭐ 13,168 | 🐛 133 | 🌐 TypeScript | 📅 2026-08-28 - A library for building terminal user interfaces.
* [rockorager/libvaxis](https://github.com/rockorager/libvaxis) ⭐ 1,982 | 🐛 35 | 🌐 Zig | 📅 2026-08-20 - Modern TUI library written in Zig.
* [ziglibs/zgl](https://github.com/ziglibs/zgl) ⭐ 627 | 🐛 4 | 🌐 Zig | 📅 2026-05-26 - Zig OpenGL Wrapper.
* [MasterQ32/SDL.zig](https://github.com/MasterQ32/SDL.zig) ⭐ 446 | 🐛 19 | 🌐 C | 📅 2025-11-25 - A shallow wrapper around SDL that provides object API and error handling.
* [fubark/cosmic](https://github.com/fubark/cosmic) ⭐ 361 | 🐛 17 | 🌐 Zig | 📅 2023-03-20 - A platform for computing and creating applications. [cosmic.ooo](https://www.cosmic.ooo/).
* [TinyVG/sdk](https://github.com/TinyVG/sdk) ⭐ 302 | 🐛 17 | 🌐 Zig | 📅 2025-06-11 - TinyVG software development kit. [tinyvg.tech/](https://tinyvg.tech/).
* [vancluever/z2d](https://github.com/vancluever/z2d) ⭐ 295 | 🐛 12 | 🌐 Zig | 📅 2026-07-27 - A pure Zig 2D graphics library.
* [fabioarnold/nanovg-zig](https://github.com/fabioarnold/nanovg-zig) ⭐ 246 | 🐛 1 | 🌐 C | 📅 2026-01-29 - [NanoVG](https://github.com/memononen/nanovg) ⭐ 5,701 | 🐛 321 | 🌐 C | 📅 2026-02-19 - Zig Version. A small anti-aliased hardware-accelerated vector graphics library. [fabioarnold.github.io/nanovg-zig/](https://fabioarnold.github.io/nanovg-zig/).
* [MasterQ32/zero-graphics](https://github.com/MasterQ32/zero-graphics) ⭐ 180 | 🐛 2 | 🌐 Zig | 📅 2023-02-10 - Application framework based on OpenGL ES 2.0. Runs on desktop machines, Android phones and the web.
* [andrewrk/zig-vulkan-triangle](https://github.com/andrewrk/zig-vulkan-triangle) ⭐ 158 | 🐛 0 | 🌐 Zig | 📅 2026-07-02 - Simple triangle displayed using Vulkan, glfw, and Zig.
* [craftlinks/zig\_learn\_opengl](https://github.com/craftlinks/zig_learn_opengl) ⭐ 150 | 🐛 1 | 🌐 Zig | 📅 2023-03-24 - Follow the Learn-OpenGL book using Zig.
* [cshenton/learnopengl](https://github.com/cshenton/learnopengl) ⭐ 145 | 🐛 2 | 🌐 Zig | 📅 2021-05-28 - Zig Learn OpenGL.
* [ashpil/moonshine](https://github.com/ashpil/moonshine) ⭐ 140 | 🐛 0 | 🌐 Zig | 📅 2026-07-26 - A general purpose ray traced renderer built with Zig + Vulkan.
* [MasterQ32/Zig-OpenGL](https://github.com/MasterQ32/zig-opengl) ⭐ 124 | 🐛 3 | 🌐 C# | 📅 2025-07-26 - OpenGL binding generator based on the OpenGL registry.
* [JonSnowbd/ZT](https://github.com/JonSnowbd/ZT) ⚠️ Archived - A Zig based Imgui Application framework.
* [andrewrk/SDL](https://github.com/andrewrk/SDL) ⭐ 111 | 🐛 1 | 🌐 C | 📅 2026-06-17 - SDL with the build system replaced by Zig. [libsdl.org](https://libsdl.org/).
* [Nelarius/weekend-raytracer-zig](https://github.com/Nelarius/weekend-raytracer-zig) ⭐ 100 | 🐛 1 | 🌐 Zig | 📅 2022-07-11 - A Zig implementation of the "Ray Tracing in One Weekend" book.
* [renerocksai/slides](https://github.com/renerocksai/slides) ⚠️ Archived - This project is both a case study and also marks my first steps in the programming language Zig, towards creating a simple but powerful [imgui](https://github.com/ocornut/imgui/wiki#about-the-imgui-paradigm) ⭐ 75,911 | 🐛 1,239 | 🌐 C++ | 📅 2026-08-28 based, OpenGL-rendered slideshow app in Zig.
* [Thomvanoorschot/zignite](https://github.com/Thomvanoorschot/zignite) ⭐ 42 | 🐛 1 | 🌐 Zig | 📅 2025-07-05 - Simple cross platform rendering engine able to compile to WebAssembly with WebWorkers support.
* [SpexGuy/Zig-Gltf-Display](https://github.com/SpexGuy/Zig-Gltf-Display) ⭐ 36 | 🐛 1 | 🌐 C++ | 📅 2024-03-22 - A program that displays glTF files using Vulkan, written in Zig.
* [zsdl3](https://github.com/felixuxx/zsdl3) ⭐ 33 | 🐛 4 | 🌐 Zig | 📅 2026-07-05 - SDL3 bindings for Zig.
* [tiehuis/zig-raytrace](https://github.com/tiehuis/zig-raytrace) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2024-05-27 - Simple raytracer in Zig.
* [zig-plotille](https://github.com/tammoippen/zig-plotille) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2026-08-03 - Terminal plotting library using Unicode braille characters.
* [xtxf](https://github.com/charlesrocket/xtxf) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2026-07-30 - The Matrix screensaver in Zig.
* [tiehuis/zig-sdl2](https://github.com/tiehuis/zig-sdl2) ⭐ 14 | 🐛 0 | 🌐 Zig | 📅 2019-05-09 - SDL2 bindings for Zig.
* [winksaville/zig-3d-soft-engine](https://github.com/winksaville/zig-3d-soft-engine) ⭐ 4 | 🐛 1 | 🌐 Zig | 📅 2019-03-05 - An attempt to create a 3D engine in software using Zig.
* [river](https://codeberg.org/river/river) - A dynamic tiling Wayland compositor.

### GUI

* [Capy](https://github.com/capy-ui/capy) ⭐ 2,679 | 🐛 25 | 🌐 Zig | 📅 2025-12-25 - Build one codebase and get native UI on Windows, Linux and Web. [capy-ui.org](https://capy-ui.org/).
* [david-vanderson/dvui](https://github.com/david-vanderson/dvui) ⭐ 1,642 | 🐛 98 | 🌐 Zig | 📅 2026-08-28 - Easy to Integrate Immediate Mode GUI for Zig.
* [webui-dev/zig-webui](https://github.com/webui-dev/zig-webui) ⭐ 828 | 🐛 10 | 🌐 Zig | 📅 2026-08-03 - Use any web browser or WebView as GUI, with your preferred language in the backend and HTML5 in the frontend, all in a lightweight portable lib.
* [meszmate/zigzag](https://github.com/meszmate/zigzag) ⭐ 532 | 🐛 0 | 🌐 Zig | 📅 2026-08-28 - The TUI Framework for Zig.
* [rcalixte/libqt6zig](https://github.com/rcalixte/libqt6zig) ⭐ 264 | 🐛 0 | 🌐 Zig | 📅 2026-08-27 - Qt 6 for Zig.
* [ziglibs/positron](https://github.com/ziglibs/positron) ⭐ 126 | 🐛 2 | 🌐 C++ | 📅 2024-07-20 - A web renderer frontend for Zig applications.
* [batiati/IUPforZig](https://github.com/batiati/IUPforZig) ⚠️ Archived - IUP (Portable User Interface Toolkit) bindings for the Zig language.
* [kassane/qml\_zig](https://github.com/kassane/qml_zig) ⭐ 124 | 🐛 2 | 🌐 Zig | 📅 2025-05-19 - QML bindings for the Zig programming language.
* [Aransentin/ZWL](https://github.com/Aransentin/ZWL) ⭐ 108 | 🐛 5 | 🌐 Zig | 📅 2022-06-13 - A Zig Windowing Library.
* [MoAlyousef/zfltk](https://github.com/MoAlyousef/zfltk) ⭐ 84 | 🐛 8 | 🌐 Zig | 📅 2025-09-23 - Zig bindings for the FLTK gui library.
* [kotsutsumi/zylix](https://github.com/kotsutsumi/zylix) ⭐ 70 | 🐛 7 | 🌐 Zig | 📅 2026-03-15 - Zig powered cross-platform UI framework with Virtual DOM.
* [donpdonp/zootdeck](https://github.com/donpdonp/zootdeck) ⭐ 46 | 🐛 0 | 🌐 Zig | 📅 2026-04-15 - Fediverse GTK Desktop Reader. [donpdonp.github.io/zootdeck/](https://donpdonp.github.io/zootdeck/).
* [lupyuen/pinephone-lvgl-zig](https://github.com/lupyuen/pinephone-lvgl-zig) ⭐ 27 | 🐛 1 | 🌐 Zig | 📅 2023-08-10 - LVGL for PinePhone (and WebAssembly) with Zig and Apache NuttX RTOS. [lupyuen.github.io/articles/lvgl2](https://lupyuen.github.io/articles/lvgl2).
* [star-tek-mb/zig-tray](https://github.com/star-tek-mb/zig-tray) ⭐ 24 | 🐛 4 | 🌐 Zig | 📅 2024-12-30 - Create tray applications with Zig.
* [lupyuen/zig-lvgl-nuttx](https://github.com/lupyuen/zig-lvgl-nuttx) ⭐ 17 | 🐛 0 | 🌐 Zig | 📅 2022-07-12 - Zig LVGL Touchscreen App on Apache NuttX RTOS.
* [happystraw/zig-webview](https://github.com/happystraw/zig-webview) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2026-08-25 - Zig bindings for webview/webview, a tiny cross-platform library for building desktop applications with web technologies using a native browser widget.
* [pparaxan/quark](https://codeberg.org/pparaxan/quark) - Vulkan-based GUI toolkit focused on simplicity.

### Game Development

* [Mach](https://github.com/hexops/mach) ⭐ 4,832 | 🐛 167 | 🌐 Zig | 📅 2026-05-23 - A game engine & graphics toolkit for the future. machengine.org.
* [PixelGuys/Cubyz](https://github.com/PixelGuys/Cubyz) ⭐ 3,637 | 🐛 938 | 🌐 Zig | 📅 2026-08-28 - Voxel sandbox game with a large render distance, procedurally generated content and some cool graphical effects.
* [zig-gamedev/zig-gamedev](https://github.com/zig-gamedev/zig-gamedev) ⭐ 2,862 | 🐛 37 | 🌐 Zig | 📅 2026-03-08 - Building game development ecosystem for @ziglang.
* [andrewrk/tetris](https://github.com/andrewrk/tetris) ⭐ 490 | 🐛 0 | 🌐 Zig | 📅 2026-05-29 - A simple tetris clone written in Zig programming language. [www.youtube.com/watch?v=AiintPutWrE](https://www.youtube.com/watch?v=AiintPutWrE).
* [wendigojaeger/ZigGBA](https://github.com/wendigojaeger/ZigGBA) ⭐ 387 | 🐛 7 | 🌐 Zig | 📅 2025-07-19 - Work in progress SDK for creating Game Boy Advance games using Zig programming language.
* [Jack-Ji/jok](https://github.com/Jack-Ji/jok) ⚠️ Archived - A minimal 2d/3d game framework for Zig.
* [godot-zig/godot-zig](https://github.com/godot-zig/godot-zig) ⭐ 304 | 🐛 19 | 🌐 Zig | 📅 2024-12-29 - Zig bindings for Godot 4.
* [foxnne/aftersun](https://github.com/foxnne/aftersun) ⭐ 302 | 🐛 3 | 🌐 Zig | 📅 2024-06-10 - Top-down 2D RPG.
* [andrewrk/clashos](https://github.com/andrewrk/clashos) ⭐ 246 | 🐛 0 | 🌐 Zig | 📅 2020-01-26 - Multiplayer arcade game for bare metal Raspberry Pi 3 B+.
* [zPSP-Dev/Zig-PSP](https://github.com/zPSP-Dev/Zig-PSP) ⭐ 133 | 🐛 5 | 🌐 Zig | 📅 2026-05-24 - A project to bring the Zig Programming Language to the Sony PlayStation Portable.
* [prime31/zig-gamekit](https://github.com/prime31/zig-gamekit) ⭐ 132 | 🐛 3 | 🌐 Zig | 📅 2023-04-28 - Companion repo for Zig-renderkit for making 2D games.
* [DanB91/Zig-Playdate-Template](https://github.com/DanB91/Zig-Playdate-Template) ⭐ 118 | 🐛 2 | 🌐 Zig | 📅 2026-08-10 - Starter code for a Playdate program written in Zig.
* [thejoshwolfe/legend-of-swarkland](https://github.com/thejoshwolfe/legend-of-swarkland) ⭐ 105 | 🐛 5 | 🌐 Zig | 📅 2025-08-20 - Turn-based action fantasy puzzle game inspired by NetHack and Crypt of the Necrodancer. [wolfesoftware.com/legend-of-swarkland/](https://wolfesoftware.com/legend-of-swarkland/).
* [MasterQ32/Ziguana-Game-System](https://github.com/MasterQ32/Ziguana-Game-System) ⭐ 54 | 🐛 1 | 🌐 Zig | 📅 2021-02-15 - A retro-style gaming console running on bare x86 metal written in Zig.
* [TM35-Metronome/metronome](https://github.com/TM35-Metronome/metronome) ⭐ 54 | 🐛 23 | 🌐 Zig | 📅 2025-03-07 - A set of tools for modifying and randomizing Pokémon games. [tm35-metronome.github.io/](https://tm35-metronome.github.io/).
* [Avokadoen/ecez](https://github.com/Avokadoen/ecez) ⚠️ Archived - An archetype based ECS library written in pure Zig.
* [ringtailsoftware/zigtris](https://github.com/ringtailsoftware/zigtris) ⭐ 33 | 🐛 0 | 🌐 Zig | 📅 2025-12-17 - Zigtris, a terminal tetris.
* [emekoi/ziglet](https://github.com/emekoi/ziglet) ⭐ 29 | 🐛 0 | 🌐 Zig | 📅 2020-05-06 - A small Zig game library.
* [captkirk88/zevy-ecs](https://github.com/captkirk88/zevy-ecs) ⚠️ Archived - ECS similar to rust Bevy supporting very similar systems params support + more.
* [Akuli/curses-minesweeper](https://github.com/Akuli/curses-minesweeper) ⭐ 21 | 🐛 0 | 🌐 Zig | 📅 2025-02-20 - Minesweeper game written in curses with Zig.
* [zkburke/quanta](https://github.com/zkburke/quanta) ⭐ 19 | 🐛 0 | 🌐 Zig | 📅 2025-11-18 - A game engine/framework written in and for Zig.
* [fabioarnold/snake-zig](https://github.com/fabioarnold/snake-zig) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2023-10-22 - A simple snake game written in the Zig programming language using OpenGL 2.
* [ryupold/zecsi](https://github.com/ryupold/zecsi) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2023-12-19 - Small game framework made with Zig utilizing the awesome raylib.
* [ringtailsoftware/zoridor](https://github.com/ringtailsoftware/zoridor) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2025-01-17 - Zoridor, a Quoridor game for terminal and web with a machine opponent.
* [4imothy/termy48](https://github.com/4imothy/termy48) ⭐ 13 | 🐛 0 | 🌐 Zig | 📅 2023-12-13 - A 2048 game to run in terminal.
* [deckarep/dungeon-rush](https://github.com/deckarep/dungeon-rush) ⭐ 13 | 🐛 0 | 🌐 Zig | 📅 2024-11-12 - An SDL snake style game ported to Zig. Originally written in C.
* [TM35-Metronome/tm35-nds](https://github.com/TM35-Metronome/tm35-nds) ⭐ 11 | 🐛 0 | 🌐 Zig | 📅 2019-08-09 - A library for working with Nintendo DS roms.
* [six519/YieArKUNGFUZig](https://github.com/six519/YieArKUNGFUZig) ⭐ 10 | 🐛 0 | 🌐 Zig | 📅 2025-03-20 - A Yie Ar Kung-Fu clone created in Zig with raylib.
* [Srekel/zag](https://github.com/Srekel/zag) ⭐ 9 | 🐛 0 | 🌐 Zig | 📅 2019-12-21 - Game dev project written in Zig and C.
* [kristianhasselknippe/zig-game-engine](https://github.com/kristianhasselknippe/zig-game-engine) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2021-03-06 - Learning Zig through game engine.
* [deckarep/CosmicInvaders](https://github.com/deckarep/CosmicInvaders) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2026-05-07 - A pixel-art Space Invaders + Tower Defense game written in Zig with raylib.
* [nitanmarcel/ScriptHookVZig](https://github.com/nitanmarcel/ScriptHookVZig) ⭐ 8 | 🐛 0 | 🌐 Zig | 📅 2024-06-15 - Library to write GTA V mods in Zig.
* [tiehuis/zstack](https://github.com/tiehuis/zstack) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2019-06-17 - Line-race tetris mode in Zig.
* [captkirk88/zevy-raylib](https://github.com/captkirk88/zevy-raylib) ⚠️ Archived - Framework for building games in Zig using raylib-zig and zevy-ecs.
* [Avokadoen/ecez\_vulkan](https://github.com/Avokadoen/ecez_vulkan) ⭐ 4 | 🐛 52 | 🌐 Zig | 📅 2024-08-20 - A scene editor built on [ecez](https://github.com/Avokadoen/ecez) ⚠️ Archived and Vulkan.
* [star-tek-mb/Paradise](https://github.com/star-tek-mb/Paradise) ⭐ 3 | 🐛 0 | 🌐 Zig | 📅 2023-03-28 - Paradise is a WebAssembly first game engine written in Zig.
* [ringtailsoftware/zero-jetpack](https://github.com/ringtailsoftware/zero-jetpack) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-01-09 - Zero-Jetpack a web game about Ziguanas carrying eggs.
* [ajTronic/zetr](https://github.com/ajTronic/zetr) ⭐ 2 | 🐛 0 | 🌐 Zig | 📅 2025-08-20 - An aesthetic tetris clone for the terminal written in Zig.
* [Stenodyon/blink](https://github.com/Stenodyon/blink) - A game about building logic with lasers.
* [darltrash/zcutenet](https://codeberg.org/darltrash/zcutenet) - A cute\_net.h binding and wrapper for Zig, for realtime networking.
* [GasInfinity/zitrus](https://codeberg.org/GasInfinity/zitrus) - A 3DS SDK with all the bells and whistles in pure Zig.
* [MASS4/MEGA4/Turian](https://gitlab.com/mass4org/mega4/turian) - A component-based 3D game engine + editor built entirely in Zig with a Unity-style workflow.

### Audio Processing

* [orhun/linuxwave](https://github.com/orhun/linuxwave) ⭐ 661 | 🐛 17 | 🌐 Zig | 📅 2026-07-31 - Generate music from the entropy of Linux 🐧🎵. [orhun.dev/linuxwave/](https://orhun.dev/linuxwave/).
* [Hejsil/zig-midi](https://github.com/Hejsil/zig-midi) ⚠️ Archived - Zig-midi.
* [hexops/mach-sysaudio](https://github.com/hexops/mach-sysaudio) ⭐ 32 | 🐛 0 | 🌐 Zig | 📅 2024-03-06 - Cross-platform low-level audio IO in Zig.

### Image and Video Processing

* [dmtrKovalenko/odiff](https://github.com/dmtrKovalenko/odiff) ⭐ 3,177 | 🐛 15 | 🌐 Zig | 📅 2026-08-24 - ODiff - A very fast SIMD-first image comparison library (with Node.js API).
* [zigimg/zigimg](https://github.com/zigimg/zigimg) ⭐ 838 | 🐛 49 | 🌐 Zig | 📅 2026-08-18 - Zig library for reading and writing different image formats.
* [freref/fancy-cat](https://github.com/freref/fancy-cat) ⭐ 558 | 🐛 20 | 🌐 Zig | 📅 2026-08-03 - PDF reader inside the terminal.
* [bfactory-ai/zignal](https://github.com/bfactory-ai/zignal) ⭐ 461 | 🐛 0 | 🌐 Zig | 📅 2026-08-27 - Image processing library in Zig, heavily inspired by dlib.
* [ryoppippi/zigcv](https://github.com/ryoppippi/zigcv) ⭐ 162 | 🐛 25 | 🌐 Zig | 📅 2026-07-18 - Opencv bindings for Zig.
* [kassane/libvlc-zig](https://github.com/kassane/libvlc-zig) ⭐ 21 | 🐛 7 | 🌐 Zig | 📅 2023-09-03 - Zig bindings for libVLC media framework.
* [marler8997/image-viewer](https://github.com/marler8997/image-viewer) ⭐ 10 | 🐛 2 | 🌐 Zig | 📅 2025-05-04 - An image-viewer experiment written in Zig.
* [brian-sinquin/mimg](https://github.com/brian-sinquin/mimg) ⭐ 0 | 🐛 1 | 🌐 Zig | 📅 2026-01-03 - A chained-modifiers Image processing Command-line tool.
* [foxnne/pixi](https://github.com/foxnne/pixi) ⭐ 0 | 🐛 0 | 📅 2026-06-01 - Pixel art and animation editor written in Zig.

## Interoperability

### FFI Bindings

Zig wrappers and bindings for existing C/C++ libraries, providing idiomatic Zig APIs.

* [fulcrum-so/ziggy-pydust](https://github.com/fulcrum-so/ziggy-pydust) ⭐ 786 | 🐛 44 | 🌐 Zig | 📅 2026-08-27 - A toolkit for building Python extensions in Zig. [pydust.fulcrum.so/](https://pydust.fulcrum.so/).
* [floooh/sokol-zig](https://github.com/floooh/sokol-zig) ⭐ 722 | 🐛 14 | 🌐 C | 📅 2026-08-28 - Zig bindings for the sokol headers.
* [natecraddock/ziglua](https://github.com/natecraddock/ziglua) ⭐ 521 | 🐛 10 | 🌐 Zig | 📅 2026-08-25 - Zig bindings for the Lua C API.
* [mitchellh/zig-objc](https://github.com/mitchellh/zig-objc) ⭐ 345 | 🐛 3 | 🌐 Zig | 📅 2026-04-17 - Objective-C runtime bindings for Zig (Zig calling ObjC).
* [jiacai2050/zig-curl](https://github.com/jiacai2050/zig-curl) ⭐ 160 | 🐛 3 | 🌐 Zig | 📅 2026-04-24 - Zig bindings for libcurl.
* [lassade/c2z](https://github.com/lassade/c2z) ⭐ 126 | 🐛 9 | 🌐 C++ | 📅 2025-04-06 - C++ to Zig bindings and transpiler.
* [sackosoft/zig-luajit](https://github.com/sackosoft/zig-luajit) ⭐ 84 | 🐛 2 | 🌐 Zig | 📅 2026-05-08 - Zig bindings for the LuaJIT C API.
* [katafrakt/zig-ruby](https://github.com/katafrakt/zig-ruby) ⭐ 78 | 🐛 0 | 🌐 Zig | 📅 2025-11-12 - This repo contains an experiment of building a Ruby extension with Zig programming language. It implements a slightly altered version of 100 doors from Rosetta Code.
* [arshidkv12/zig-php](https://github.com/arshidkv12/zig-php) ⭐ 25 | 🐛 0 | 🌐 Zig | 📅 2025-09-14 - Write PHP extension in Zig.
* [ExpidusOS/zig-flutter](https://github.com/ExpidusOS/zig-flutter) ⚠️ Archived - Flutter with Zig.
* [jiacai2050/zig-rocksdb](https://github.com/jiacai2050/zig-rocksdb) ⭐ 6 | 🐛 1 | 🌐 Zig | 📅 2025-09-21 - Zig bindings for RocksDB.
* [OnlyF0uR/pqc-zig](https://github.com/OnlyF0uR/pqc-zig) ⭐ 5 | 🐛 1 | 🌐 Zig | 📅 2025-05-01 - Zig bindings and abstractions for [PQClean](https://github.com/PQClean/PQClean/) ⚠️ Archived, post-quantum cryptography.
* [happystraw/phpz](https://github.com/happystraw/phpz) ⭐ 5 | 🐛 1 | 🌐 Zig | 📅 2026-08-05 - Build PHP extensions with Zig.
* [jiacai2050/zig-jemalloc](https://github.com/jiacai2050/zig-jemalloc) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2024-10-27 - Zig allocator baked by jemalloc.

### Build with Zig

Existing C/C++ projects that have replaced their original build systems with Zig's build system, enabling seamless cross-compilation and dependency management via `zig build`.

* [raylib](https://github.com/raysan5/raylib/) ⭐ 34,487 | 🐛 15 | 🌐 C | 📅 2026-08-28 - A simple and easy-to-use library to enjoy videogames programming.
* [libxlsxwriter](https://github.com/jmcnamara/libxlsxwriter) ⭐ 1,753 | 🐛 20 | 🌐 C | 📅 2026-07-07 - A C library for creating Excel XLSX files, build system replaced by Zig.
* [FFmpeg](https://github.com/andrewrk/ffmpeg) ⭐ 321 | 🐛 7 | 🌐 C | 📅 2026-08-28 - Library FFmpeg with the build system replaced by Zig.
* [openssl](https://github.com/kassane/openssl-zig) ⭐ 30 | 🐛 0 | 🌐 C | 📅 2026-04-20 - TLS/SSL and crypto library (uses Zig Build).
* [pulseaudio](https://github.com/andrewrk/pulseaudio) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2026-07-03 - Library pulseaudio with the build system replaced by Zig.
* [libz](https://github.com/andrewrk/libz) ⭐ 15 | 🐛 3 | 🌐 C | 📅 2024-04-17 - Library zlib with the build system replaced by Zig.
* [libchromaprint](https://github.com/andrewrk/libchromaprint) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2024-02-25 - Library chromaprint with the build system replaced by Zig.
* [boring\_tls](https://github.com/Thomvanoorschot/boring_tls) ⭐ 12 | 🐛 1 | 🌐 Zig | 📅 2026-01-15 - Google's BoringTLS client and server. Adds TLS to any (including non standard library) TCP/HTTP traffic.
* [wolfssl](https://github.com/kassane/wolfssl) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2026-02-25 - Library WolfSSL Using Zig Build.
* [asio](https://github.com/kassane/asio) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2026-03-25 - The Asio C++ Library with Zig build-system.
* [libmp3lame](https://github.com/andrewrk/libmp3lame) ⭐ 7 | 🐛 2 | 🌐 C | 📅 2026-08-02 - Library libmp3lame with the build system replaced by Zig.
* [Standalone](https://github.com/kassane/Standalone-Server) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2025-03-10 - An Asio standalone C++ HTTP/S Server (uses Zig build-system).
* [libvorbis](https://github.com/andrewrk/libvorbis) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-03-31 - Library libvorbis with the build system replaced by Zig.
* [libogg](https://github.com/andrewrk/libogg) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-03-31 - Library libogg with the build system replaced by Zig.
* [json](https://github.com/kassane/json) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2024-08-04 - Library JSON for Modern C++ (uses Zig build-system).
* [fiber](https://github.com/kassane/fiber) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2024-09-04 - Userland threads using Zig build.
* [hana](https://github.com/kassane/hana) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2024-08-04 - Your standard library for metaprogramming.
* [fmt](https://github.com/kassane/fmt) ⭐ 1 | 🐛 1 | 🌐 C++ | 📅 2024-09-28 - A modern formatting library (uses Zig build-system).
* [boost async](https://github.com/kassane/cobalt) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-06-26 - Coroutines for C++20 & asio (uses Zig build for testing).
* [outcome](https://github.com/kassane/outcome) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-08-04 - Provides very lightweight `outcome<T>` and `result<T>` (non-Boost edition) (uses Zig build-system).
* [cppfront](https://github.com/kassane/cppfront-zigbuild) ⭐ 1 | 🐛 1 | 🌐 Zig | 📅 2025-11-21 - Build Cppfront with Zig build.
* [libebur128](https://github.com/andrewrk/libebur128) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2023-12-05 - Library libebur128 with the build system replaced by Zig.
* [boost unordered](https://github.com/kassane/unordered) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-06-27 - Boost.org unordered module (uses Zig build).
* [context](https://github.com/kassane/context) ⭐ 0 | 🐛 0 | 🌐 Assembly | 📅 2024-06-26 - Library `boost.context` using Zig build.
* [observable](https://github.com/kassane/observable_unique_ptr) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-07-13 - Unique-ownership smart pointers with observable lifetime.
* [Catch2](https://github.com/kassane/Catch2) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-10-05 - A modern, C++-native, test framework for unit-tests, TDD and BDD - using C++14, C++17 and later (C++11 support is in v2.x branch, and C++03 on the Catch1.x branch) - uses Zig build-system.
* [intrusive](https://github.com/kassane/intrusive) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-06-19 - Boost.org intrusive module.
* [range](https://github.com/kassane/range-v3) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-08-04 - The Range library for C++14/17/20, basis for C++20's std::ranges.
* [benchmark](https://github.com/kassane/benchmark) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-02-17 - A microbenchmark support library. First posted on [Ziggit](https://ziggit.dev/t/is-there-a-list-of-projects-that-has-been-zigged/1785).
* [libui-ng](https://github.com/happystraw/libui-ng) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-02-11 - Library libui-ng (a portable GUI library for C) with the build system replaced by Zig.
* [nasm](https://github.com/andrewrk/nasm) - Library nasm with the build system replaced by Zig.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
