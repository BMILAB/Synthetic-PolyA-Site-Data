Synthetic poly(A) site data
====================

Based on real rice poly(A) site data, we generate synthetic poly(A) site data sets with a certain number of conditions (tissues, developmental states, etc.) and repeated measurements.

About
====================
The real poly(A) site data set which consists of 14 tissues each with two or three repeated measurements in rice was collected from the [previous study](http://www.genome.org/cgi/doi/10.1101/gr.210757.116). In order to get data sets with a certain number of conditions (tissues, developmental states, etc.) and repeated measurements, we used a two-step process to generate synthetic data that have the same distributions of abundance of poly(A) sites derived from the rice data. See our [paper](http://www.genome.org/cgi/doi/10.1101/gr.210757.116) for details.

Files information
=============
This directory contains three files:
* **diff_replicates**. The files are consistently namesd following this pattern:
```
<species>_<gene number>_<repli number>.csv
<species>: The systematic name fo the species. ja = oryza sativa japonica.
<gene number>: The number of genes contained in this data set.
<repli number>: The number of replication.
```
* **diff_numbers**. The files are consistently namesd following this pattern:
```
[<species>_<gene number>_<repli number>.csv][type]
<species>: The systematic name fo the species. ja = oryza sativa japonica.
<gene number>: The number of genes contained in this data set.
<repli number>: The number of replication.
```
* **diff_tissues**. The files are consistently namesd following this pattern:
```
<species>_<gene number>_<tissues number>_<id>.csv
<species>: The systematic name fo the species. ja = oryza sativa japonica.
<gene number>: The number of genes contained in this data set.
<tissue number>: The number of types of tissues contained in this data set.
<id>: Data index number.
```
