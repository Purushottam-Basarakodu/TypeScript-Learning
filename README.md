
# TypeScript: Basics & Quick Start

---

## Overview
**Playwright** is an open-source Node.js library by Microsoft for **browser automation** and **E2E testing** across **Chromium**, **Firefox**, and **WebKit**. Pairing it with **TypeScript** adds static typing and great IDE support, making tests safer and more maintainable.

---

## Why TypeScript for Playwright?
- **Type Safety**: Catch mistakes at compile time.
- **IntelliSense**: Autocomplete for `page`, `locator`, `expect`, fixtures, etc.
- **Maintainability**: Typed helpers, page objects, and fixtures scale well.
- **Refactoring confidence**: Clean API contracts via interfaces and types.

---

## Getting Started

### 1) Prerequisites
- Node.js
- npm
- TypeScript compiler (Command to install : npm install -g TypeScript)
- TypeScript Executor (Command to install : npm install -g tsx)
- VSCode Editor
---

## 🧪 First Program in TypeScript

### How to print "Hello World !!!" ?
- create a file with extension as .ts and save the file (Example file name : MyFirstProgram.ts)
- to print the given string, first we need to compile the TypeScript code into JavaScript code
- Use the following command to do that (Command : tsc **filePath**)
- It will create a file with .js extension, which can be run using node commands (for example : node MyFirstProgram.js)
### do you find difficulty to execute the file with above process?
- here is the simple process to directly execute without compiling the code into plain JavaScript
- use command : tsx **filePath**
- the above command will directly execute the .ts extension files directly
---
