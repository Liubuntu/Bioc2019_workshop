# Lazy representation of very large genomic resources in R/Bioconductor

# Qian Liu and Martin Morgan. 
Qian.liu@roswellpark.org. Roswell Park Comprehensive Cancer Center

# Workshop Description

In this workshop, we will learn the existing R/Bioconductor lazy 
infrastructures, as well as the development of new interfaces. We will
also show some examples in representation and comprehension of very big 
dataset from DNA/RNA-seq data. The workshop will be mainly instructor-led 
live demo with completely working examples. Instructions and notes will 
be included. 

## Pre-requisites

* Basic knowledge of R syntax
* Familiarity with the DelayedArray class
* Familiarity with SummarizedExperiment class

List relevant background reading for the workshop, including any
theoretical background you expect students to have.

* List any textbooks, papers, or other reading that students should be
  familiar with. Include direct links where possible.

## Workshop Participation

Students will be using their laptops with internet connection, follow
the instructor to read course materials and run through
the working code chunks.

## _R_ / _Bioconductor_ packages used

* VariantAnnotation
* DelayedArray
* VCFArray
* [SQLDataFrame](https://github.com/Bioconductor/VariantExperiment)
* SingleCellExperiment
* SummarizedExperiment
* [VariantExperiment](https://github.com/Bioconductor/VariantExperiment)

## Time outline

| Activity                            | Time |
|-------------------------------------|------|
| Conventional infrastructures        | 5m   |
| DelayedArray and extension          | 20m  |
| lazy DataFrame packages             | 20m  |
| RESTful APIs                        | 10m  | 
| lazy interface development          | 10m  |
|example 1: Single cell in HDF5Array  | 20m  |
|example 2: SQLDataFrame for BigQuery | 20m  |

# Workshop goals and objectives

Refer to: [Bloom's Taxonomy](#bloom)

## Learning goals

* know the lazy representations available in _R_ / _Bioconductor_
* know the popular computational infrastructures in need of _R_ / _Bioconductor_ interfaces
* understand the development requirements for lazy interfaces
* know the application of lazy interfaces in high-throughput genomic data

## Learning objectives

* create HDF5Array, VCFArray from HDF5 file and VCF file
* analyze _SingleCellExperiment_ data with HDF5Array
* create SQLDataFrame from SQL database table on local disk or web resources (e.g., BigQuery)


[1]: https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/ "Bloom's Taxonomy"
