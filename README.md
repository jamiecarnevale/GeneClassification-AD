# Alzheimer’s Disease RNASeq Research Recommendations


## Classic View - Amyloid Beta Plaques 

## Glucose Metabolism Problems

## Blood-Brain Barrier Dysfunction 

## RNA-Seq Overview
How RNA-Seq Works: 
extracting RNA
make cDNA (complementary DNA) from it
cDNA is sequenced to recreate RNA (this time with labels)
ran through machine to translate labels into sequence data
RNA-Seq in Alzheimer's Research: RNA-Seq allows us to monitor changes in RNA expression in the brain and identify novel targets for treatments
can apply machine learning to this data

## Data Sources:
ROSMAP (Religious Orders Study and Memory and Aging Project)
MSBB (Mount Sinai Brain Bank)
MAYO Clinic Study
Key Metric:
Residual Counts: 
Normalized gene expression data
- reduces technical variation and make samples more comparable
- high values = high RNA expression
- low values = low RNA expression

## Best Model: Logistic Regression
Accuracy: 87%		
ROC_AUC: 93%

## Logistic Regression Weights

## Key Genes:

### TIMM44:
Description: TIMM44 is involved in mitochondrial protein import machinery, having a role in energy production and glucose metabolism within cells.

### MT-CO2:
Description: MT-CO2 codes for an integral component of the mitochondrial respiratory chain, a crucial system for energy production in the cell. It significantly influences cellular glucose metabolism.

## Next Steps
- Analyze and model on Whole Genome Sequencing for TIMM44 and MT-CO2
- look for variants between Alzheimer’s and Control
- Perform biological research Techniques on TIMM44 and MT-CO2
-- e.g. immunohistochemistry
- Gather more data, model on that and see if model coefficients change or if we can get a higher accuracy

## Data Acknowledgement

The results published here are in whole or in part based on data obtained from the AD Knowledge Portal (https://adknowledgeportal.org). Data generation was supported by the following NIH grants: P30AG10161, P30AG72975, R01AG15819, R01AG17917, R01AG036836, U01AG46152, U01AG61356, U01AG046139, P50 AG016574, R01 AG032990, U01AG046139, R01AG018023, U01AG006576, U01AG006786, R01AG025711, R01AG017216, R01AG003949, R01NS080820, U24NS072026, P30AG19610, U01AG046170, RF1AG057440, and U24AG061340, and the Cure PSP, Mayo and Michael J Fox foundations, Arizona Department of Health Services and the Arizona Biomedical Research Commission. We thank the participants of the Religious Order Study and Memory and Aging projects for the generous donation, the Sun Health Research Institute Brain and Body Donation Program, the Mayo Clinic Brain Bank, and the Mount Sinai/JJ Peters VA Medical Center NIH Brain and Tissue Repository. Data and analysis contributing investigators include Nilüfer Ertekin-Taner, Steven Younkin (Mayo Clinic, Jacksonville, FL), Todd Golde (University of Florida), Nathan Price (Institute for Systems Biology), David Bennett, Christopher Gaiteri (Rush University), Philip De Jager (Columbia University), Bin Zhang, Eric Schadt, Michelle Ehrlich, Vahram Haroutunian, Sam Gandy (Icahn School of Medicine at Mount Sinai), Koichi Iijima (National Center for Geriatrics and Gerontology, Japan), Scott Noggle (New York Stem Cell Foundation), Lara Mangravite (Sage Bionetworks).

Cite:

https://doi.org/10.1038/sdata.2016.89
https://doi.org/10.1038/sdata.2018.185
https://doi.org/10.1038/sdata.2018.142







