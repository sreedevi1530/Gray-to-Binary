# Gray to Binary Code Converter using Verilog

## 📌 Description

This project implements a **4-bit Gray to Binary Code Converter** using Verilog HDL.

Gray code is converted back into its corresponding binary representation using XOR operations.

## 🔹 Inputs and Outputs

* Input: `gray[3:0]`
* Output: `binary[3:0]`

## 🔹 Conversion Logic

The conversion is performed as:

* `binary[3] = gray[3]`
* `binary[2] = binary[3] XOR gray[2]`
* `binary[1] = binary[2] XOR gray[1]`
* `binary[0] = binary[1] XOR gray[0]`

## 🔹 Example

Gray = `1111`

Binary = `1010`

## 🔹 Applications

* Digital communication
* Rotary encoders
* Digital systems
* Error reduction
* Data conversion circuits

## 🔹 Files

* `gray_to_binary.v` – Verilog design code
* `gray_to_binary_tb.v` – Testbench
* `simulation/waveform.png` – Simulation waveform
* `LICENSE` – Project license

## 🔹 Tools Used

* Verilog HDL
* Icarus Verilog
* GTKWave / ModelSim / Vivado

## 🔹 Result

The 4-bit Gray to Binary Code Converter was successfully designed and verified using Verilog HDL through simulation.
