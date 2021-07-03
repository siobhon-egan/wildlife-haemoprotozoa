# Wildlife Haemoprotozoa

Project website available here http://siobhonlegan.com/wildlife-haemoprotozoa/

A [workflowr](https://github.com/jdblischak/workflowr) project created for data analysis related to the following publication: 

Egan, S., Taylor, C., Austen, J., Banks, P., Northover, A., Ahlstrom, L., Ryan, U., Irwin, P., and Oskam C. (*Under review*). Haemoprotozoa surveillance in peri-urban native and introduced wildlife.

## Data availability

Raw Illumina MiSeq data is available at European nucleotide archive under the project accession number PRJEB46031 (ERP130215), which includes the following sample accession numbers:

- 18S kinetoplastid blood samples: ERS6633767--ERS6633815, ERS6633872--ERS6633981 (BioSample # SAMEA8950999--SAMEA8951047, SAMEA8951104--SAMEA8951213)
- 18S kinetoplastid tissue samples: ERS6633816--ERS6633871, ERS6633982--ERS6634081 (BioSample # SAMEA8951048--SAMEA8951103, SAMEA8951214--SAMEA8951313)
- 18S kinetoplastid tick samples: ERS6634083--ERS6634241 (BioSample # SAMEA8951315--SAMEA8951473)

Nucleotide sequence data has been made available on Genbank, under the following accession numbers:

- Trypanosome (Illumina MiSeq zOTUs): MW676261--MW676287
- Piroplasm and *Hepatozoon* (Sanger sequencing): MW664957--MW664997


## Supporting data

Data produced after bioinformatic analysis of raw Illumina MiSeq data such as taxonomy table, zOTU count data and metadata is available within the **data/Rdata** in `.RData` format.

Data used but not directly produced for this manuscript - nucleotide data generated for the molecular identification of ticks has been uploaded to GenBank under accession numbers MW665133--MW665150


---

<!-- Worlflowr commands

# Worlflowr commands 

To build/view webiste locally
`wflow_build()` and `wflow_view()`

Status of workflow
`wflow_status()`

Publish website pages
`wflow_publish(c("analysis/index.Rmd", "analysis/first-analysis.Rmd"), "Add my first analysis")`

Push website to github
`wflow_git_push()`  -->
