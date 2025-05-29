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

## License
This project is licensed under the [MIT License](LICENSE) — feel free to use, modify, and distribute with attribution.

## Contact
For questions or collaborations, please contact:  
**Ian Pshea-Smith**  
University of Florida  
Email: [ianpsheasmith@ufl.edu]
