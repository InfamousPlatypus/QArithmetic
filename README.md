# QArithmetic
Arithmetic library for IBM Qiskit

This is our great, awesome, extremely impressive, daunting, inspiring arithmetic library

List of operations implemented:

# Bit-wise operations

Controlled Toffoli gate (qc,ctrl,a,b,c)

qc->quantum circuit, ctrl->control bit, a->toffoli control input 1, b->toffoli control input 2, c->target qubit

Logical AND (qc, a, b, c, N)

qc->quantum circuit, a->input1, b->input2, c->output, N->bit-string length

Logical OR (qc, a, b, c, N)

qc->quantum circuit, a->input1, b->input2, c->output, N->bit-string length

Logical XOR (qc, a, b, c, N)

qc->quantum circuit, a->input1, b->input2, c->output, N->bit-string length

Logical NOT (qc, a, c, N)

qc->quantum circuit, a->input, c->output, N->bit-string length

Shift right (qc,reg,N,shift)

qc->quantum circuit, reg->shift register, N->shift register bit-length, shift->shift amount

Shift left (qc,reg,N,shift)

qc->quantum circuit, reg->shift register, N->shift register bit-length, shift->shift amount


# Arithmetic operations

QFT-based add (Draper adder)

Ripple carry add

QFT-based sub

Ripple carry sub

Sub-and-swap

Multiply

Divide

