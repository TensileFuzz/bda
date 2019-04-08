# BDA: Practical Dependence Analysis for Binary Executables by Unbiased Whole-program Path Sampling and Per-path Abstract Interpretation

## Description

Please install [radare2](https://github.com/radare/radare2) on your machine first. After that, following executable could run directly on Ubuntu 16.04.

+ `rexe`: Sampling-based abstract interpreter

+ `rgdb`: GDB for sampling-based abstract interpretr

+ `rdep`: Sampling-based posterior analyzer

+ `rinfo`: Binary basic information dumper


## Basic Usage

```bash
./rexe -t 1000 <binary>
./rdep -d <refer.dep> <binary>
```

You can also set log level for more information, as follows

```bash
RUST_LOG=info ./rexe -t 1000 <binary>
RUST_LOG=info ./rdep -d <refer.dep> <binary>
```

## More

`rgdb` could also help you debug abstract interpreter.

```bash
./rgdb <binary>
```

## Postscript

**Documents** and **Source Code** will come soon... 
