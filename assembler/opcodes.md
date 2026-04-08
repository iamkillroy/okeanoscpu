# Design Philosophy

The design of this CPU is mirroring other architectures that I understand. Primarily, the idea is that instructions can be repeated generally on multiple registers. This is supposed to, at a low level, speed up matrix mathematics. By interfacing directly with this at a low level, this ought to provide extreme cost savings for matrix math.

# Opcode Table

### BRK - Break (0x00)
