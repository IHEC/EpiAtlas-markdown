A brief summary of the EpiATLAS project, for display alongside the data on the IHEC Data Portal.

Loosely inspired by the Roadmap page: [https://egg2.wustl.edu/roadmap/web_portal/](https://egg2.wustl.edu/roadmap/web_portal/), though intended to be more brief than comprehensive.

Could also be comparable to McGill EMC's methods page, though modified for EpiATLAS: [https://epigenomesportal.ca/edcc/doc/analysis_methods.html](https://epigenomesportal.ca/edcc/doc/analysis_methods.html).

### Additional Categories
* Description
* Figures
* Resources
* Articles

### File Descriptions
Data Portal tracks represent a browsable subset of the complete EpiATLAS reprocessing.
| Assay | Provenance | Source naming | Format |
| :--- | :--- | :--- | :--- |
| ChIP-Seq | Signal p-value | pval.signal | bigWig |
| ChIP-Seq Input | Raw control | ctl_raw | bigWig |
| RNA-Seq stranded | Unique plus / minus raw | Unique.minusRaw / Unique.plusRaw | bigWig |
| RNA-Seq unstranded | Unique raw | Unique.raw | bigWig |
| WGBS | CPG coverage & methylation | cpg_coverage & cpg_methylation | bigWig |
| UCLA ChIP-Imputed | P-value | pval | bigWig |
| ChromHMM | ChromHMM | ChromHMM | bigBed |

### Data Processing Pipelines
* ChIP-seq data was processed using the following container pipeline:
  * [https://github.com/IHEC/integrative_analysis_chip/releases](https://github.com/IHEC/integrative_analysis_chip/releases)
* WGBS data was processed using the following container pipeline:
  * [https://github.com/heathsc/gemBS/releases/tag/v3.5.0](https://github.com/heathsc/gemBS/releases/tag/v3.5.0)
* RNA-seq data was processed using the following container pipeline:
  * [https://github.com/IHEC/grape-nf/releases](https://github.com/IHEC/grape-nf/releases)

### Further Data Sources
* Complete reprocessed and post-processed data is available through [rsync/https/ftps](https://ihec.sd4h.ca/).
* Metadata is also in [EpiRR](https://www.ebi.ac.uk/epirr/)
* Raw, unprocessed data is available through [EGA](https://ega-archive.org/), [DDBJ](https://www.ddbj.nig.ac.jp), & [ENCODE](https://www.encodeproject.org)

### Additonal Resources
* [IHEC (consortium website)](https://ihec-epigenomes.org/)
* [BioRxiv channel](https://connect.biorxiv.org/relate/content/219)   
