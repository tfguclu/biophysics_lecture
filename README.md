# ⚛️ Biophysics (MBG211): Course Syllabus & Lecture Notes

**Based on Phillips, Kondev, Theriot & Garcia, *Physical Biology of the Cell* (2nd Edition)**
**Audience:** 2nd-year Molecular Biology & Genetics students (algebra + basic calculus)
**Length:** 13 Weeks (Midterm in Week 8)

---

## 📘 Course Description

This course teaches students to **think about living systems as physical systems**. The emphasis is on **order-of-magnitude reasoning, simple models, and a few key equations**, not on heavy derivations. Students will learn:

- How big, how many, and how fast: the numbers that describe cells and molecules.
- Why water, electrostatics, and entropy shape the structure of biomolecules.
- How free energy decides binding, folding, and transport.
- How cells generate and use voltages: ion channels, action potentials, nerve conduction.
- How molecular motors produce force (muscle), and how radiation damages biomolecules.
- How physical principles explain disease and underpin clinical technologies.

**Main text:** *Physical Biology of the Cell* (PBoC), 2nd ed.
**Supplementary:** Hobbie & Roth, *Intermediate Physics for Medicine and Biology* (radiation, clinical); Serdyuk, Zaccai & Zaccai, *Methods in Molecular Biophysics* (structure determination); Kuriyan, Konforti & Wemmer, *The Molecules of Life* (water, intermolecular forces).

---

## 🎯 Course Learning Outcomes

By the end of the course, you should be able to:

1. **Apply** general principles of physics (force, heat, electric and magnetic fields) to matter and biomolecules.
2. **Explain** why the laws of physics are needed to understand biological phenomena.
3. **Discuss** the basic principles of neuronal transmission.
4. **Relate** molecular and physical interactions to the mechanisms of disease.
5. **Integrate** interdisciplinary (physics–biology) reasoning into problem solving.

---

## 📅 13-Week Schedule Overview

| Week | Unit | Core Focus | PBoC Chapters\* | Supplement | Key Concept (Simplified) |
|---|---|---|---|---|---|
| **1** | **I. Foundations** | Introduction to Biophysics | Ch. 1–3 | — | Biology is quantitative: estimate sizes, numbers, energies, and times. |
| **2** | **I. Foundations** | Water & Molecular Structure | Ch. 2, 5, 9 | Kuriyan Ch. 6 | Water's hydrogen bonds and high dielectric constant set the rules for everything else. |
| **3** | **I. Foundations** | Biomolecules as Physical Objects | Ch. 8, 10 | — | DNA and proteins are polymers; stiffness and entropy decide their shapes. |
| **4** | **II. Methods** | Structure Determination Methods | Ch. 2 (partial) | Serdyuk et al. | We "see" molecules by scattering waves shorter than the object. |
| **5** | **II. Energy** | Thermodynamics & Bioenergetics | Ch. 5, 6 | — | Free energy = energy − T × entropy; kBT is the unit of biological energy. |
| **6** | **II. Energy** | Proteins: Binding, Folding, Cooperativity | Ch. 7, 8 | — | Two-state models explain binding, switching, and cooperativity. |
| **7** | **III. Membranes** | Membrane Structure & Transport | Ch. 11, 13 | — | Membranes are self-assembled 2D fluids; diffusion is fast over short distances only. |
| **8** | **Midterm** | Review & Exam | Weeks 1–7 | — | Estimates, free energy, binding, diffusion. |
| **9** | **IV. Electricity** | Ion Channels | Ch. 7, 11, 17 | — | Channels are two-state gates controlled by voltage, ligands, or tension. |
| **10** | **IV. Electricity** | Resting & Action Potential; Nerve Conduction | Ch. 17 | — | Ion gradients store energy; channels turn it into electrical signals. |
| **11** | **V. Force** | Muscle Contraction | Ch. 16 | — | Motors convert ATP into steps and force; muscle is millions of motors in series and parallel. |
| **12** | **V. Radiation** | Radiation & Biomolecules | Ch. 18 | Hobbie & Roth | Photon energy decides the effect: excitation (light) vs. ionization (X-rays, γ). |
| **13** | **VI. Synthesis** | Clinical Applications of Biophysics | Selected | Hobbie & Roth | Diseases are often physical failures: misfolding, aggregation, broken channels. |

\*Chapters may be assigned in part. Supplementary chapter numbers depend on edition; exact sections will be announced weekly.

---

# 📝 Weekly Lecture Notes

---

## 📅 Week 1 – Introduction to Biophysics: Biology by the Numbers

**Reading:** PBoC Ch. 1 (Biology by the Numbers), Ch. 2 & 3 (selected sections)

### ❓ Big Question
Can we understand a living cell with a pencil, a few numbers, and physical reasoning?

### 🗝️ Key Concepts
- **What is biophysics?**
  Using the laws of physics (mechanics, thermodynamics, electrostatics) and quantitative models to explain biological phenomena.
- **Measurement, units, and SI:**
  - Base units (m, kg, s, A, K, mol) and derived units (N, J, Pa, V, C).
  - Biological units: nm, µm, pN, ms, mV, µM.
  - Unit conversion and dimensional analysis as error checks.
- **Order-of-magnitude estimates ("Fermi problems"):**
  - *E. coli*: ~1 µm³ volume, ~1 pg mass, ~20 min division time.
  - 1 molecule in an *E. coli* ≈ 1 nM concentration.
  - Typical protein: ~5 nm diameter, ~30 kDa.
- **Scales of life:** from atoms (0.1 nm) to proteins (nm) to cells (µm) to organisms (m); from bond vibrations (fs) to cell cycles (hours).
- **Models in biology:** "toy" models (springs, two-state switches, random walks) that capture the essential physics.

### 🦠 Case Study: How Many Proteins in a Bacterium?
Using cell volume, density, and the fraction of dry mass that is protein, estimate ~3 × 10⁶ proteins per *E. coli* cell. A single back-of-the-envelope calculation reveals how crowded the cytoplasm is.

### 🔢 Key Numbers
- 1 nM in 1 µm³ ≈ 1 molecule
- Avogadro's number: 6.022 × 10²³ mol⁻¹

### 📖 Vocabulary
- **Dimensional analysis:** Checking equations by comparing units.
- **Order of magnitude:** Power of ten describing a quantity's size.
- **Model:** A simplified physical description that makes testable predictions.

---

## 📅 Week 2 – Water & the Molecular Structure of Life

**Reading:** PBoC Ch. 2 (cell components), Ch. 5 (equilibrium, selected), Ch. 9 (Electrostatics for Salty Solutions, intro sections); Kuriyan Ch. 6 (optional)

### ❓ Big Question
Why is water, a tiny three-atom molecule, the most important "biomolecule"?

### 🗝️ Key Concepts
- **Chemical bonds and their energies:**
  - Covalent bonds: ~100 kBT (stable at body temperature).
  - Non-covalent interactions: hydrogen bonds, ionic, van der Waals: ~1–10 kBT (breakable by thermal motion).
- **Structure of water:**
  - Bent geometry (104.5°), dipole moment, tetrahedral hydrogen-bond network.
  - High heat capacity, high heat of vaporization, and high surface tension all come from H-bonds.
- **Water as a solvent:**
  - High dielectric constant (ε ≈ 80) weakens electrostatic interactions ~80× compared to vacuum.
  - Hydration shells around ions.
- **Electrostatics in salty solutions:**
  - Coulomb's law.
  - **Bjerrum length** (~0.7 nm): distance where electrostatic energy = kBT.
  - **Debye screening length** (~1 nm at 150 mM): charges are "hidden" beyond this distance.
- **Hydrophobic effect:**
  Nonpolar molecules disturb the water H-bond network. Water minimizes contact, which drives protein folding and membrane formation. This is an *entropic* effect.
- **Role of water in the organism:** ~60–70% of body mass, temperature buffering, transport, participation in reactions (hydrolysis).

### 💧 Case Study: Oil and Water
Oil droplets coalesce not because oil molecules attract each other strongly, but because water "prefers" to maximize its own H-bonding. This is the same force that buries hydrophobic residues inside proteins.

### 🔢 Key Numbers
- kBT ≈ 4.1 pN·nm ≈ 2.5 kJ/mol ≈ 0.6 kcal/mol (at 300 K)
- Water concentration: ~55 M

### 📖 Vocabulary
- **Hydrogen bond:** Attraction between an H on an electronegative atom and a lone pair on another.
- **Dielectric constant:** How strongly a medium weakens electric fields.
- **Debye length:** Distance over which ions screen a charge.
- **Hydrophobic effect:** Tendency of nonpolar groups to cluster in water.

---

## 📅 Week 3 – Biophysical Features of Biomolecules

**Reading:** PBoC Ch. 8 (Random Walks and the Structure of Macromolecules), Ch. 10 (Beam Theory, selected)

### ❓ Big Question
How does a 2-meter-long DNA molecule fit inside a nucleus a few micrometers wide?

### 🗝️ Key Concepts
- **Biomolecules as polymers:** DNA, RNA, and proteins are chains of monomers; polysaccharides and lipids complete the set.
- **Random walk model of polymers:**
  - Chain of N segments of length b → typical size R ≈ b√N.
  - Entropy favors coiled, disordered states.
- **Persistence length:**
  - Length over which a polymer "remembers" its direction.
  - DNA: ~50 nm (stiff at short scales, floppy at long scales).
  - Actin: ~10 µm; microtubules: ~mm.
- **Bending energy (beam theory):** Bending stiff filaments costs energy; this is why packaging DNA requires proteins (histones) and energy.
- **Entropic elasticity:** Stretching a polymer reduces its entropy → it acts like a spring (force–extension curves, optical tweezers).

### 🧬 Case Study: DNA Packing in Viruses
Bacteriophages pack DNA to near-crystalline density inside their capsids using an ATP-driven motor. The internal pressure (tens of atmospheres) comes from bending energy and electrostatic repulsion of DNA.

### 🔢 Key Equations
- R ≈ b√N (random walk size)
- DNA persistence length ξ_p ≈ 50 nm ≈ 150 bp

### 📖 Vocabulary
- **Persistence length:** Stiffness measure of a polymer.
- **Random walk:** Path made of successive random steps.
- **Entropic spring:** Restoring force arising from entropy, not bond stretching.

---

## 📅 Week 4 – Biophysical Methods for Structure Determination

**Reading:** Serdyuk, Zaccai & Zaccai (selected chapters); PBoC Ch. 2 (structural data sections)

### ❓ Big Question
How can we "see" a molecule that is thousands of times smaller than the wavelength of visible light?

### 🗝️ Key Concepts
- **Resolution limit:** You cannot resolve details smaller than ~λ/2. Visible light (~500 nm) cannot show atoms → need X-rays (~0.1 nm) or electrons (pm wavelength).
- **X-ray crystallography:**
  - Crystals scatter X-rays into diffraction spots (Bragg's law: nλ = 2d sinθ).
  - The phase problem; electron density maps; model building.
- **NMR spectroscopy:**
  - Nuclear spins in a magnetic field; chemical shifts; distance restraints (NOE).
  - Structures and dynamics in solution.
- **Cryo-electron microscopy (cryo-EM):**
  - Flash-frozen samples; averaging thousands of particle images.
  - "Resolution revolution": near-atomic structures of large complexes.
- **Spectroscopic and single-molecule methods:**
  - UV-Vis absorbance, fluorescence, circular dichroism (secondary structure).
  - FRET as a "molecular ruler" (1–10 nm).
  - Optical tweezers and AFM for forces (pN).
- **Computational methods:**
  - Molecular dynamics (MD) simulations.
  - AI structure prediction (AlphaFold) and its limits.

### 🔬 Case Study: The Double Helix
Rosalind Franklin's "Photo 51" X-ray pattern (the X shape and layer spacings) revealed the helical geometry of DNA: 3.4 Å rise per base, 34 Å per turn.

### 🔢 Key Equations
- Bragg's law: nλ = 2d sinθ
- FRET efficiency: E = 1 / [1 + (r/R₀)⁶]

### 📖 Vocabulary
- **Diffraction:** Bending and interference of waves around periodic objects.
- **Resolution:** Smallest distinguishable detail.
- **FRET:** Distance-dependent energy transfer between two fluorophores.

---

## 📅 Week 5 – Thermodynamics & Bioenergetics

**Reading:** PBoC Ch. 5 (Mechanical and Chemical Equilibrium in the Living Cell), Ch. 6 (Entropy Rules!)

### ❓ Big Question
How do living systems stay highly ordered when the universe tends toward disorder?

### 🗝️ Key Concepts
- **Work, energy, and metabolism:** Cells convert chemical energy (food, light) into work: mechanical, chemical, and electrical.
- **Laws of thermodynamics:**
  - First law: energy is conserved.
  - Second law: total entropy of an isolated system increases.
  - Living cells are **open systems**: they reduce internal entropy by increasing the entropy of their surroundings (heat, waste).
- **Entropy as counting:** S = kB ln W (number of microstates).
- **Boltzmann distribution:** Probability of a state ∝ e^(−E/kBT). The central equation of statistical biophysics.
- **Free energy:**
  - G = H − TS; spontaneous processes have ΔG < 0.
  - ΔG = ΔG° + RT ln Q; at equilibrium, ΔG° = −RT ln K.
- **Chemical potential:** μ = μ° + kBT ln c. Drives diffusion and reactions.
- **Energy flow and ATP:** ATP hydrolysis ~20 kBT under cellular conditions (far from equilibrium). Coupling unfavorable reactions to ATP.

### 🔋 Case Study: The Cell's Energy Budget
Estimate how many ATP molecules an *E. coli* needs to build a new cell in 20 minutes (~10¹⁰ ATP). Where does it go? Mostly into protein synthesis.

### 🔢 Key Equations
- p(E) ∝ e^(−E/kBT)
- ΔG° = −RT ln K
- ΔG_ATP ≈ −20 kBT (in the cell)

### 📖 Vocabulary
- **Entropy:** Measure of the number of accessible microstates.
- **Free energy:** Energy available to do work at constant T and P.
- **Chemical potential:** Free energy per molecule; drives flows.

---

## 📅 Week 6 – Proteins: Binding, Folding & Cooperativity

**Reading:** PBoC Ch. 7 (Two-State Systems: From Ion Channels to Cooperative Binding), Ch. 8 (protein folding sections)

### ❓ Big Question
How does a chain of amino acids fold into one precise shape, and how do proteins act as molecular switches?

### 🗝️ Key Concepts
- **Protein structure hierarchy:** primary → secondary (α-helix, β-sheet) → tertiary → quaternary.
- **Forces in protein folding:** hydrophobic effect (dominant), H-bonds, salt bridges, van der Waals, conformational entropy (opposes folding).
- **Levinthal's paradox and the energy landscape:** Proteins don't search all conformations; they follow a funnel-shaped landscape.
- **Folding stability:** ΔG_fold is small (~5–15 kcal/mol). Proteins are only marginally stable, so mutations easily destabilize them.
- **Two-state models:**
  - Ligand binding: p_bound = (c/K_d) / (1 + c/K_d).
  - Dissociation constant K_d and binding affinity.
- **Cooperativity:**
  - Hill equation and Hill coefficient.
  - MWC model: allosteric proteins switch between two conformations.

### 🩸 Case Study: Hemoglobin
Hemoglobin binds O₂ cooperatively (Hill coefficient ~2.8). Its sigmoidal curve lets it load oxygen in the lungs and unload it efficiently in tissues. A non-cooperative protein (myoglobin) could not do this.

### 🔢 Key Equations
- p_bound = (c/K_d)ⁿ / [1 + (c/K_d)ⁿ] (Hill)
- ΔG = −RT ln(1/K_d)

### 📖 Vocabulary
- **K_d:** Ligand concentration at which half the proteins are bound.
- **Cooperativity:** Binding of one ligand changes the affinity for the next.
- **Allostery:** Regulation through binding at a distant site.

---

## 📅 Week 7 – Membrane Structure & Transport

**Reading:** PBoC Ch. 11 (Biological Membranes: Life in Two Dimensions), Ch. 13 (A Statistical View of Biological Dynamics: diffusion)

### ❓ Big Question
How does a 5-nm-thick fatty film keep the cell's inside separate from the outside, yet let the right things through?

### 🗝️ Key Concepts
- **Lipid self-assembly:** Amphiphilic lipids form bilayers spontaneously because of the hydrophobic effect.
- **Fluid mosaic model:** Membrane is a 2D fluid; proteins and lipids diffuse laterally. Rafts and cytoskeletal anchoring.
- **Membrane mechanics:** Bending stiffness (~20 kBT), tension, curvature, vesicle formation.
- **Diffusion:**
  - Random walk of molecules; Fick's laws.
  - Diffusion time t ≈ L²/2D. Fast over µm, very slow over cm → why large organisms need circulation.
- **Osmosis:** Water flows toward higher solute concentration; van 't Hoff osmotic pressure Π = cRT.
- **Transport mechanisms:**
  - Passive: simple diffusion (small nonpolar molecules), facilitated diffusion (channels, carriers).
  - Active: primary (Na⁺/K⁺-ATPase) and secondary (symporters, antiporters).
  - Bulk: endocytosis, exocytosis.

### 🔴 Case Study: Red Blood Cells in Different Solutions
In hypotonic solution, RBCs swell and lyse; in hypertonic solution, they shrink (crenation). Osmotic pressure differences of just a few % are enough, which is why IV fluids must be isotonic (0.9% NaCl).

### 🔢 Key Equations
- t ≈ L²/(2D)
- J = −D (dc/dx) (Fick's first law)
- Π = cRT (van 't Hoff)

### 📖 Vocabulary
- **Amphiphilic:** Having both hydrophilic and hydrophobic parts.
- **Diffusion coefficient (D):** How fast a molecule spreads (µm²/s).
- **Osmotic pressure:** Pressure needed to stop water flow across a membrane.

---

## 📅 Week 8 – Midterm Review & Exam

**Content Covered:** Weeks 1–7

### 📝 Study Guide
Be prepared to:
- **Estimate** sizes, concentrations, and numbers of molecules in cells; convert units correctly.
- **Explain** water's special properties and the hydrophobic effect.
- **Use** kBT as an energy scale; compare bond energies to thermal energy.
- **Apply** the Boltzmann distribution and ΔG° = −RT ln K.
- **Calculate** binding probabilities from K_d; interpret Hill curves.
- **Estimate** diffusion times; explain osmosis and transport types.
- **Compare** structure-determination methods (what each can and cannot see).

The midterm focuses on **short calculations, estimates, and conceptual explanations.**

---

## 📅 Week 9 – Ion Channels

**Reading:** PBoC Ch. 7 (ion channel sections), Ch. 11 (mechanosensitive channels), Ch. 17 (intro sections)

### ❓ Big Question
How can a single protein let millions of ions per second pass, yet choose K⁺ over the smaller Na⁺?

### 🗝️ Key Concepts
- **Why channels are needed:** Ions cannot cross the hydrophobic bilayer (large desolvation energy).
- **Channel types by gating stimulus:**
  - Voltage-gated (Na⁺, K⁺, Ca²⁺ channels).
  - Ligand-gated (acetylcholine receptor).
  - Mechanosensitive (MscL, Piezo).
- **Selectivity:** The K⁺ channel selectivity filter mimics water's hydration shell for K⁺ but not for Na⁺.
- **Gating as a two-state system:** P_open = 1 / (1 + e^(ΔG/kBT)), where ΔG depends on voltage (gating charge × V) or tension.
- **Single-channel recordings:** Patch clamp shows discrete open/closed currents (pA).
- **Conductance:** I = g(V − E_rev); channels as resistors.

### ⚡ Case Study: The Bacterial Pressure Valve (MscL)
When bacteria are placed in fresh water, they swell. MscL opens under high membrane tension, releasing solutes and preventing the cell from bursting. This is a pure mechanical two-state switch.

### 🔢 Key Equations
- P_open = 1 / [1 + e^((ΔG₀ − qV)/kBT)]
- Single-channel current ~1–10 pA

### 📖 Vocabulary
- **Gating:** Opening/closing of a channel in response to a stimulus.
- **Selectivity filter:** Narrow region that discriminates between ions.
- **Patch clamp:** Technique to measure currents through single channels.

---

## 📅 Week 10 – Resting & Action Potential; Nerve Conduction

**Reading:** PBoC Ch. 17 (Biological Electricity and the Hodgkin–Huxley Model)

### ❓ Big Question
How does a nerve cell send an electrical signal over a meter without it fading away?

### 🗝️ Key Concepts
- **Electrical properties of cells:**
  - Membrane as a capacitor (~1 µF/cm²); channels as resistors.
  - Very few ions need to cross to change the voltage.
- **Resting potential:**
  - Nernst equation for a single ion: E = (kBT/ze) ln(c_out/c_in).
  - E_K ≈ −90 mV, E_Na ≈ +60 mV.
  - Goldman–Hodgkin–Katz (GHK) equation for multiple ions → V_rest ≈ −70 mV.
  - Na⁺/K⁺-ATPase maintains the gradients.
- **Action potential:**
  - Threshold, depolarization (Na⁺ influx), repolarization (K⁺ efflux), hyperpolarization, refractory period.
  - All-or-none response.
- **Hodgkin–Huxley model:** Equivalent circuit with voltage-dependent Na⁺ and K⁺ conductances (m, h, n gating variables).
- **Propagation:**
  - Cable theory: signals decay passively over the length constant λ.
  - Action potentials regenerate the signal.
  - **Myelin:** Increases resistance, decreases capacitance → saltatory conduction between nodes of Ranvier (up to ~100 m/s).
- **Synaptic transmission:** Ca²⁺-triggered neurotransmitter release; postsynaptic potentials.

### 🦑 Case Study: The Squid Giant Axon
Hodgkin and Huxley used the ~0.5-mm-diameter squid axon to insert electrodes and measure ionic currents with voltage clamp. Their model (1952, Nobel 1963) remains the foundation of neuroscience.

### 🔢 Key Equations
- Nernst: E = (RT/zF) ln(c_out/c_in) ≈ (61.5 mV/z) log₁₀(c_out/c_in) at 37 °C
- C dV/dt = −Σ g_i (V − E_i) + I_ext
- Conduction velocity: unmyelinated ~1 m/s; myelinated ~10–100 m/s

### 📖 Vocabulary
- **Depolarization:** Membrane potential becoming less negative.
- **Voltage clamp:** Holding V constant to measure ionic currents.
- **Saltatory conduction:** "Jumping" of action potentials between nodes of Ranvier.

---

## 📅 Week 11 – Muscle Contraction

**Reading:** PBoC Ch. 16 (Dynamics of Molecular Motors)

### ❓ Big Question
How do nanometer-sized protein steps add up to lifting a weight?

### 🗝️ Key Concepts
- **Molecular motors:** Myosin, kinesin, dynein convert ATP hydrolysis into directed motion.
  - Kinesin: 8 nm steps on microtubules.
  - Myosin II: ~5–10 nm power stroke on actin, forces of a few pN.
- **Mechanochemical cycle:** ATP binding → detachment → hydrolysis → reattachment → power stroke (ADP + Pi release).
- **Brownian ratchet vs. power stroke:** Motors rectify thermal fluctuations using ATP energy.
- **Efficiency:** Work per step (force × distance) compared with ~20 kBT from ATP.
- **Muscle architecture:**
  - Sarcomere: thick (myosin) and thin (actin) filaments; sliding filament theory.
  - Motors in parallel → force; sarcomeres in series → speed.
- **Excitation–contraction coupling:** Action potential → Ca²⁺ release from sarcoplasmic reticulum → troponin/tropomyosin shift → cross-bridge cycling.
- **Force–velocity relationship (Hill's muscle equation):** Faster contraction → less force.

### 💪 Case Study: Rigor Mortis
After death, ATP is depleted. Myosin heads stay bound to actin because ATP is needed to detach them, so muscles become stiff. This directly demonstrates the ATP-dependent step of the cross-bridge cycle.

### 🔢 Key Numbers
- Myosin force: ~1–5 pN per head
- Work per ATP: ~5 pN × 8 nm = 40 pN·nm ≈ 10 kBT (~50% efficiency)

### 📖 Vocabulary
- **Sarcomere:** Basic contractile unit of striated muscle.
- **Cross-bridge:** Myosin head attached to actin.
- **Processivity:** Ability of a motor to take many steps without detaching.

---

## 📅 Week 12 – Radiation & Biomolecules

**Reading:** PBoC Ch. 18 (Light and Life); Hobbie & Roth (interaction of photons and charged particles with matter; selected sections)

### ❓ Big Question
Why does visible light let us see, while X-rays can break DNA?

### 🗝️ Key Concepts
- **Electromagnetic spectrum:** Photon energy E = hν = hc/λ. Radio → microwave → IR → visible → UV → X-ray → γ.
- **Non-ionizing radiation:**
  - Absorption and electronic excitation (chlorophyll, retinal, fluorophores).
  - Vision: one photon isomerizes retinal → rhodopsin signaling cascade.
  - Photosynthesis: converting photon energy into chemical gradients.
  - UV: thymine dimers in DNA.
- **Ionizing radiation (> ~10 eV):**
  - α, β, γ, X-rays, neutrons; interaction with matter (photoelectric effect, Compton scattering, pair production).
  - Direct damage vs. indirect damage (water radiolysis → OH• radicals).
  - DNA single- and double-strand breaks; repair pathways.
- **Dosimetry:**
  - Absorbed dose: Gray (Gy = J/kg); equivalent dose: Sievert (Sv).
  - Radiation weighting factors; background exposure (~2–3 mSv/year).
- **Radioactive decay:** Half-life, exponential decay N(t) = N₀ e^(−λt).
- **Radiation in molecular biology & genetics:** Radioisotope labeling (³²P, ³⁵S), mutagenesis, radiation-induced mutations.

### ☀️ Case Study: Xeroderma Pigmentosum
Patients lack nucleotide excision repair, so UV-induced thymine dimers are not fixed. The result is extreme sun sensitivity and a very high skin cancer risk. The disease is a direct link from photon physics to genetics.

### 🔢 Key Equations
- E = hc/λ (1240 eV·nm / λ)
- N(t) = N₀ e^(−λt); t½ = ln2/λ

### 📖 Vocabulary
- **Ionizing radiation:** Radiation energetic enough to remove electrons from atoms.
- **Gray (Gy):** 1 J of energy absorbed per kg.
- **Free radical:** Reactive species with an unpaired electron.

---

## 📅 Week 13 – Clinical Applications of Biophysical Principles

**Reading:** Hobbie & Roth (medical use of X-rays, nuclear medicine, MRI; selected sections); review articles announced in class

### ❓ Big Question
How do the physical principles from this course help us diagnose and understand disease?

### 🗝️ Key Concepts
- **Diseases as physical failures:**
  - **Misfolding & aggregation:** amyloid (Alzheimer's, Parkinson's); marginal protein stability revisited.
  - **Sickle cell anemia:** one mutation (Glu6Val) → hydrophobic patch → hemoglobin polymerization → rigid RBCs.
  - **Channelopathies:** cystic fibrosis (CFTR Cl⁻ channel), long-QT syndrome, epilepsy.
  - **Demyelination:** multiple sclerosis slows or blocks conduction (cable theory revisited).
- **Imaging technologies:**
  - X-ray and CT: attenuation differences between tissues.
  - MRI: nuclear spin (the same physics as NMR in Week 4), T1/T2 relaxation.
  - PET: positron emitters and coincidence detection.
  - Ultrasound: acoustic impedance and reflection.
- **Electrophysiology in the clinic:** ECG and EEG as sums of cellular electrical activity.
- **Therapeutic uses of physics:**
  - Radiotherapy: dose fractionation, targeting tumors.
  - Defibrillation; hyperthermia; laser surgery.
- **Structure-based drug design:** Binding free energy and K_d revisited.

### 🩺 Case Study: Sickle Cell Disease
A single amino acid change creates a sticky hydrophobic spot on deoxygenated hemoglobin. Above a critical concentration, molecules polymerize into fibers that deform the red blood cell. This connects weeks 2 (hydrophobic effect), 6 (proteins, cooperativity), and 7 (cell mechanics, circulation).

### 📖 Vocabulary
- **Channelopathy:** Disease caused by a defective ion channel.
- **Amyloid:** Insoluble β-sheet-rich protein aggregates.
- **Attenuation:** Reduction in radiation intensity passing through matter.

---

**End of Markdown File**
