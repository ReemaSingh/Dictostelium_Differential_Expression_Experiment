# Differential Expression of Dictyostelium discoideum RNAseq data
Identify Differential Expressed Genes in DgcA null mutant and Knock-out samples in Dictyostelium Discoideum. The same workflow has been used for the differential expression analysis of Polysphondylium pallidum.

## Quality Control

  R CMD BATCH QualityControl.R &

## Alignmnet using Tophat

  ./try.sh
  ./try1.sh
  ./try2.sh
  
## Alignmnet Visualization

   R CMD BATCH InputIGV-HtseqCount.R

## Read Count

  R CMD BATCH htseq-count.R

## Differential Gene Expression

  R CMD BATCH DiffExpTwoGroup.R
  
## Gene-Set Enrichment Analysis

# Publication

Chen ZH, Singh R, Cole C, Lawal HM, Schilde C, Febrer M, Barton GJ, Schaap P. Adenylate cyclase A acting on PKA mediates induction of stalk formation by cyclic diguanylate at the Dictyostelium organizer. Proceedings of the National Academy of Sciences. 2017 Jan 17;114(3):516-21.
