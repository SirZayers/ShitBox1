# ShitBox1
A 16 bit computer emulator

## Technical spefications

16 16bit general purpose registers R0-R15
7 16bit special registers sp (stack pointer), bp (base pointer), pc (program counter), osp (os stack pointer), obp (os base pointer), rpc (reserve program counter for saving a processes pc when it is interrupted)
2 stacks one for operating system and one for currently executing process (save stack when process is blocked by os)
Flags(Zero, Negative, Positive, Kernel-/Usermode, Disable interrupts, )
16 bit addresses
32bit instructions (8 op code, 4 dest, 4 sr1, 16 immediate/sr2)
2¹⁶-1 byte memory
list of process stacks
