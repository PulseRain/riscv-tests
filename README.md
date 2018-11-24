Dhrystone for RV32I Instruction Set
===================================

Introduction
------------

This repository is a fork of https://github.com/riscv/riscv-tests
 
And the purpose of this repository is to provide a RV32I (or RV32IM) flavor of Dhrystone that can be run on [PulseRain Reindeer Soft CPU](https://github.com/PulseRain/Reindeer)


Building from repository
-----------------------------

It is assumed that Zephyr SDK 0.9.5 has been installed at its default location, and __riscv32-zephyr-elf-__ cross-compiler can be accessed anywhere. 

To build the Dhrystone, do the following:

    $ git clone https://github.com/PulseRain/riscv-tests.git
    $ cd riscv-tests/benchmarks
    $ make clean
    $ make

And the result elf file is dhrystone.riscv.
