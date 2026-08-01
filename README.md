# BVIPS
Computational mapping of vascular inflammatory potential in bronchiectasis through airway microbiome endotyping.

Dataset (Not included in the repository)  - BioProjectID: PRJEB65368
• Shotgun metagenomic sequencing
• Non-CF bronchiectasis sputum microbiome

Workflow:

Data Preprocessing:
         ↓
         
Microbiome Characterization:
  - Relative abundance
  - CLR transformation
  - Alpha & Beta Diversity
         ↓ 
 
Inflammatory Feature Engineering
(Custom inflammatory scoring calculations and an annotation process was done. They are within the Jupyter notebook but are not provided as separate files)
  - Dysbiosis burden
  - LPS burden
  - Tissue injury burden
  - Pathogen burden
        ↓

Microbial Inflammatory Endotyping
  - Feature-based clustering
  - Inflammatory ecosystem states
        ↓

BVIPS (Bronchiectasis Vascular Inflammatory Potential Score) Calculation
        ↓
        
Visualization
