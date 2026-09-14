# Whole expression and purification protocol:
Methodologically, all expressions and purifications are done as similarly as possible unless otherwise indicated, allowing consistency. Big preps allow to try experiments with low priority efficient and reliably. Also, this protocol robustness has been tested and improved through a decade, allowing a relatively wide range of variations. Mainly, the second purification of the :
## Day -2:
Transform BL21 bacteria with 1ul of plasmid.
Transformation protocol: thaw on ice an aliquote of BL21 (NEB) for 5 minutes, add 1ul of your low copy plasmid (20-100mg/ml -> 20-100ug), wait for 10 minutes, heat shock for 45 sec 42C and back to ice again. After 5 minutes, add 500ul of SOC media and shake 800rmps 60minutes. Plate 100ul of it and put in 37C incubator O/N.
## Day -1:
Take 1 colony from the plate and put it in 120ml liquid LB media in a 250ml baffled flask + antibiotic shaking 170rpms, 37C O/N.
## Day 0:
scale up culture to 12L in 12 2l baffled flasks and grow at 37C shaking 170rpms until optic density 600nm reaches 0.2 (typically, 2h). Then, chill for 60 minutes at 18C 170rpms shaking and induce with 1mM IPTG (1ml) O/N.
## Day 1:
 Separate and collect pellet by centrifugation 4000rpms and resuspended in 300ml Lysis buffer and freeze at -80C if you want to store. Lyse at 70% amplitude 5minutes x 100ml final volume (typically, 500ml) on ice 5s ON / 10s OFF. Spined down for 60min 18000rpms and supernatant sonicated again 5s/100ml to break DNA chains (or add benzonase). Filtrated 0.45uM and put in sample pump 5th floor akta to purify O/N 1ml/min.
Nico affinity protocol: Passes sample through HisTrap HP column equilibrated in buffer A. Washes with Buffer A, 5% buffer B until signal is stable +- 1mAU for 1minute. Gradient up to 100% buffer B 20 CVs.
## Day 2:
Pool peak fractions.
[If protein is still impure: (ie, BRAF) dilute in buffer IEC A up to 4x volume (typically 300ml in total) following IEC with same protocol (+1 day).]
[If tag presents a TEV digestion site and plan to digest: pool fractions and mix with an estimated 1/50 molar ratio of His-TEV (during dialysis to 2l buffer A if directly from IMAC affinity) O/N 4C. Then passed through a gravity flow column Ni-NTA beads equilibrated and washed with buffer A 20mM Imidazole, flow through concentrated for SEC (+1 day).]

 Concentrate the fractions and do SEC O/N with SEC buffer.
## Day 3:
Concentrate peak up to 20mg/ml, flash freeze and store at -80C.
Nico gel filtration protocol: Equilibrates gel filtration column in buffer, injects the sample from the loop, runs the sample collecting fractions and re-equilibrates the column in water.

### Buffers:
Lysis buffer: 500mM NaCl, 50mM Tris pH=8, 5% glycerol, 1ug/ml PEI, 0.05% Triton-X 100, 1 EDTA protease inhibitor tablet
Buffer A: 200mM NaCl, 20mM Tris pH=8, 5% Glycerol, 0.5mM TCEP.
Buffer B: Buffer A + 500mM Imidazole. 1M imidazole for 10xHisTags, BRAF or TEV purifs.
Buffer IEC A:, 20mM Tris (pH=8 Q, pH=7 for SP columns), 5% glycerol, 1mM TCEP
Buffer IEC B: Buffer IEC A + 1M NaCl.
SEC buffer: 150mM NaCl, 20mM Hepes pH=7.5, 1mM TCEP. For biochemistry, +5% glycerol
