## Mutational escape from three affinity-matured IGHV3-53 neutralizing antibodies.

These experiments are described in **this pre-print**, and the antibodies were first described in [Sheward et al.](https://www.biorxiv.org/content/10.1101/2022.01.03.474825v1).

For the details of the experimental and analytical approach, see our paper: [Greaney et al.](https://www.sciencedirect.com/science/article/pii/S1931312820306247?via%3Dihub).

### What data are shown here?
We are showing mutations to the SARS-CoV-2 RBD that escape binding by each of three monoclonal antibodies, CAB-A17, CAB-A49, and CAB-C19. Raw data are available [here](https://github.com/jbloomlab/SARS-CoV-2-RBD_MAP_Karolinska/blob/main/results/supp_data/karolinska_raw_data.csv).

When you click on sites, they will be highlighted on the protein structure of the ACE2-bound RBD ([PDB 6M0J](https://www.rcsb.org/structure/6M0J)).

At the site level you can visualize one of two quantities:

 - *total escape* is the sum of the escape from all mutations at a site.

 - *max escape* is the magnitude of the largest-effect escape mutation at each site.

At the mutation level, the height of each letter is proportional to the extent to which that amino-acid mutation escapes antibody binding.
You can color the logo plot letters in four ways:

 - *escape color ACE2 bind* means color letters according to how that mutation affects ACE2 binding as measured in our prior deep mutational scanning ([Starr et al. (2020)](https://doi.org/10.1016/j.cell.2020.08.012), with yellow meaning highly deleterious, and brown meaning neutral or beneficial for ACE2 binding.

 - *escape color RBD expr* means color letters according to how that mutation affects RBD expression as measured in [Starr et al. (2020)](https://doi.org/10.1016/j.cell.2020.08.012).

 - *escape color gray* means color all letters gray.

 - *escape color func group* means color letters by functional group.
