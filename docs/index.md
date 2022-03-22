# Interactive structural visualizations of escape mutation maps

Below are links to interactive visualizations of the effects of single mutations to the SARS-CoV-2 spike receptor-binding domain (RBD) on recognition by three affinity-matured IGHV3-53 neutralizing antibodies.

These antibodies, CAB-A17, CAB-A49, and CAB-C19, were first described in [Sheward et al.](https://www.biorxiv.org/content/10.1101/2022.01.03.474825v1).

These visualizations are built using [dms-view](https://dms-view.github.io/docs/).
These experiments are described in **this pre-print**, and raw data are available [here](https://github.com/jbloomlab/SARS-CoV-2-RBD_MAP_Karolinska/blob/main/results/supp_data/karolinska_raw_data.csv).

Sites of escape are shown for each antibody, and are mapped to the ACE2-bound RBD structure ([PDB 6M0J](https://www.rcsb.org/structure/6M0J)).

`dms-view` renderings for each antibody's escape mapped to the ACE2-bound RBD structure:
 - <a href="https://dms-view.github.io/?markdown-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fdata%2Fdms-view_metadata.md&pdb-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fdata%2Fpdbs%2F6M0J.pdb&data-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fresults%2Fsupp_data%2Fkarolinska_6m0j_dms-view_data.csv&condition=CAB-C19&site_metric=site_max+escape&mutation_metric=mut_escape+color+ACE2+bind&selected_sites=&protein-data-color=&protein-other-color=pink" target="_blank">ACE2-bound RBD</a>

 `dms-view` renderings for CAB-A17's escape mapped to the Fab-bound Omicron BA.1 RBD structure. This structure was solved by Martin Hällberg and colleagues and is reported in the preprint linked above:
  - <a href="https://dms-view.github.io/?markdown-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fdata%2Fdms-view_metadata.md&pdb-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fdata%2Fpdbs%2FBA1_A17.pdb&data-url=https%3A%2F%2Fraw.githubusercontent.com%2Fjbloomlab%2FSARS-CoV-2-RBD_MAP_Karolinska%2Fmain%2Fresults%2Fsupp_data%2Fkarolinska_BA1_A17_dms-view_data.csv&condition=CAB-A17&site_metric=site_max+escape&mutation_metric=mut_escape+color+ACE2+bind&selected_sites=417%2C456%2C475&protein-data-color=lightgray&protein-other-color=darkslateblue" target="_blank">CAB-A17-bound Omicron BA.1 RBD</a>
