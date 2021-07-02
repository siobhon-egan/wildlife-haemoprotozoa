# Wildlife Haemoprotozoa

A [workflowr](https://github.com/jdblischak/workflowr) project for Siobhon Egan's PhD project on the characterisation of haemoprotozoa from wildlife samples.

Project website available here http://siobhonlegan.com/wildlife-haemoprotozoa/

Haemoprotozoa of wildlife samples

In the spirit of reproducibility this project website is created that outlines analysis done for the following publication:

PhD Thesis 2021 (Chapter five)

Raw Illumina MiSeq data is available at European nucleotide archive the project accession number PRJEB46031 (ERP130215), which includes the following sample accession numbers:

- 18S kinetoplastid blood samples: ERS6633767--ERS6633815, ERS6633872--ERS6633981 (BioSample # SAMEA8950999--SAMEA8951047, SAMEA8951104--SAMEA8951213)
- 18S kinetoplastid tissue samples: ERS6633816--ERS6633871, ERS6633982--ERS6634081 (BioSample # SAMEA8951048--SAMEA8951103, SAMEA8951214--SAMEA8951313)
- 18S kinetoplastid tick samples: ERS6634083--ERS6634241 (BioSample # SAMEA8951315--SAMEA8951473)

Nucleotide sequence data available on Genbank

- Trypanosome (Illumina MiSeq zOTUs): MW676261--MW676287
- Piroplasm and *Hepatozoon* (Sanger sequencing): MW664957--MW664997


## Supporting data

Data used but not directly produced for this manuscript.

Nucleotide data for identification of ticks: MW665133--MW665150


## Directory information


# Worlflowr commands 

To build/view webiste locally
`wflow_build()` and `wflow_view()`

Status of workflow
`wflow_status()`

Publish website pages
`wflow_publish(c("analysis/index.Rmd", "analysis/first-analysis.Rmd"), "Add my first analysis")`

Push website to github
`wflow_git_push()`
