# Haiti_Aeae_IR

This repository contains data and code associated with a study of insecticide resistance (IR) of *Aedes aegypti* in Haiti. The study aims to describe to what extent IR-associated alleles are present, how much they have increased and where they are located in our study site.

## Repository Contents

- **Datasets**  
  The single .csv file (Haiti_IR.csv) contains the data on IR, location and pertinent metadata relating to each sample.
  The folder denoted "Haiti Shapefile" contains the required .shp components for Haiti's 2nd level administrative boundaries, used for mapping in this analysis.

- **Modeling and Figure Code (.Rmd file)**  
  The `.Rmd` file contains all code used to:
  - Fit statistical tests including models
  - Map the study area
  - Provide descriptive statistics

## Data Description

In the Haiti_IR.csv file:
- `NECE Sample ID`: Sample ID used for internal reference 
- `GPS N` / `GPS W` / `Coordinates` : Coordinates of the trap site  
- `Collection Date`: The Date the trap was set 
- `Manifest Collection Location`: The name affiliated with each coordinate pair
- `XXX qPCR`: The result of each PCR assay
- `XXX NGS`: The result of each NGS assay
- `Picture`: Whether or not a picture was obtained of the assay

In the Shapefiles folder:
- `hti_admbnda_adm1_cnigs_20181129`: Shapefile of Haiti
- `hti_admbnda_adm2_cnigs_20181129`: Shapefile of Haiti with administrative level 2 boundaries
- `hti_admbnda_adm3_cnigs_20181129`: Shapefile of Haiti with administrative level 3 boundaries
- `Key`: Text document describing the attributes of the Haiti shapefiles

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/[YourUsername]/Haiti_Aeae_IR.git
   ```
2. Open the `.Rmd` file in RStudio.
3. Install any required R packages (listed at the top of the `.Rmd` file).
4. Knit the document to reproduce outputs and figures.

## Citation
If you use this code or data in your research, please cite the associated manuscript:
> [Manuscript Citation Placeholder – update with DOI or full citation when available]

## Funding and Disclaimer
This work was funded by the Armed Forces Health Surveillance Branch (AFHSB), Global Emerging Infections Surveillance (GEIS) Section, under ProMIS ID (P0154_24_EC and P0118-24-RD). These funders had no role in study design, data collection and analysis, decision to publish, or preparation of the manuscript. This work was also funded in part through Battelle Memorial Institute’s contract with the Information Analysis Center Multiple Award Contract (IAC MAC) No. FA807518D0005-FA807523F0016: Ongoing Force Health Protection (FHP) Analysis, Assessment, and Evaluation for Navy and Marine Corps Force Health Protection Command (NMCFHPC). This material is based upon work supported by the DoD Information Analysis Center Program Management Oﬃce (DoD IAC PMO) and the Navy and Marine Corps Force Health Protection Command (NMCFHPC) under Contract No. FA807518D0005-FA807523F0016. Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the US Navy and Marine Corps Force Health Protection Command (NMCFHPC), the 774 Enterprise Sourcing Squadron (774 ESS), the Air Force Installation Contracting Center (AFICC), the DoD Information Analysis Center Program Management Oﬃce (DoD IAC PMO), or of the institutions and companies aﬃliated with the authors. 

The use of either trade or manufacturers’ names in this repository does not constitute an official endorsement of any commercial products. This repository may not be cited for purposes of advertisement. The opinions, interpretations, conclusions, recommendations and views in this repository are those of the authors and do not necessarily reflect the official policy or position of the Uniformed Services University of the Health Sciences, Department of the Army, Department of the Navy, Department of Defense, nor the U. S. Government. Multiple authors are military service members of the U.S. Government. This work was prepared as part of their official duties. Title 17, U.S.C., §105 provides that copyright protection under this title is not available for any work of the U.S. Government. Title 17, U.S.C., §101 defines a U.S. Government work as a work prepared by a military Service member or employee of the U.S. Government as part of that person’s official duties.

## Contact
For questions or collaborations, please contact:  
**Ian Pshea-Smith**  
University of Florida  
Email: [ianpsheasmith@ufl.edu] OR [ismithgh@umich.edu]
