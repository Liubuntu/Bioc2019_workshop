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

Students will be using their laptops with internet connection, open the 
course material and follow the instructor to read contents and run through
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

List "big picture" student-centered workshop goals and learning
objectives. Learning goals and objectives are related, but not the
same thing. These goals and objectives will help some people to decide
whether to attend the conference for training purposes, so please make
these as precise and accurate as possible.

*Learning goals* are high-level descriptions of what
participants will learn and be able to do after the workshop is
over. *Learning objectives*, on the other hand, describe in very
specific and measurable terms specific skills or knowledge
attained. The [Bloom's Taxonomy](#bloom) may be a useful framework
for defining and describing your goals and objectives, although there
are others.

## Learning goals

Some examples:

* describe how to...
* identify methods for...
* understand the difference between...

## Learning objectives

* analyze xyz data to produce...
* create xyz plots
* evaluate xyz data for artifacts

### A note about learning goals and objectives (#bloom)

While not a new or modern system for thinking about learning,
[Bloom's taxonomy][1] is one useful framework for understanding the
cognitive processes involved in learning. From lowest to highest
cognitive requirements:

1. Knowledge: Learners must be able to recall or remember the
   information.
2. Comprehension: Learners must be able to understand the information.
3. Application: Learners must be able to use the information they have
   learned at the same or different contexts.
4. Analysis: Learners must be able to analyze the information, by
   identifying its different components.
5. Synthesis: Learners must be able to create something new using
   different chunks of the information they have already mastered.
6. Evaluation: Learners must be able to present opinions, justify
   decisions, and make judgments about the information presented,
   based on previously acquired knowledge.

To use Bloom's taxonomy, consider the following sets of verbs and
descriptions for learning objectives:

1. Remember: Memorize, show, pick, spell, list, quote, recall, repeat,
   catalogue, cite, state, relate, record, name.
2. Understand: Explain, restate, alter, outline, discuss, expand,
   identify, locate, report, express, recognize, discuss, qualify,
   covert, review, infer.
3. Apply: Translate, interpret, explain, practice, illustrate,
   operate, demonstrate, dramatize, sketch, put into action, complete,
   model, utilize, experiment, schedule, use.
4. Analyze: Distinguish, differentiate, separate, take apart,
   appraise, calculate, criticize, compare, contrast, examine, test,
   relate, search, classify, experiment.
5. Evaluate: Decide, appraise, revise, score, recommend, select,
   measure, argue, value, estimate, choose, discuss, rate, assess,
   think.
6. Create: Compose, plan, propose, produce, predict, design, assemble,
   prepare, formulate, organize, manage, construct, generate, imagine,
   set-up.

[1]: https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/ "Bloom's Taxonomy"
