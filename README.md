# Real-time plant evolution reveals dynamic and contrasting roles of direct and indirect effects of herbivory on plant evolution

**Authors:** Sara Nouere, Martin Schäfer, Antonino Malacrinò, Martin Lohr, Christoph Vorburger, and Shuqing Xu

---

## Abstract
The rapid pace of evolution observed in controlled laboratory settings often contrasts with slower evolutionary rates inferred from natural populations. This discrepancy may arise from highly dynamic selection pressures in nature. We tested this hypothesis in a two-year outdoor mesocosm experiment using Spirodela polyrhiza (giant duckweed) and its natural herbivore Lymnaea stagnalis (great pond snail). By manipulating snail presence and isolating direct versus indirect effects of herbivory, we tracked changes in plant demography, phenotype, genotype frequencies, and selection on specialized metabolites. In the first growing season, snail herbivory initially reduced duckweed abundance but increased growth likely via indirect pathways, such as reduced algal competition and enhanced phosphate availability. Pool-seq and metabolic profiling revealed significant shifts in plant phenotypes and genotype frequencies under herbivory. However, in the second growing season, a macro-algal bloom drastically reduced phosphate availability in the mesocosms. Concurrently, the previously observed differences in duckweed genotypes and phenotypes between herbivory and control treatments disappeared. Herbivory imposed strong but temporally variable selection on plant metabolites, with selection coefficients frequently reversing between two years. The shift in selection was largely driven by the high variability of direct herbivory effects, which frequently changed strength and reversed direction between years, while indirect effects, when significant, were more consistent. This suggests that while direct herbivory effects dominate short-term evolutionary responses, indirect effects might be important in shaping long-term evolutionary trajectories. Our findings highlight how ecological complexity, and nutrient dynamics modulate both the strength and direction of natural selection in multitrophic communities, emphasizing the critical need to integrate ecological complexity into studies of natural selection.

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
   Data and code for reproducing Fig. 1A   

2. **Growth/Susceptibility assays**  
   Data and code for reproducing Fig. 1C, Fig. 2C

3. **Macroalgaea and Chlorophyll-a**  
   Data and code for reproducing Fig. 1D, Fig. S2D

4. **Metabolites mixpopulation**  
   Data and code for reproducing Fig. S3A, Fig. S3B

5. **Monitoring morphology**  
   Data and code for reproducing Fig. S2A, Fig. S2B  

6. **Nutrients and physichemical parameters**  
   Data and code for reproducing Fig. 1D, Fig. S5, Table S6

7. **Phenotypic selection**  
   Data and code for reproducing Fig. 4, Fig S7-12, and Table S7    

6. **Pool-seq**  
   Data and code for reproducing:
   -Fig. 2A-F snd Figure S4: Circular and time-series plots of genotype dynamics
   -Table S3: : genotype frequency model (mixed effects)
   -Table S4: PERMANOVA on microbial and algal community structure
   -Table S5: Shannon diversity (mixed model) 

7. **Transplant experiment**  
   Data and code for reproducing Fig. 3C, Fig S6   
 
