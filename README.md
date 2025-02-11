# CASTLE: Cancer Standards Long-read Evaluation

CASTLE panel is a multi-technology whole-genome sequencing of six commercially available tumor/normal cell line pairs (HCC1954, HCC1937, H1437, H2009, Hs578T and HCC1395). Genomic sequencing currently includes PacBio, Oxord Nanopore, Illumina and PoreC, in most cases sequenced from the same DNA extraction or cell line passage. The panel is designed for benchmarking and developing short- and long-read tools for analysis of cancer genomes.

We also generated a set of confident somatic structural variation (SV) and single nucleotide variation(SNV) calls for each tumor cell line. 

## Sequencing data information and access
For sequencing details, plase see [DeepSomatic preprint](https://www.biorxiv.org/content/10.1101/2024.08.16.608331v1.full).  

Raw sequencing data is available through NCBI SRA BioProject [PRJNA1086849](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1086849) and
[Google Cloud mirror](https://console.cloud.google.com/storage/browser/brain-genomics-public/publications/park2024_deepsomatic). 

### CASTLE panel data inital release

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|HCC1954|Breast Ductal Carcinoma|ONT R10|253|28|[SRR28305164](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305164)|
|HCC1954||HiFi|195|17|[SRR28305163](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305163)|
|HCC1954||Illumina|232|-|[SRR28305162](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305162)|
|HCC1954BL|Blood|ONT R10|104|28|[SRR28305161](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305161)|
|HCC1954BL||HiFi|193|17|[SRR28305160](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305160)|
|HCC1954BL||Illumina|436|-|[SRR28305159](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305159)|

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|HCC1937|Breast Invasive Ductal Carcinoma|ONT R10|355|37|[SRR28305186](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305186)|
|HCC1937||ONT UL E821|572|48|[SRR31537484](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305184)|
|HCC1937||HiFi|184|15|[SRR28305185](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305185)|
|HCC1937||Illumina|740|-|[SRR28305184](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305184)|
|HCC1937BL|Blood|ONT R10|79|41|[SRR28305183](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305183)|
|HCC1937BL||ONT UL E821|172|45|[SRR31537483](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537483)|
|HCC1937BL||HiFi|172|16|[SRR28305182](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305182)|
|HCC1937BL||Illumina|218|-|[SRR28305181](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305181)|

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|H1437|Lung (NSCLC)|ONT R10|242|38|[SRR28305180](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305180)|
|H1437||ONT UL E821|550|48|[SRR31537476](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537476)|
|H1437||HiFi|198|17|[SRR28305179](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305179)|
|H1437||Illumina|595|-|[SRR28305178](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305178)|
|BL1437|Blood|ONT R10|151|42|[SRR28305177](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305177)|
|BL1437||ONT UL E821|203|39|[SRR31537475](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537475)|
|BL1437||HiFi|218|18|[SRR28305175](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305175)|
|BL1437||Illumina|203|-|[SRR28305174](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305174)|

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|H2009|Lung (NSCLC)|ONT R10|329|27|[SRR28305173](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305173)|
|H2009||ONT UL E821|516|65|[SRR31537473](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537473)|
|H2009||HiFi|201|16|[SRR28305172](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305172)|
|H2009||Illumina|669|-|[SRR28305171](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305171)|
|BL2009|Blood|ONT R10|92|37|[SRR28305170](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305170)|
|BL2009||HiFi|209|16|[SRR28305169](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305169)|
|BL2009||Illumina|171|-|[SRR28305168](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305168)|

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|Hs578T|Lung (NSCLC)|ONT R10|261|36|[SRR31537470](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537470)|
|Hs578T||HiFi|172|18|[SRR31537482](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537482)|
|Hs578T||Illumina|616|-|[SRR31537481](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537481)|
|Hs578Bst|Blood|ONT R10|113|40|[SRR31537480](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537480)|
|Hs578Bst||HiFi|84|12|[SRR31537479](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537479)|
|Hs578Bst||Illumina|102|-|[SRR31537478](https://www.ncbi.nlm.nih.gov/sra/?term=SRR31537478)|

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|--------------|-------------|
|HCC1395|Breast Invasive Ductal Carcinoma|ONT R10|246|10|[SRR28305167](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305167)|
|HCC1395BL|Blood|ONT R10|90|11|[SRR28305166](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305166)|

### Additional ultra-long Nanopore and Pore-C data

XXX

### Additional COLO829 data:

COLO829 is a popular benchmarking dataset for cancer somatic SV evaluation. We generated additional
ONT R9 data to support the evaluation.

|Sample|Tissue/Cancer|Technology|Read length (Gb)|Coverage depth*|Reads N50 (kb)|SRA accession|
|------|-------------|----------|----------------|---------------|--------------|-------------|
|COLO829|Melanoma|ONT R9|361|112|40|[SRR28305188](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305188)|
|COLO829||Illumina|162|50|-|[SRR28305187](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305187)|
|COLO829BL|Blood|ONT R9|419|130|38|[SRR28305176](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305176)|
|COLO829BL||Illumina|395|123|-|[SRR28305165](https://www.ncbi.nlm.nih.gov/sra/?term=SRR28305165)|

## Ethics statement

For the cell line sequencing, the Institutional Review Board of National Institutes of Health considers patient-derived cell lines as non-human subjects, 
thus approval was required. We note that because commercially available cell lines were derived prior to establishing the research use consent mechanism, 
no such consent was received. The cell lines used in this study are anonymized, therefore the risks of identifying original donors or their immediate family members are considered low. 
There are substantial benefits of openly releasing the cell line data for other research developing new methods for detecting somatic variants, 
which is crucial for precision cancer therapies. Given that existing data for these cell lines is already publicly available via NCBI SRA,
we concluded that the benefits of releasing additional long-read data outweigh the marginal risks. 
This decision follows the practices previously established by the NCI and NHGRI in the TCGA tumor cell line data release (https://www.cancer.gov/ccg/research /genome-sequencing/tcga/history/ethics-policies).

## Credits

The sequencing data was generated and analyzed in a joint initiaive by the following institutions/groups:

* National Cancer Institute (Kolmogorov lab)
* UC Santa Cruz (Paten and Miga labs)
* Children's Mercy Hospital (Farooqi lab)
* Google Health (DeepVariant group)
* Oxford Nanopore Technologies (Applications team)
* New York Genome Center (Robine and Narzisi labs)

## How to cite

* The most relevant citation for data generation and small variation analysis is the [DeepSomatic]( https://www.biorxiv.org/content/10.1101/2024.08.16.608331v1.full) preprint.

* To refer to structural variation analysis, please cite [Severus]( https://www.medrxiv.org/content/10.1101/2024.03.22.24304756v1) preprint.

## Somatic Variation Analysis
### Structural Variation Calls
Since no ground truth SV calls are available, we created an ensemble of confident calls generated by merging the results from different methods and sequencing technologies using [Minda]( https://github.com/KolmogorovLab/minda). We used [Severus]( https://github.com/KolmogorovLab/Severus), [nanomonsv]( https://github.com/friend1ws/nanomonsv), [SAVANA]( https://github.com/cortes-ciriano-lab/savana), [Sniffles2]( https://github.com/fritzsedlazeck/Sniffles), [SvABA]( https://github.com/walaj/svaba), [GRIDSS]( https://github.com/PapenfussLab/gridss), and [Manta]( https://github.com/Illumina/manta) to generate ensembles. Confident calls were defined if supported by at least two (out of three) technologies and at least 4 (out of 11) callers. This assumes that singleton calls are false-positives and that calls supported by multiple tools are more reliable. Severus consistently had the highest recall and precision against the ensemble SV sets. For more details on the method and statistics, please see [Severus preprint]( https://www.medrxiv.org/content/10.1101/2024.03.22.24304756v1). 

<p align="center">
  <img src="docs/sv_bench.png" alt="benchmarking" style="width:90%"/>
</p>

Individual vcfs and scripts for each caller are available at [here](https://doi.org/10.5281/zenodo.10856827).
For data preprocessing steps, please [see](https://github.com/KolmogorovLab/Severus/blob/main/README.md#preparing-phased-and-haplotagged-alignments)

This dataset is used to develop and evaluate the somatic structural variation (SV) caller [Severus]( https://github.com/KolmogorovLab/Severus).
### Single Nucleotide Variation Calls

XXX

## Contact
Please raise issues concerning this dataset in the Github repository.
