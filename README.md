# Single_cell_roadmap
![alt text](https://github.com/mkorshe/single_cell__transcritpomics_roadmap/blob/main/SC_ROADMAP.png)

In this roadmap it is described the path from a beginner in bioinformatics/biology to single-cell expert.

PDF, PNG and XML are presented in this repository

Here is a link to draw.io:
https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1#G1Pt7qlrlkqKgcTHseUnjHDvku7OcioKLA

## Level 1
To start with you have to understand basic biological principles, know how cell works, which tissues are composed of which cells and what fundctions do they have. Basic course of school biology and some auxiliary maerials will be enought to have a general overview. 
After that you can better understand the importance of research in single-cell resolution. 

Also, you have to understand how sequencing works and what are differences between main sequencing platforms. 

### Usefull articles:

Andrews, Tallulah S., et al. “Tutorial: Guidelines for the Computational Analysis of Single-Cell RNA Sequencing Data.” Nature Protocols, Dec. 2020, doi:10.1038/s41596-020-00409-w.  https://www.nature.com/articles/s41596-020-00409-w

Stuart, T. and Satija, R. (2019). Integrative single-cell analysis. Nature Reviews Genetics, [online] 20(5), pp.257–272. Available at: https://www.nature.com/articles/s41576-019-0093-7 

Luecken, M.D. and Theis, F.J. (2019). Current best practices in single‐cell RNA‐seq analysis: a tutorial. Molecular Systems Biology, 15(6). https://www.embopress.org/doi/full/10.15252/msb.20188746

Chen, G., Ning, B. and Shi, T. (2019). Single-Cell RNA-Seq Technologies and Related Computational Data Analysis. Frontiers in Genetics, 10. Available at: https://www.frontiersin.org/articles/10.3389/fgene.2019.00317/full

Tang, X., Huang, Y., Lei, J., Luo, H. and Zhu, X. (2019). The single-cell sequencing: new developments and medical applications. Cell & Bioscience, 9(1). Available at: https://cellandbioscience.biomedcentral.com/articles/10.1186/s13578-019-0314-y 

Dal Molin, Alessandra, and Barbara Di Camillo. “How to Design a Single-Cell RNA-Sequencing Experiment: Pitfalls, Challenges and Perspectives.” Briefings in Bioinformatics, vol. 20, no. 4, Jan. 2018, pp. 1384–94, doi:10.1093/bib/bby007.

### Slides: 
https://rna-seqblog.com/an-introduction-to-single-cell-rna-sequencing-and-clinical-applications/

### Short tutorials:
“Vignettes.” Satijalab.org, 2019, https://satijalab.org/seurat/vignettes.html.

Theislab. “Theislab/Single-Cell-Tutorial.” GitHub, 6 Oct. 2020, https://github.com/theislab/single-cell-tutorial.


## Level 2

After receiving general overview you have to deeper your knowledge and understand main differences in single-cell sequencing protocols, pipelines of data processing and other tools.

### Tutorials: 

A beautiful and very explanatory tutorial of single-cell analysis:
  Bioconductor.org. (2020). Orchestrating Single-Cell Analysis with Bioconductor. [online] Available at: http://bioconductor.org/books/release/OSCA/ 

  Westoby, J. (2019). Analysis of single cell RNA-seq data. [online] Sanger.ac.uk. Available at: https://scrnaseq-course.cog.sanger.ac.uk/website/index.html

  McCarthy, Davis J. “Analysis of Single Cell RNA-Seq Data.” Svi.Edu.Au, 3 Oct. 2019, http://biocellgen-public.svi.edu.au/mig_2019_scrnaseq-workshop/public/index.html.

#### Raw data & pipelines

Ashton, John M., et al. Comparative Analysis of Single-Cell RNA Sequencing Platforms and Methods. July 2020, doi:10.1101/2020.07.20.212100. https://www.biorxiv.org/content/10.1101/2020.07.20.212100v1

Gao, Mingxuan, et al. Comparison of High-Throughput Single-Cell RNA Sequencing Data Processing Pipelines. Feb. 2020, doi:10.1101/2020.02.09.940221. https://www.biorxiv.org/content/10.1101/2020.02.09.940221v1

Vieth, Beate, et al. “A Systematic Evaluation of Single Cell RNA-Seq Analysis Pipelines.” Nature Communications, vol. 10, no. 1, Oct. 2019, doi:10.1038/s41467-019-12266-7. https://www.nature.com/articles/s41467-019-12266-7

#### Clustering

Feng, Chao, et al. “Dimension Reduction and Clustering Models for Single-Cell RNA Sequencing Data: A Comparative Study.” International Journal of Molecular Sciences, vol. 21, no. 6, Mar. 2020, p. 2181, doi:10.3390/ijms21062181. https://www.mdpi.com/1422-0067/21/6/2181

Peng, Lihong, et al. “Single-Cell RNA-Seq Clustering: Datasets, Models, and Algorithms.” RNA Biology, vol. 17, no. 6, Mar. 2020, pp. 765–83, doi:10.1080/15476286.2020.1728961. https://www.tandfonline.com/doi/abs/10.1080/15476286.2020.1728961?journalCode=krnb20

Petegrosso, Raphael, et al. “Machine Learning and Statistical Methods for Clustering Single-Cell RNA-Sequencing Data.” Briefings in Bioinformatics, vol. 21, no. 4, June 2019, pp. 1209–23, doi:10.1093/bib/bbz063. https://academic.oup.com/bib/article-abstract/21/4/1209/5519426

#### Imputation

Zhang, Lihua, and Shihua Zhang. “Comparison of Computational Methods for Imputing Single-Cell RNA-Sequencing Data.” IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2019, pp. 1–1, doi:10.1109/tcbb.2018.2848633. https://pubmed.ncbi.nlm.nih.gov/29994128/

#### Batch effect correction

Chen, Wenan, et al. “A Comparison of Methods Accounting for Batch Effects in Differential Expression Analysis of UMI Count Based Single Cell RNA Sequencing.” Computational and Structural Biotechnology Journal, vol. 18, 2020, pp. 861–73, doi:10.1016/j.csbj.2020.03.026. https://www.sciencedirect.com/science/article/pii/S200103701930409X

#### Dropout correction

Qiu, Peng. “Embracing the Dropouts in Single-Cell RNA-Seq Analysis.” Nature Communications, vol. 11, no. 1, Mar. 2020, doi:10.1038/s41467-020-14976-9. https://www.nature.com/articles/s41467-020-14976-9

Lan, Tian, et al. “Sequencing Dropout-and-Batch Effect Normalization for Single-Cell MRNA Profiles: A Survey and Comparative Analysis.” Briefings in Bioinformatics, Oct. 2020, doi:10.1093/bib/bbaa248. https://academic.oup.com/bib/advance-article-abstract/doi/10.1093/bib/bbaa248/5929825

#### Enrichment

Ma, Ying, et al. “Integrative Differential Expression and Gene Set Enrichment Analysis Using Summary Statistics for ScRNA-Seq Studies.” Nature Communications, vol. 11, no. 1, Mar. 2020, doi:10.1038/s41467-020-15298-6. https://www.nature.com/articles/s41467-020-15298-6

#### Pseudotime

Saelens, Wouter, et al. “A Comparison of Single-Cell Trajectory Inference Methods.” Nature Biotechnology, vol. 37, no. 5, Apr. 2019, pp. 547–54, doi:10.1038/s41587-019-0071-9. https://www.nature.com/articles/s41587-019-0071-9

https://github.com/agitter/single-cell-pseudotime

https://broadinstitute.github.io/2019_scWorkshop/pseudotime-cell-trajectories.html

#### Cell cycle

Hsiao, Chiaowen Joyce, et al. “Characterizing and Inferring Quantitative Cell Cycle Phase in Single-Cell RNA-Seq Data Analysis.” Genome Research, vol. 30, no. 4, Apr. 2020, pp. 611–21, doi:10.1101/gr.247759.118. https://genome.cshlp.org/content/early/2020/04/20/gr.247759.118.abstract

https://satijalab.org/seurat/v3.2/cell_cycle_vignette.html

#### Gene regulatory networks 

Chen, Shuonan, and Jessica C. Mar. “Evaluating Methods of Inferring Gene Regulatory Networks Highlights Their Lack of Performance for Single Cell Gene Expression Data.” BMC Bioinformatics, vol. 19, no. 1, June 2018, doi:10.1186/s12859-018-2217-z. https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2217-z

Iacono, Giovanni, et al. “Single-Cell Transcriptomics Unveils Gene Regulatory Network Plasticity.” Genome Biology, vol. 20, no. 1, June 2019, doi:10.1186/s13059-019-1713-4. https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1713-4

Nguyen, Hung, et al. “A Comprehensive Survey of Regulatory Network Inference Methods Using Single Cell RNA Sequencing Data.” Briefings in Bioinformatics, Sept. 2020, doi:10.1093/bib/bbaa190. https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbaa190/5904505

#### Dataset integration

Luecken, MD, et al. Benchmarking Atlas-Level Data Integration in Single-Cell Genomics. May 2020, doi:10.1101/2020.05.22.111161. https://www.biorxiv.org/content/10.1101/2020.05.22.111161v2


#### Visualization

Cakir, Batuhan, et al. “Comparison of Visualization Tools for Single-Cell RNAseq Data.” NAR Genomics and Bioinformatics, vol. 2, no. 3, July 2020, doi:10.1093/nargab/lqaa052. https://academic.oup.com/nargab/article/2/3/lqaa052/5877814

#### Cell-cell communication

Shao, Xin, et al. “New Avenues for Systematically Inferring Cell-Cell Communication: Through Single-Cell Transcriptomics Data.” Protein & Cell, May 2020, doi:10.1007/s13238-020-00727-5. https://link.springer.com/article/10.1007/s13238-020-00727-5

Armingol, Erick, et al. “Deciphering Cell–Cell Interactions and Communication from Gene Expression.” Nature Reviews Genetics, Nov. 2020, doi:10.1038/s41576-020-00292-x.  https://www.nature.com/articles/s41576-020-00292-x


#### Protein imputation
Example:
Zhou, Zilu, et al. “Surface Protein Imputation from Single Cell Transcriptomes by Deep Neural Networks.” Nature Communications, vol. 11, no. 1, Jan. 2020, doi:10.1038/s41467-020-14391-0. https://www.nature.com/articles/s41467-020-14391-0

#### Automatic cell identification

22 classification methods benchmarking
https://github.com/tabdelaal/scRNAseq_Benchmark
Paper:
Abdelaal, Tamim, et al. “A Comparison of Automatic Cell Identification Methods for Single-Cell RNA Sequencing Data.” Genome Biology, vol. 20, no. 1, Sept. 2019, doi:10.1186/s13059-019-1795-z. https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1795-z

### Other very useful links 

https://www.scrna-tools.org/tools
The scRNA-tools database records details of software tools designed for analysing scRNA-seq data. Each tool is categorised according to the analysis tasks it can be used for.

https://bioinformaticshome.com/tools/rna-seq/scRNA-seq.html
230 Free Single-cell RNA-seq (scRNA-seq) Tools - Software and Resources

