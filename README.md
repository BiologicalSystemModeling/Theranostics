# Theranostics
Galaxy and MEAN stack to create a user-friendly workflow for the rational optimization of cancer chemotherapy

By: Jorge Guerra Pires1,2, Gilberto Ferreira da Silva1,2, Thomas Weyssow3, Alessandra Jordano Conforte2,4, Dante Pagnoncelli5, Fabricio Alves Barbosa da Silva4, Nicolas Carels1,2,*

Emails:
Jorge Guerra Pires - jorgeguerrapires@yahoo.com.br;
Gilberto Ferreira da Silva - gilbertofs@gmail.com;
Thomas Weyssow - thomas.weyssow@gmail.com;
Alessandra Jordano Conforte - conforteaj@gmail.com;
Dante Pagnoncelli - dantepagnoncelli@gmail.com;
Fabricio Alves Barbosa da Silva - fabs.fiocruz@gmail.com;
Nicolas Carels - nicolas.carels@cdts.fiocruz.br; nicolas.carels@gmail.com

1 hese authors contributed equally to this research.
2 Plataforma de Modelagem de Sistemas Biológicos, Center for Technology Development in Health (CDTS), Oswaldo Cruz Foundation (FIOCRUZ), Rio de Janeiro, Brazil.
3 Informatic Department, Free University of Brussels (ULB), Brussels, Belgium.
4 Laboratório de Modelagem Computacional de Sistemas Biológicos, Scientific Computing Program, FIOCRUZ, Rio de Janeiro, Brazil.
5 Centro de Oncologia Integrado (COI), Botafogo, Rio de Janeiro, Brazil.

*Correponding author: e-mails: nicolas.carels@cdts.fiocruz.br ; nicolas.carels@gmail.com

Abstract: 
One aspect of personalized medicine is aiming at identifying specific targets for therapy considering the gene expression profile of each patient individually. The real-world implementation of this approach is better achieved by user-friendly bioinformatics systems for healthcare professionals. In this report, we present an online platform that endows users with an interface designed using MEAN stack supported by a Galaxy pipeline. This pipeline targets connection hubs in the subnetworks formed by the interactions between the proteins of genes that are up-regulated in tumors. This strategy has been proved to be suitable for the inhibition of tumor growth and metastasis in vitro. Therefore, Perl and Python scripts were enclosed in Galaxy for translating RNA-seq data into protein targets suitable for the chemotherapy of solid tumors. Consequently, we validated the process of target diagnosis by (i) reference to subnetwork entropy, (ii) the critical value of density probability of differential gene expression, and (iii) the inhibition of the most relevant targets according to TCGA and GDC data. Finally, the most relevant targets identified by the pipeline are stored in MongoDB and can be accessed through the aforementioned internet portal designed to be compatible with mobile or small devices through Angular libraries.
	
Keywords: Systems biology, translational oncology, personalized medicine, Galaxy, MEAN stack, Angular, network, Shannon entropy.

This matter is being published in Frontiers in Genetics and the full paper will be up-loaded here when available.

The perl, python and xml codes are given in the "GalaxyScripts" sub-directory. Note that the use of these codes is under MIT licence, but that the concept of theranostics, as presented here, was registered under the Brazilian intelectual property regulation number BR1020150308191. Organizations interested in the development of this concept are encouraged to contact Nicolas Carels. The interactome data are given in the "Interactome" sub-directory. These data enable to reproduce the finding of the paper content summarized above. The TCGA, GDC, and ArrayEXPRESS data that were used for this exercice can be retrieved from the GDC (https://portal.gdc.cancer.gov/) and ArrayEXPRESS (https://www.ebi.ac.uk/arrayexpress/) portals. They are far too big (hundreds of gigabases) to be up-loaded here. Finally, the code that has been written for the front-end is available from https://github.com/Teranostico.
