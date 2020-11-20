# LAMMPS integration with RexPon and PQEQ
Our final project focuses on helping Jose Cobeña-Reyes (USC Chemical Engineering PhD student) with integrating RexPon and PQEQ (Polarizable Charge Equilibration) into the newest version of LAMMPS.
## LAMMPS
LAMMPS is an acronym for Large-scale Atomic/Molecular Massively Parallel Simulator.

## RexPon
RexPon is based on the [paper](https://aip.scitation.org/doi/pdf/10.1063/1.5042658) written by Saber Naserifar from Caltech.

The package is using quantum mechanics-based polarizable force field for water simulations, thus creating a super accurate result.

RexPon code is not shared here since Jose asked us to keep it confidential, the author Saber Naserifar is still working on it before releasing it to the public.

## What we are trying to solve

The newest version of LAMMPS (Oct. 30) is compatible with Widom Insertion Algorithm.
Jose wants to run a simulation using Widom Insertion Algorithm with RexPon in LAMMPS.

RexPon is not compatible with the new LAMMPS and we are fixing bugs and integrate the RexPon Package and PQEQ into LAMMPS. 
