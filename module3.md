---
layout: page
title: Module 3
permalink: /module3/
---


# Module 3. Bioinformatics and Systems Biology

Computational analysis of OMICs data (genomics, transcriptomics, proteomics).  Analysis of protein-protein interactions and gene expression data. Pathways and networks, machine learning. Example applications from translational medicine and cell biology.

  
**N.B.** Please complete this pre-course [**questionnaire**](http://tinyurl.com/bioinf525-questions) if you have not already done so. 


|         |         |                    | 
| :-----: |:------:| :----------------------- | 
| **3.1** | Lecture | [**Introduction to systems biology**](#3.1) | 
|         | Lab     | [Network analysis for systems biology](#3.1) | 
| **3.2** | Lecture | [**Epigenome data mining to understand disease predisposition**](#3.2) | 
|         | Lab     | [Epigenome profiling and disease links](#3.2)       | 
| **3.3** | Lecture | [**Computational clinical decision support systems**](#3.3)  | 
|         | Lab     | [WEKA for machine learning and feature analysis](#3.2)  | 
| **3.4** | Lecture | [**Application of systems biology to translational medicine**](#3.4) | 
|         | Lab     | [Systems biology resources for translational medicine](#3.4)  | 

<br>

---
<a name="3.1"></a>
<br>

#### Lecture (3-1):	**Introduction to systems biology**  
- **Instructor**: 	Dr. Gerry Higgins  
- **Time**: 		Mar 22 (Tuesday), 2:30 - 4:00 PM  
- **Topics**:  
What are bioinformatics and computational biology?  Major NCBI and EBI bioinformatics resources.  How do we actually do bioinformatics?  Major areas of research and application.  
- **Material**:  
[Lecture Slides]({{ site.baseurl }}/class-material/lecture3-1.pdf)  
Readings  
[A glutamatergic network mediates lithium response in bipolar disorder](https://ctools.umich.edu/access/content/group/cd806bd4-a051-4873-9be1-4a158109a66b/Module%203/A%20glutamatergic%20network%20mediates%20lithium%20response%20in%20bipolar%20disorder.pdf),  
[Cold Spring Harb Perspect Biol-2015-Dekker-](https://ctools.umich.edu/access/content/group/cd806bd4-a051-4873-9be1-4a158109a66b/Module%203/Cold%20Spring%20Harb%20Perspect%20Biol-2015-Dekker-.pdf),  
[Ten Years of Pathway Analysis](https://ctools.umich.edu/access/content/group/cd806bd4-a051-4873-9be1-4a158109a66b/Module%203/Ten%20Years%20of%20Pathway%20Analysis.pdf)  


<br>

#### Lab (3-1): 	**Network analysis for systems biology**  
- **Instructor**: 	Marci Brandenburg and Dr. Viji Nair  
- **Time**: 		2:30 – 4:00 PM, Mar 24 (Thursday) or Mar 25, 10:30 - 12:00 PM, (Friday)  
- **Topics**:  
Representation of data as graphs.  Pathway and network exploration and visualization with Cytoscape, including the MetScape app, in addition to ConceptGen.  
- **Material**:  
[Lab slides]({{ site.baseurl }}/class-material/Bfx525_2016_Cytoscape_Final.pptx)  
Supporting Files:  
[Reactomedata.txt]({{ site.baseurl }}/class-material/Reactomedata.txt),  
[aminoacids.output.pcor_lasso.17of23.csv]({{ site.baseurl }}/class-material/aminoacids.output.pcor_lasso.17of23.csv),  
[cytoscapeoverview.txt]({{ site.baseurl }}/class-material/cytoscapeoverview.txt),  
[metscape_test.csv]({{ site.baseurl }}/class-material/metscape_test.csv)  
[Muddy point assessment](https://docs.google.com/forms/d/1WUDoBCwzH8wNF46rDNLtTw-DVUqJDu9rt5XTfwPj2mA/viewform)  

<br>

---
<a name="3.2"></a>
<br>

#### Lecture (3-2): **Epigenome data mining to understand disease predisposition**  
- **Instructor**: 	Dr. Stephen Parker  
- **Time**: 		Mar 29 (Tuesday), 2:30 - 4:00 PM  
- **Topics**:  
For decades, substantial research efforts have focused on the <2% of the human genome that encodes proteins. Recent epigenome-based functional genomic analyses and genome-wide association studies (GWAS) together implicate non-coding DNA regulatory elements as critical regions influencing gene expression, risk for common diseases, variation in physiological traits, and evolution across species. Because they represent the convergent point of evolutionary, genetic, developmental, and environmental inputs, basal epigenomic signatures and their dynamic changes are central to understanding biological function. This lecture will explore epigenomic assays and bioinformatic analyses and how these approaches can help untangle disease mechanisms. 
- **Material**:  
[Lecture Slides]({{ site.baseurl }}/class-material/lecture3-2.pptx)  
Readings  
[Integrative analysis of 111 reference human epigenomes](https://ctools.umich.edu/access/content/group/cd806bd4-a051-4873-9be1-4a158109a66b/Module%203/Integrative%20analysis%20of%20111%20reference%20human%20epigenomes.pdf)  


<br>

#### Lab (3-2): 	**Epigenome profiling and disease links**  
- **Instructor**: 	Dr. Stephen Parker  
- **Time**: 2:30 – 4:00 PM, Mar 31 (Thursday) or Apr 1, 10:30 - 12:00 PM, (Friday)  
- **Topics**:  
Students will learn how to computationally process epigenomic data, create interactive displays of these profiles, and then use the profiles to interpret disease associated genetic variations.
- **Material**:  
[Lab Link](https://github.com/ParkerLab/bioinf525)  
[Muddy point assessment](https://docs.google.com/forms/d/1P3zEXxybasJWttziZ9F_osiFaM1418Zu0vppH--GtoM/viewform)  


<br>

---
<a name="3.3"></a>
<br>

#### Lecture (3-3): **Computational clinical decision support systems** 
- **Instructor**:   Dr. Kayvan Najarian  
- **Time**:         Apr 5 (Tuesday), 2:30 - 4:00 PM  
- **Topics**:  
Introduction to computational clinical decision support systems. Machine learning and its application to biomedical informatics.

<br>

#### Lab (3-3):     **WEKA for machine learning and feature analysis**  
- **Instructor**:   Dr. Kayvan Najarian  
- **Time**:         2:30 – 4:00 PM, Apr 7 (Thursday) or Apr 8, 10:30 - 12:00 PM, (Friday)  
- **Topics**:  
Introduction to WEKA, using machine learning methods such as SVM, Random Forest, Neural Networks for simple examples in systems biology, using WEKA for feature extraction and analysis.  
- **Material**: [Lab worksheet]

<br>

---
<a name="3.4"></a>
<br>

#### Lecture (3-4): **Application of systems biology to translational medicine**  
- **Instructor**: 	Dr. Matthias Kretzler  
- **Time**: 		Apr 12 (Tuesday), 2:30 - 4:00 PM  
- **Topics**:  
Integrating genome wide data sets with high-resolution clinical phenotypes, molecular marker definition, regulatory network generation in patient samples.  

<br>

#### Lab (3-4): 	**Systems biology resources for translational medicine** 
- **Instructor**: 	Felix Eichinger
- **Time**: 		2:30 – 4:00 PM, Apr 14 (Thursday) or  Apr 15, 10:30 - 12:00 PM, (Friday)
- **Topics**:
Introduction to web based systems biology resources including Oncomine and Nephromine.
- **Material**: [Lab worksheet]


<br>

### Reference material
<!--- files dont exist yet...
[Slides-2.1]()
[Slides-2.2]()
-->

