---
title: "https://pubs.acs.org/doi/10.1021/acs.jctc.1c00363
collection: publications
permalink: /publication/2021-tautomers
excerpt: 'Tautomers and Machine Learning'
date: 2015-10-01
venue: 'Journal of Chemical Theory and Computation'
paperurl: 'https://pubs.acs.org/doi/10.1021/acs.jctc.1c00363'
citation:  Vazquez-Salazar, L. I., Boittier, E., Unke, O. T., & Meuwly, M. (2021). &quot;Impact of the characteristics of quantum chemical databases 
            on machine learning predictions of tautomerization energies.&quot;  <i>Journal of Chemical Theory and Computation</i> 17 (8), 4769-4785
---


An essential aspect for adequate predictions of chemical properties by machine learning models is the database used for training them. 
However, studies that analyze how the content and structure of the databases used for training impact the prediction quality are scarce. 
In this work, we analyze and quantify the relationships learned by a machine learning model (Neural Network) trained on five different reference 
databases (QM9, PC9, ANI-1E, ANI-1, and ANI-1x) to predict tautomerization energies from molecules in Tautobase. 
For this, characteristics such as the number of heavy atoms in a molecule, number of atoms of a given element, bond composition, 
or initial geometry on the quality of the predictions are considered. The results indicate that training on a chemically diverse
database is crucial for obtaining good results and also that conformational sampling can partly compensate for limited 
coverage of chemical diversity. The overall best-performing reference database (ANI-1x) performs on average by 1 kcal/mol better 
than PC9, which, however, contains about 2 orders of magnitude fewer reference structures. On the other hand, PC9 is chemically more 
diverse by a factor of ∼5 as quantified by the number of atom-in-molecule-based fragments (amons) it contains compared with the ANI 
family of databases. A quantitative measure for deficiencies is the Kullback–Leibler divergence between reference and target distributions. 
It is explicitly demonstrated that when certain types of bonds need to be covered in the target database (Tautobase) but are undersampled in
the reference databases, the resulting predictions are poor. Examples of this include the poor performance of all databases analyzed to 
predict C(sp2)–C(sp2) double bonds close to heteroatoms and azoles containing N–N and N–O bonds. Analysis of the results with a Tree MAP
algorithm provides deeper understanding of specific deficiencies in predicting tautomerization energies by the reference datasets 
due to inadequate coverage of chemical space. Capitalizing on this information can be used to either improve existing databases or generate 
new databases of sufficient diversity for a range of machine learning (ML) applications in chemistry.

[Download paper here](https://arxiv.org/abs/2104.06099)
