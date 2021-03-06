---
title: The Obfvious Compiler
author: Nimrod Partush
date: Feb 20, 2021
categories: [Projects]
tags: [compilers, llvm, clang, obfuscation, c, c++, security, reverse-engineering, windows]
math: false
---

[_Obfvious_](https://github.com/nimrodpar/Obfvious) is a LLVM & Clang (version 12) based compiler focused on **Windows** binaries obfuscation. It's currently implemented as an integral part of Clang and is invoked automatically as part of the compilation.

Obfvious was incepted during my [research on executable similarity](https://nimrodpar.github.io/posts/firmup-paper/). I was contemplating using the technique for malware similarity, and wanted to examine how reliant are static AV engines (exposed through VirusTotal) on meta data such as hard-coded strings and debug info (Spoiler: they are very reliant). Although seeming a trivial task, as hard as I looked I could not find a compile time tool that hides strings without needing to manually alter the code. So I created one. 

I've open sourced Obfvious as a tool for other researchers interested in binary and malware analysis. I'm planning on adding more obfuscation techniques as time allows (and per request). 

Cheers 🍻
