.. Bioinformatics and R User Group 
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Bioinformatics and R User Group
=============================================================

**Organizers:**


* Asela Wijeratne (wijeratne.1[at]osu[dot]edu)

* Saranga Wijeratne (wijeratne.3[at]osu[dot]edu)

* Stephen Opiyo (opiyo.1[at]osu[dot]edu)

* Tea Meulia (meulia.1[at]osu[dot]edu) **(Faculty advisor)**



Objectives of the meeting:
---------------------------------------------------------------
1.     To provide a place for the MCBL users and other bioinformatic practitioners to meet and share ideas and thoughts, and provide feedback for each other's work.
2.     To provide an opportunity for the users to discuss difficulties they have and to get help from the MCBL staff.
 
Agenda:
---------------------------
1. First 10-15 minutes will be dedicated to discuss user issues

2. Presentation 


Who should participate:
-------------------------------
All the MCBL users. 
For non-MCBL users, if you are a bioinformatic practitioner and are interested in participating in these meetings, please contact us.
 
We will meet the last Thursday of every month (except for November). Please go to the following link to see the full schedule: 

Meetings
------------------------
We will meet the last Thursday of every month (except for November). Please go to the following link to see the `full schedule`_: 

.. _full schedule: http://bit.ly/1HwThpe



Presentations
===================================

March 26
----------------

Discussed user issues.

Please go to this link to get the `minutes`_:
 
.. _minutes: https://drive.google.com/file/d/0B7uMQmwhsPG8bW5TdWh0VXd0QWc/view?usp=sharing


April 30
------------------
**Presenter**: Aditi Sengupta  

**Title**: Targeted amplicon-based sequencing strategy to determine bacterial community diversity in soils


May 28
------------------

**Presenter**: David Showalter

**Title**: Ortholog identification and differential expression analysis across species



June 25
-----------------------

**Presenter**: Dr. Asela Wijeratne

**Title**: RNA-seq quantification in five minutes with Kallisto

Abstract:
************************

Kallisto is described in a new paper (still in pre-pub:http://bitly.com/kallisto_rnaseq) and would analyze 30 million RNAseq reads in 5 minutes on a laptop (as opposed to hours on a multicore server using other software). During the talk, I will:

* Give an introduction to RNA-seq analysis

* Describe how Kallisto works and how it is different from existing software

* Present some results from an analysis that I performed using Kallisto

* Give a quick demo of the analysis 

* `Online tutorial`_

.. _Online tutorial: http://bit.ly/RNAseq_150625

July 30
----------------

**Presenter**: Dr. Eudald Illa Berenguer (van der Knaap Lab) will present his analysis using QTL-seq. 

**Title**: QTL-seq: a rapid and efficient way to identify new QTLs in tomato, too

Abstract:
**********************

Domestication of fruit and vegetable crops was accompanied by selection for edible parts weight. This increase in fruit weight is controlled by multiple quantitative trait loci (QTL) of large and small effects. To date, only two fruit weight genes have been cloned and a third has been fine-mapped. To efficiently identify additional fruit weight loci, three populations were generated from crosses between cultivated tomato and wild relatives followed by bulked-segregant analysis coupled with whole genome sequencing (QTL-seq) approach. This method led to the identification of three fruit weight QTLs. fw11.2, was identified at the distal part of chromosome 11 and the location confirmed to a 1.62-Mb interval. fw1.1 was found in the peri-centromeric region of chromosome 1. Extremely low recombination frequencies preclude the cloning of this gene. Lastly, fw3.3 was mapped to a region ~1.6-Mb below the known fruit weight gene, SlKLUH/FW3.2. To confirm the location of the genes underlying fw11.2 and fw3.3, we used the genome sequence data to develop additional markers and conducted recombinant screens. The recombinant progeny tests allowed us to narrow down fw11.2 QTL to a region of ~750-kb corresponding to 66 candidate genes. Our research approach provides a cost and time-effective basis for the identification of additional genes involved in fruit weight that could be used for tomato improvement.


August 27
-------------------

**Presenter**: Dr. Stephen Opiyo

**Title**: Introduction to Metabolomics for Biomarker Discovery

Abstract:
*******************

Metabolomics is becoming an increasingly popular tool in the plant sciences. It can be applied with either a particular focus or in a global manner to reveal new knowledge about biological systems.  In this presentation, I will discuss approaches in metabolomics, and how we have employed them in biomarker discovery in our collaborative research.


September 24
---------------------

**Presenter**: Dr. Vitor Antonio Corrêa Pavinato 

**Title**: RAD (Restriction site Associated DNA) for de novo sequencing and marker discovery 

October 29
------------------------

**Presenter**: Deb Liabeuf

**Title**: Comparison of SNP density across lines from vcf files, using a custom Python script and a custom R script

Abstract:
******************

To compare the whole genome sequences of lines from a same species or from closely related species is of interest to understand their relationships at the genetic fragment scale, bringing light on the evolutionary or breeding process which lead to these organisms. We compared the whole genome sequence of a tomato variety and of 6 of its parents, using custom python and R scripts comparing the SNP density of  the lines in a sliding window. This first approach helped us to indentify the donor parent of each genetic fragment of our variety. These observations are made in the frame of reference genome, however, the parent lines of this variety are from different tomato species, thus the variety may carry major structure variations as deletions or inversions, which do not appear when aligned to a reference. We used the software Lumpy and CNVnator to detect these major structure variations. This presentation is a tutorial detailing the steps for these two analysis. I will stress the main steps and interests of these methods. The tutorial is available on demand. 

November 19
---------------------

**Presenters**: Maria Elena Hernandez Gonzalez (MCIC) and Saranga Wijeratne (MCIC)

**Title**: Introduction to Illumina’s BaseSpace and BaseMount
 
Abstract:
**********************

You have received an email saying your Illumina sequencing data is ready! And you are wondered “now what???” Please come and discover two possible ways to get your information using Illumina’s:
1.  BaseSpace
2.  BaseMount
First, we will show the basics of BaseSpace, which is a web server application with a GUI interface.  Then we will demonstrate how to mount BaseSpace using BaseMount, a Linux command line interface for BaseSpace, on to a local computer and do a basic analysis of sequence files without having to download the files onto a local hard drive.