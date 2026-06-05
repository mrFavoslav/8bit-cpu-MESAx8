# MESAx8 - Minimal Extensible System Architecture x8

I'll make a more detailed README in the near future, but for now, this repository is mainly a host of files for people who want to have a look at my progress on an 8-bit CPU design.

### Files Overview

* **`instructions.txt`** — Contains my current proposal for the Instruction Set Architecture (ISA).
* **`cpu.circ`** — The main Logisim file containing all the hardware schematics. 

---

### Schematics Breakdown (`cpu.circ`)

Here is a quick overview of what you will find inside the Logisim project, as it contains both current 8-bit components and remnants of an older 4-bit design:

**Current 8-bit Architecture:**
* **`main_8bit`** — Currently mostly empty, but this is where the entire 8-bit CPU will eventually be assembled.
* **`ALU_8bit`** — The current 8-bit ALU design.
* **`add_sub_8bit`** — 8-bit Adder/Subtractor, used in the 8-bit ALU.
* **`latch_8bit`** — 8-bit latch, also used in the 8-bit ALU.

**Basic Components & Workspace:**
* **`adder_1bit`** — The fundamental building block for the math circuits.
* **`test`** — Workspace for random testing, prototyping, and debugging.

**Legacy 4-bit Architecture:**
*(Note: This project originally started as a 4-bit CPU. I even have an emulator for it in another repository on my GitHub profile.)*
* **`main_4bit`** — Remnant of the original 4-bit CPU top-level design.
* **`ALU_4bit`** — The complete legacy 4-bit ALU.
* **`adder_4bit`** — Used in the 4-bit ALU.
* **`comp_4bit`** — Comparator, used in the 4-bit ALU.
* **`add_sub_4bit`** — Adder/Subtractor, used in the 4-bit ALU.
