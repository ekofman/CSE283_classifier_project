# CSE283_classifier_project
### Project for CSE283


*GSE131512_cancerTPM.txt  
*GSE131512_metaData.xlsx  
*GSE131512_normalTPM.txt  
were obtained from https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131512  

This data consists of longitudinal SILVER-seq profiling of exRNA from a cohort of breast cancer patients (96) and controls (32). The normal data (GSE131512_normalTPM.txt) is from self-reported non-breast-cancer donors and the cancer data (GSE131512_cancerTPM.txt) is from breast-cancer patients that underwent chemotherapy and were subsequently followed for five years. Of the cancer patients, over the course of the study, 28 developped recurring cancer and 68 remained cancer-free. 

*patient_info.csv  
*preselectedList  
*readcounts_96_nodup.tsv  
were obtained from https://github.com/Zhong-Lab-UCSD/course_project_2020  

*readcounts_96_nodup.tsv consists of read counts for the 96 breast cancer samples, data for the samples are organized in columns (C1 to C96)  
*patient_info.csv consists of metadata for all samples, the column recurStatus contains recurrence status of the corresponding donor, "R" for recurrence and "N" for non-recurrence.  
*preselectedList consists of the 750 pre-selected breast cancer biomarker genes in Ensembl gene ID

*CTD_cancer_genes was obtained from the Comparative Toxicogenomics Database at http://ctdbase.org/basicQuery.go?bqCat=gene&bq=cancer after which the gene symbols were processed in Biomart to convert to Ensembl stable gene IDs. 
*Cancer_census_genes was obtained from the COSMIC Cancer Gene Census at https://cancer.sanger.ac.uk/cosmic/census?tier=all after which the gene symbols were processed in Biomart to convert to Ensembl stable gene IDs. 
*GSEA_KRAS_BREAST_UP_V1_UP was obtained from MSigDB at https://www.gsea-msigdb.org/gsea/msigdb/geneset_page.jsp?geneSetName=KRAS.BREAST_UP.V1_UP&keywords=KRAS.BREAST_UP.V1_UP after which the gene symbols were processed in Biomart to convert to Ensembl stable gene IDs. 
*GSEA_VANTVEER_BREAST_CANCER_POOR_PROGNOSIS was obtained from MSigDB at https://www.gsea-msigdb.org/gsea/msigdb/cards/VANTVEER_BREAST_CANCER_POOR_PROGNOSIS after which the gene symbols were processed in Biomart to convert to Ensembl stable gene IDs. 




