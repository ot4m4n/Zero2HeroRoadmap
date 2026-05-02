# Digital Logic & Binary Systems

> **Goal:** Understand binary, boolean logic, and how gates build adders, registers, memory.
> **Prerequisites:** 01.
> **Estimated time:** 6–10 h

## 📚 Free resources

- [Ben Eater — Building an 8-bit computer (YouTube)](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU)
- [Crash Course CS — Boolean Logic episode](https://www.youtube.com/watch?v=gI-qXk7XojA)
- [nand2tetris (free course)](https://www.nand2tetris.org/)

## ✅ Checkpoint — you're ready to move on when:

- You can convert between binary/hex/decimal in your head and draw a 1-bit full adder.

---

## 📂 Syllabus

## 💻 Binary Number Systems
- What is binary and why computers use it
- Base conversions:
  - Decimal → Binary
  - Binary → Decimal
  - Binary → Hexadecimal
- Signed vs unsigned numbers
- Two's complement
- Endianness: little-endian vs big-endian
- Floating-point representation (IEEE 754)
- Binary arithmetic: addition, subtraction, multiplication
- Bitwise operations:
  - AND, OR, NOT, XOR
  - Bit shifting (<<, >>)
- Bit masking and flag fields
- Representing negative numbers and overflows

## ⚖️ Boolean Algebra & Logic Gates
- Boolean variables and logic expressions
- Truth tables and logic evaluation
- Fundamental logic gates:
  - AND, OR, NOT
- Derived gates:
  - NAND, NOR, XOR, XNOR
- De Morgan's Laws
- Combinational logic
- Minimizing logic expressions (Karnaugh Maps)
- Logic circuit simulation tools
- Logic propagation delays
- Using Boolean logic in control flow (if/else, conditions)

## 🛠️ Digital Components
- Flip-Flops:
  - SR, D, JK, T Flip-Flops
- Latches vs Flip-Flops
- Clocking mechanisms and edge-triggered design
- Registers and shift registers
- Counters (synchronous, asynchronous)
- Timers and clocks
- Multiplexers, Demultiplexers
- Encoders and Decoders
- Comparators
- Tri-state buffers

## ⚖️ Combinational Circuits
- Half Adder, Full Adder
- Multiplexer / Demultiplexer
- Decoder / Encoder
- ALU Design (Arithmetic Logic Unit)
- Circuit diagrams using logic gate symbols
- Simulation with digital logic tools (e.g., Logisim)
- Circuit optimization and simplification

## 🌐 Data Representation & Encoding
- ASCII vs Unicode (UTF-8, UTF-16)
- Binary-coded decimal (BCD)
- Parity bits and error detection
- Checksum algorithms
- Hamming code (Error correction)
- Gray code and its use in hardware
- Memory encoding formats
- Digital signal encoding concepts (NRZ, Manchester)
- Compression basics (lossless vs lossy)
- Base64 and hexadecimal in data transmission

## 🌀 Sequential Logic & FSMs
- Difference between combinational and sequential logic
- State machines:
  - Moore vs Mealy models
- Designing FSMs:
  - State diagrams
  - State transition tables
- Applications in digital design
- Use in protocol parsing
- Timing diagrams and delays
- HDL-based implementation (optional advanced)
- Clock synchronization
- Metastability issues in hardware

## 🔹 Logic Implementation Tools
- Schematic vs text-based design
- Digital circuit simulators:
  - Logisim
  - CircuitVerse
  - Digital Works
- HDL introduction:
  - Verilog vs VHDL (basics only)
- FPGA basics (field-programmable gate arrays)
- Breadboard prototyping (for physical learners)

## 📊 Digital Measurement & Timing
- Measuring signal timings
- Clock cycles and frequency
- Debouncing signals
- Propagation delay
- Signal timing diagrams
- Synchronizing inputs
- Flip-Flop setup/hold time
- Logic analyzer use

## 🥯 Real-world Applications
- Use of logic in microprocessors
- Control systems
- Memory and storage controllers
- Network hardware logic paths
- Encoders/decoders in multimedia
- Sensor signal digitization
- Logic in keyboard/mouse controllers
- Use in IoT device design
- Error detection in communication protocols
