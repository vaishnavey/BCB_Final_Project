# Original study
The objective is to assess different available AMBER forcefields for modeling interactions between DNA and a minor groove binding ligand, which helps gain useful insights into drug design. \n
The study assessed seven versions of the AMBER force field pre-embedded in GROMACS: AMBER03, AMBER94, AMBER96, AMBER99, AMBER99SB, AMBER99SB-ILDN, and AMBERGS.\n
Each force field represents the interaction potential of the molecular system through bonded and non-bonded interactions.\n
Here are the steps involved with each forch field:
* Obtaining structure files for DNA and ligand
  1. ligand topologies were generated using the ANTECHAMBER module via the acpype.py script
  2. DNA topologies are generated from the force fields
* Optimizing molecular geometry of ligand (using DFT and Gaussian)
* Molecular docking to determine the ligand binding groove
* Molecular Dynamics simulations to study stability and time evolution of the DNA-ligand complex
  1. Solvation and neutralization
  2. Energy minimization
  3. NVT and NPT equilibration
  4. 100ns simulation

# Replication of analysis
