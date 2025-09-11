🌀 Quantum Teleportation



📖 Introduction

Quantum Teleportation is a fundamental protocol in quantum information science that allows the transfer of a quantum state from one location to another without physically moving the particle itself.

Unlike sci-fi teleportation, no matter or energy is transported directly. Instead, information about the quantum state is transmitted using a combination of:

Quantum entanglement

Classical communication

⚡ How It Works

Entanglement Sharing

Two parties, traditionally called Alice and Bob, share a pair of entangled qubits.

State to Teleport

Alice has a qubit in an unknown quantum state |ψ⟩ that she wants to send to Bob.

Bell Measurement

Alice performs a joint measurement (Bell-state measurement) on her unknown qubit and her half of the entangled pair.

This collapses the system into one of four possible Bell states.

Classical Communication

Alice sends the two classical bits of measurement results to Bob over a normal channel (like the internet).

Reconstruction

Based on Alice’s message, Bob applies a quantum gate (X and/or Z) on his entangled qubit.

The result: Bob’s qubit is now in the exact state |ψ⟩ that Alice had originally!


🔑 Key Points

No Faster-than-Light Communication ⚠️

Classical communication is required, so it still obeys relativity.

State Destruction

The original qubit’s state is destroyed during measurement — no cloning is possible (consistent with the no-cloning theorem).

Applications

Quantum networks & quantum internet

Secure communication (Quantum Key Distribution)

Building blocks for quantum repeaters
