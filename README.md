Mixed-Logic Decoder Design Using Cadence Virtuoso

📌 Project Overview

This project focuses on the design and simulation of digital logic circuits and decoder architectures using Cadence Virtuoso. It explores mixed-logic circuit design through the implementation of basic logic gates and different decoder configurations.

The project includes inverter, NAND, NOR, 2-to-4 decoder, 3-to-8 decoder, and 5-to-32 decoder designs, along with corresponding test folders for simulation and verification.

🎯 Objectives

- Design and simulate digital logic circuits using Cadence Virtuoso.
- Implement different decoder architectures.
- Verify the functional correctness of completed designs.
- Understand combinational logic and decoder operation.
- Explore mixed-logic design techniques for VLSI applications.

🛠️ Tools and Technologies

- EDA Tool: Cadence Virtuoso
- Domain: VLSI Design and Digital Electronics
- Design Methodology: Schematic-based circuit design
- Verification: Testbench-based simulation and output waveform analysis

📂 Repository Structure

mixedlogic_decoder/
│
├── .cadence/
│
├── inv/
├── inv_test/
│
├── nand2/
├── nand2_test/
│
├── nor/
├── nor_test/
│
├── decoder2to4/
├── decoder2to4_test/
│
├── decoder3to8/
├── decoder3to8_test/
│
├── decoder5to32/
│
├── .oalib
├── cdsinfo.tag
├── data.dm
│
└── README.md

Note: The structure above represents the main folders and files in the project. Additional Cadence-generated files may be present in the repository.

⚙️ Implemented Designs

1. Inverter

A basic logic circuit that produces the complement of its input.

Boolean expression:

Y = NOT A

Status: Completed and functionally verified.

2. 2-Input NAND Gate

A logic gate that produces the complement of the AND operation.

Boolean expression:

Y = NOT (A · B)

Status: Completed and functionally verified.

3. 2-Input NOR Gate

A logic gate that produces the complement of the OR operation.

Boolean expression:

Y = NOT (A + B)

Status: Completed and functionally verified.

4. 2-to-4 Decoder

A combinational circuit that converts a 2-bit binary input into four output lines, with one output activated for each valid input combination in an active-high implementation.

Status: Completed and functionally verified.

5. 3-to-8 Decoder

A combinational circuit that converts a 3-bit binary input into eight output lines, with one output activated for each valid input combination in an active-high implementation.

Status: Completed and functionally verified.

6. 5-to-32 Decoder

A combinational circuit designed to decode a 5-bit binary input into 32 output lines.

Status: In progress. Design completion and functional verification are pending.

🧪 Simulation and Verification

The inverter, 2-input NAND gate, 2-input NOR gate, 2-to-4 decoder, and 3-to-8 decoder have been implemented and their outputs verified in the lab using Cadence Virtuoso.

Verification involves applying appropriate input combinations, observing output responses, and checking circuit functionality against expected logical behavior.

Output screenshots and simulation waveforms for all designs will be uploaded to the repository together after the 5-to-32 decoder is completed and verified.

📊 Project Progress

Design| Implementation Status| Verification Status
Inverter| Completed| Verified
2-Input NAND Gate| Completed| Verified
2-Input NOR Gate| Completed| Verified
2-to-4 Decoder| Completed| Verified
3-to-8 Decoder| Completed| Verified
5-to-32 Decoder| In Progress| Pending

📚 Key Learning Outcomes

- Hands-on experience with Cadence Virtuoso.
- Practical understanding of digital logic and combinational circuits.
- Experience designing and organizing schematics and test cells.
- Functional verification through circuit simulation.
- Understanding the role of decoder circuits in digital systems and VLSI design.

🚧 Future Work

- Complete the 5-to-32 decoder design.
- Verify the 5-to-32 decoder through simulation.
- Upload output screenshots and simulation waveforms for all designs.
- Document simulation results and performance measurements where available.
- Explore opportunities to optimize decoder circuits for power, delay, and area.

👩‍💻 Author

Akshata Ontigodimath

Electronics and Communication Engineering

Areas of Interest: VLSI Design, Digital Electronics, Embedded Systems

---

This project demonstrates practical learning and implementation of digital logic circuits using Cadence Virtuoso, with ongoing work on larger decoder architectures.
