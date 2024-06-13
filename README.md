# Amplitude Modulator Circuit using BJT and Resistors

This project involves building an amplitude modulator circuit using a Bipolar Junction Transistor (BJT) and resistors. The circuit is designed to modulate the amplitude of a carrier signal using an input signal. Capacitors and inductors are used in the simulation to achieve the desired modulation effect.

## Table of Contents

- [Introduction](#introduction)
- [Components Needed](#components-needed)
- [Circuit Diagram](#circuit-diagram)
- [Assembly Instructions](#assembly-instructions)
- [Testing and Verification](#testing-and-verification)
- [Applications](#applications)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to design and build an amplitude modulator circuit using a BJT and resistors. The circuit modulates the amplitude of a carrier signal in accordance with an input signal. While capacitors and inductors are essential for the modulation process, they are included in the simulation for practical purposes.

## Components Needed

- Bipolar Junction Transistor (BJT)
- Resistors (various values)
- Capacitors (included in the simulation)
- Inductors (included in the simulation)
- Signal generator (for input signal and carrier signal)
- Oscilloscope (for output signal observation)
- Breadboard and connecting wires
- Soldering tools and accessories (if needed)

## Circuit Diagram

![1718285606996](https://github.com/Dhruvvisariya/AM/assets/98723934/4893dc5e-b7ec-4b6d-92bd-75de07bd4025)

## Simulator Output 
<img width="1118" alt="CKT1" src="https://github.com/Dhruvvisariya/AM/assets/98723934/73005ee0-9785-43ed-8ddb-a56598b14541">


## Assembly Instructions

1. **Transistor Configuration**:
   - Configure the BJT in a common emitter configuration.
   - Connect the base of the BJT to a resistor network that sets the biasing point.

2. **Biasing Resistors**:
   - Select appropriate resistor values to bias the BJT for proper operation.
   - Connect the resistors to form a voltage divider network that provides the necessary base current.

3. **Input Signal**:
   - Connect the input signal (modulating signal) to the base of the BJT through a coupling capacitor (included in the simulation).

4. **Carrier Signal**:
   - Connect the carrier signal to the collector of the BJT through an LC tank circuit (inductor and capacitor included in the simulation).
   - Ensure the carrier signal is at a higher frequency compared to the input signal.

5. **Output Signal**:
   - Take the modulated output signal from the collector of the BJT.
   - Connect this output to an oscilloscope to observe the modulation effect.

## Testing and Verification

1. **Initial Testing**:
   - Before powering up the circuit, double-check all connections for correctness.
   - Ensure that there are no short circuits or loose connections.

2. **Power On**:
   - Connect the signal generators to the circuit.
   - Set the desired input (modulating) signal and carrier signal frequencies.

3. **Observation**:
   - Use an oscilloscope to observe the output signal at the collector of the BJT.
   - Verify that the amplitude of the carrier signal is modulated by the input signal.

4. **Adjustment**:
   - Adjust the biasing resistors and signal amplitudes if necessary to achieve optimal modulation.

## Applications

- Amplitude modulation in communication systems
- Educational projects to demonstrate the principles of amplitude modulation
- Signal processing experiments

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.

---

This README provides an overview of the Amplitude Modulator Circuit project, including setup instructions and usage guidelines. Insert images in the specified spaces to enhance the documentation.
