## Imputation

## QC for Imputed datasets


## Association study by plink
#PCA of QCed Genotype

#Association
`/home/unix/qfeng/huang_lab/00_Software/plink2 --bfile imputed_dataset --covar pcafile --covar-col-nums pc1-5colms --glm --out outname`

## Meta analysis by METAL 
 Inverse variance weighting shows a better performance than the sample size weighted approach; For sample size weighted approach, if one cohort has an extremely imbalanced case:control ratio, you'll have to use the effective sample size: 4/(1/case + 1/control)

`/home/unix/qfeng/huang_lab/00_Software/metal/metal metal.para.txt`






