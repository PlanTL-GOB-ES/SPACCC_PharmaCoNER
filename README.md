# SPACCC_CheNE: Spanish Clinical Case Corpus - Chemical Named Entities


## Introduction

This repository contains the annotations of chemical mentions, drugs and biosimilars with therapeutic relevance in clinical reports in the Spanish Clinical Case Corpus. 


## Repository structure

<pre>
corpus/
The annotated corpus.

guidelines/
Annotation guidelines.

IAA/
Inter-annotator agreement report.

README.md
This file.
</pre>


## Document selection

The SPACCC corpus was created after collecting 1,000 clinical cases from SciELO (Scientific Electronic Library Online), an electronic library that gathers electronic publications of complete full text articles from scientific journals of Latin America, South Africa and Spain (http://www.scielo.org).

A clinician classified those cases into those that were similar to real clinical texts in terms of structure and content and those that were not suitable for this task. Figure legends were automatically removed and in case multiple clinical cases were listed, these were split into single clinical cases.


## Annotation tool

Annotations were carried out through AnnoateIt (https://github.com/openannotation/annotateit).


## Annotation format


## Annotation types


## Corpus predictions


## Annotation guidelines

The annotation guidelines describe the criteria that have been followed to annotate the corpus, along with illustrative examples. 

Guidelines have been written and developed in Spanish and are only available in Spanish.


## Corpus consistency

The following table shows the interagreement results measured on a set of 50 documents. See the inter-annotator agreement report (Informe de control de calidad.pdf) included in folder IAA for further details. The required minimum level of agreement was 93%.

|                                        |           |
| -------------------------------------- | --------- |
| Total number of annotations            | 251       |
| Annotations made by the annotator 1    | 217 (86%) |
| Annotations made by the annotator 2    | 201 (80%) |
| Matching annotations                   | 235 (93%) |
| Coincidence in annotations (same type) | 191 (76%) |

Table 1: Interagreement betwen the two human annotators


## Contact

Montserrat Marimon (montserrat.marimon@bsc.es)


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Copyright (c) 2018 Secretaría de Estado para el Avance Digital (SEAD)
