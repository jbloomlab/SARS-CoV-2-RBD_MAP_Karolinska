# Input data

This directory contains input data used for the analysis and configuration for some of the analyses:

 - [barcode_runs.csv](barcode_runs.csv): Illumina sequencing runs for barcode counting.
   The *sample* column should be the hyphen separated concatenation of *experiment*, *antibody*, *concentration*, and *selection*.
   The **combination** of the *library* and *sample* columns should be unique.
   The *frac_escape* column gives the overall fraction of the library that escaped antibody.
   The *R1* FASTQ files should be semicolon (`; `) separated list of glob patterns.

 - [wildtype_sequence.fasta](wildtype_sequence.fasta): wildtype sequence of mutagenized gene.

 - [./pdbs/](pdbs): files downloaded from the [Protein Data Bank](https://www.rcsb.org/) for structural analyses.

 - [escape_profiles_config.yaml](escape_profiles_config.yaml): Information on how to plot the escape profiles; manually edit this to alter their plotting.

 - [output_pdbs_config.yaml](output_pdbs_config.yaml): Information on how to output structural mappings of escape.

 - [structural_annotation_config.yaml](structural_annotation_config.yaml): Information on how to output structural annotations of contact residues in various RBD:ligand complexes.

 - [site_color_schemes.csv](site_color_schemes.csv): Schemes for how to color sites (can be used in escape profiles).

 -  [spikeprot0315.tar.tar.xz](spikeprot0315.tar.tar.xz): A compressed FASTA file with all spike sequences in GISAID. Downloaded on March-15-2021 as follows: logged into GISAID, went to the *EpiCoV* page, clicked on *Downloads*, clicked on *spikeprot0315*, which yielded the file `spikeprot0315.tar.tar.xz` which was then copied here.

 - [./RBD_sites.csv](RBD_sites.csv): Useful numeric and functional annotations of RBD sites for referencing in various analyses.

 - [./RBDs_aligned.fasta](RBDs_aligned.fasta): alignment of sarbecovirus RBDs.
