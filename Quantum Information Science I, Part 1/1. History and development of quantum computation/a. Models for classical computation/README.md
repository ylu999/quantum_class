### Universality of classical computation

#### Classical Computation
1. Universal: Given any computation that is reasonable, you can solve it on the machine

    Turing Machine

    Lamda-Calculas

2. Not Universal: You can not solve all computation on the machine

    Finite Automata

    Coin

3. Super Universal: Can solve some computation that universal computation cannot solve

    Circuit Model

#### What is Circuit Model
Circuits are only designed for finite size input.

Example:

Multiply 2 n bit numbers, can be 10 bit * 10 bit, but cannot have computation that independent of the size of input, because circuits are specified on particular size of input.

Does the Turing machine with program given by P. And input i halt? -> Uncomputable!

But you can solve it with a family with Circuits. 

Circuit with 2 pow p*i inputs, outputs 

                                        1 Turing Machine Halts
                                        2 Turing Machine Does not Halt


Description of the Circuit should be output of a classical program.

Classical computer input is n(size of circuits), output is quantum circuit of size n, that solves problem for input of size n.

#### Conclusion

#### Circuits VS Turing machine

1. Circuits are universal for classical computation
2. Circuits can describe computations which are beyond what a turing machine can do
3. Circuits can simulate turing machines
