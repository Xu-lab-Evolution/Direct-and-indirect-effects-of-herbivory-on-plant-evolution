# Real-time plant evolution reveals dynamic and contrasting roles of direct and indirect effects of herbivory on plant evolution

**Authors:** Sara Nouere, Martin Schäfer, Antonino Malacrinò, Martin Lohr, Christoph Vorburger, and Shuqing Xu

---

## Abstract
Predicting evolution in nature requires separating the forces acting directly on traits from those indirectly acting through ecological pathways. In a two-year outdoor mesocosm with Spirodela polyrhiza and its herbivore, we experimentally partitioned direct from indirect herbivory effects and tracked their evolutionary consequences. In the first year, herbivory reduced duckweed abundance but indirectly promoted growth by reducing algal competition and increasing phosphate availability, shifting plant traits and genotype frequencies. In the second year, a macroalgal bloom co-occurred with severe phosphate depletion, eliminating these effects and reversing the direction of selection on defence metabolites. Across years and metabolites, selection from direct effects was strong but fluctuate, whereas selection from indirect effects were weaker yet more consistent and frequently antagonistic with direct effects, buffering net evolutionary change. A macroalgal bloom with phosphate depletion erased earlier signals and reversed selection, identifying a community-level factor that constrains the predictability of evolution in natural ecosystems. 

---

## Disclaimer
This repository contains the main components used to process the raw data and to analyze it.  
Raw data is available at NCBI SRA under the BioProject numbers:   
- **PRJNA1196832** (pool-seq).  

---

## Pipeline
- TrimGalore (Krueger et al. 2021)  
- Bwa (Li et al. 2009)  
- Samtools (Danecek et al. 2021)  
- HAFpipe (Tilk et al. 2019)  
- Kraken2 (Wood et al. 2019)  
- R (R Core Team 2024)  

---

## Code Organization
1. **Duckweed coverage**  
   Data and code for reproducing Fig. 2A   

2. **Growth/Susceptibility assays**  
   Data and code for reproducing Fig. 2C, Fig. S1C

3. **Macroalgaea and Chlorophyll-a**  
   Data and code for reproducing Fig. 2D, Fig. S1D

4. **Metabolites mixpopulation**  
   Data and code for reproducing Fig. S2A, Fig. S2B

5. **Monitoring morphology**  
   Data and code for reproducing Fig. S1A, Fig. S1B  

6. **Nutrients and physichemical parameters**  
   Data and code for reproducing Fig. 2D, Fig. S4, Table S6

7. **Phenotypic selection**  
   Data and code for reproducing Fig. 5, Fig S6-11, and Table S7, table S8   

6. **Pool-seq**  
   Data and code for reproducing:
   -Fig. 3A-F snd Figure S3: Circular and time-series plots of genotype dynamics
   -Table S3: : genotype frequency model (mixed effects)
   -Table S4: PERMANOVA on microbial and algal community structure
   -Table S5: Shannon diversity (mixed model) 

7. **Transplant experiment**  
   Data and code for reproducing Fig. 4C, Fig S5   
 
