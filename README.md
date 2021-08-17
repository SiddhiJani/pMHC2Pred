# MHC2AffyPred: Structural Interaction Fingerprinting of MHC Class II HLA-DR B1 gene Peptide and Affinity Estimation using Machine Learning Approach
Understanding how MHC-II binding peptides with differing lengths exhibit specific interaction at the core and extended sites within the large MHC-II pocket is a very important aspect of immunological research for designing peptides. Certain efforts were made to generate peptide conformations amenable for MHC-II binding and calculate the binding energy of such complex formation but not directed towards developing a relationship between the peptide conformation in MHC-II structures and the binding affinity (IC50). We present here a machine-learning approach to calculate the binding affinity of the peptides within the MHC-II pocket for HLA-DRA1, HLA-DRB1 allotype. Instead of generating ensembles of peptide conformations conventionally, the biased mode of conformations was created by considering the peptides in the crystal structures of pMHC-II complexes as the templates, followed by site-directed peptide docking. The structural interaction fingerprints (SIFTs) generated from such docked pMHC-II structures along with the Moran autocorrelation descriptors were trained using a random forest regressor for MHC-II peptide lengths of 9 to 19. The entire workflow is automated using Linux shell and Perl scripts to promote the utilization of MHC2AffyPred program to any characterized MHC-II allotypes and is accessible herer. The MHC2AffyPred attained better performance (correlation coefficient of 0.612 to 0.898) than MHCII3D (0.03 to 0.594) and NetMHCIIpan-3.2 (0.289 to 0.692) programs. Further, a case study on MHC-II binding 15-mer peptides of SARS-CoV-2 showed very close competency in computing the IC50 values compared to the sequence-based NetMHCIIpan-3.2 program with a correlation of 0.998.\


![image](https://user-images.githubusercontent.com/80392409/126908154-37dacd56-f16f-4521-9e61-b1af66bac48c.png)



