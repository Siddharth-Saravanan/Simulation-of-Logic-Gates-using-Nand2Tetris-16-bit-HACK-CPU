# Simulation-of-Logic-Gates-using-Nand2Tetris-16-bit-HACK-CPU

---
This project simulates logic gates and sequential chips using the **Nand2Tetris 16-bit HACK CPU architecture**. Users can interactively test the behavior of different chips through a custom-built user interface that accepts manual inputs and provides visual feedback.

## 🚀 Features

- ✅ **Interactive Simulation**  
  Manually input values and observe real-time gate/chip behavior.

- 🧩 **Sequential Logic Simulation**  
  Includes key elements like flip-flops, registers, counters, and memory components.

- 🖼️ **Menu-Driven UI**  
  Navigate through a clean interface to:
  - Select chips
  - View built-in descriptions
  - Enter input values
  - Observe outputs

- 📚 **Well-Structured Codebase**  
  Designed in the Jack language and compiled to VM code for execution using Nand2Tetris tools.

## 📁 Project Structure

```
├── ClassFiles/             # Compiled class files for Jack programs
├── builtInVMCode/          # VM modules for various gates and helpers
├── Main.jack               # Entry point and menu logic
├── CChip_UI.jack           # UI for logic gate interaction
├── SChip_UI.jack           # UI for sequential chip simulation
├── Comb_Simulate.jack      # Logic simulation backend for gates
├── Sequential_UI.jack      # Logic backend for sequential circuits
├── Description.jack        # Displays information about each chip
├── JackCompiler.bat        # Batch script to compile Jack files
├── VMEmulator.bat          # Batch script to run VM code
└── *.vm                    # Compiled VM files for each module
```

## 🧪 Key Modules

| File Name           | Purpose                                      |
|---------------------|----------------------------------------------|
| `CChip_UI.jack`     | User interface for logic gate interaction    |
| `SChip_UI.jack`     | Interface for sequential chip simulation     |
| `Description.jack`  | Displays descriptions of each gate/chip      |
| `Main.jack`         | Central control hub for routing UI logic     |

## 🛠️ Running the Project

1. **Compile Jack Files:**
   ```bash
   JackCompiler.bat
   ```

2. **Launch the Virtual Machine Emulator:**
   ```bash
   VMEmulator.bat
   ```

3. **Interact through the menu:**  
   Choose a module, view chip descriptions, enter inputs, and simulate their behavior live.

> Requires the Nand2Tetris toolset and Java. Compatible with Windows (batch scripts provided); use equivalent `.sh` or manual steps on macOS/Linux.

## ✨ To-Do / Future Work

- Expand to support custom chip design inputs
- Implement waveform-style visualization
- Integrate persistent input/output logging

## 📄 License

MIT License

---

🎓 Developed as part of a system architecture learning journey inspired by Nand2Tetris.
