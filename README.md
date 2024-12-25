## NAME:T.V.YAMUNA SHRI VARDHINI
## REG NO:24003856
# EXPERIMENT 6: IMPLEMENTATION OF SISO SHIFT REGISTER

## AIM
To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

## SOFTWARE REQUIRED

Quartus prime

## THEORY

## SISO SHIFT REGISTER

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

## PROCEDURE
 1. Launch Quartus on your computer and create a new project:
 Go to File → New Project Wizard.
 Specify the project name, directory, and top-level entity name (e.g., SISO)
 2. Create the JK Flip-Flop Circuit and implement the SISO by writing VHDL/Verilog code.
 Go to File → New → Select Verilog File.
 3. Compile the Project
 Click on Processing → Start Compilation.
 Fix any syntax or schematic errors if present.
 4. Simulate the Circuit:
 Go to Tools → University Program VWF.
 Define the inputs for sin, and CLK in the waveform editor.
 Run the simulation and observe the waveforms.
 5. Verify the Results.
## TRUTH TABLE
![DE EXP 6 TRUTH TABLE](https://github.com/user-attachments/assets/aead3bb0-86d1-4b29-b1f2-44dbf7c1ab4a)

## PROGRAM
![DE EXP 6 CODING](https://github.com/user-attachments/assets/c0ea69c7-394a-41be-a460-8082fb5e513c)

## RTL
![DE EXP 6 RTL](https://github.com/user-attachments/assets/93d454d4-492e-452a-a51d-44efafa70cbd)

## TIMING DIAGRAM
![DE EXP 6 TIMING DIAGRAM](https://github.com/user-attachments/assets/00bafdac-1e2c-484e-9e19-d749ea4bbf2b)

## RESULT
 Implementation of SISO Shift Register using verilog and validating their functionality using their
 functional tables is verified.
