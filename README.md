🔬 Mixed-Logic Decoder Design Using Cadence Virtuoso

A VLSI design project focused on digital logic circuits and decoder architectures.

---

📌 Project Overview

This project focuses on the design and simulation of digital logic circuits using Cadence Virtuoso. It explores mixed-logic circuit design through basic logic gates and different decoder configurations.

The project includes inverter, NAND, NOR, 2-to-4 decoder, 3-to-8 decoder, and 5-to-32 decoder designs, along with their corresponding test folders.

🎯 Objectives

- Design and simulate digital circuits using Cadence Virtuoso.
- Implement different decoder architectures.
- Verify the functionality of completed designs.
- Understand combinational logic and decoder operation.
- Explore mixed-logic techniques for VLSI applications.

🛠️ Tools and Technologies

Category| Details
EDA Tool| Cadence Virtuoso
Domain| VLSI Design and Digital Electronics
Design Method| Schematic-based circuit design
Verification| Simulation and output waveform analysis

📂 Repository Structure

mixedlogic_decoder/
├── .cadence/
├── inv/
├── inv_test/
├── nand2/
├── nand2_test/
├── nor/
├── nor_test/
├── decoder2to4/
├── decoder2to4_test/
├── decoder3to8/
├── decoder3to8_test/
├── decoder5to32/
├── .oalib
├── cdsinfo.tag
├── data.dm
└── README.md

Note: Additional Cadence-generated files may be present in the repository.

⚙️ Implemented Designs

1. Inverter

Produces the complement of its input.

Boolean expression: (Y = \overline{A})

Status: ✅ Completed and verified

2. 2-Input NAND Gate

Produces the complement of the AND operation.

Boolean expression: (Y = \overline{A \cdot B})

Status: ✅ Completed and verified

3. 2-Input NOR Gate

Produces the complement of the OR operation.

Boolean expression: (Y = \overline{A + B})

Status: ✅ Completed and verified

4. 2-to-4 Decoder

Converts a 2-bit binary input into four output lines, with one output active for each valid input combination in an active-high implementation.

Status: ✅ Completed and verified

5. 3-to-8 Decoder

Converts a 3-bit binary input into eight output lines, with one output active for each valid input combination in an active-high implementation.

Status: ✅ Completed and verified

6. 5-to-32 Decoder

Designed to decode a 5-bit binary input into 32 output lines.

Status: 🚧 In progress — design and verification pending

🧪 Simulation and Verification

The inverter, NAND gate, NOR gate, 2-to-4 decoder, and 3-to-8 decoder have been simulated and functionally verified in the lab using Cadence Virtuoso.

Output screenshots and simulation waveforms for all designs will be uploaded together after the 5-to-32 decoder is completed and verified.

📊 Project Progress

Design| Implementation| Verification
Inverter| Completed| Verified
2-Input NAND Gate| Completed| Verified
2-Input NOR Gate| Completed| Verified
2-to-4 Decoder| Completed| Verified
3-to-8 Decoder| Completed| Verified
5-to-32 Decoder| In progress| Pending

📚 Key Learning Outcomes

- Hands-on experience with Cadence Virtuoso.
- Understanding digital logic and combinational circuits.
- Schematic design and testbench organization.
- Simulation-based functional verification.
- Practical exposure to VLSI design workflows.

🚧 Future Work

- Complete and verify the 5-to-32 decoder.
- Upload output screenshots and simulation waveforms.
- Document simulation results and measured performance parameters.
- Explore power, delay, and area optimization where applicable.

---

👩‍💻 Author

Akshata Ontigodimath

Electronics and Communication Engineering

Areas of Interest: VLSI Design, Digital Electronics, and Embedded Systems.
