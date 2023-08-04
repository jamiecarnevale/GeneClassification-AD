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








