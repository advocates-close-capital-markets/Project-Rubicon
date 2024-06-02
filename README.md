# Project-Rubicon


# Mathematical Methods for Applications of Machine Intelligence: Corporate Law in New York 

## Overview

Attention is to the development of mathematical methods suitable for use in applications to corporate law. Of note is the need for methods permitting:
  - Recall: Documents (defined below) that refer to other Documents which in turn point to still other Documents are problematic. Proving the nonexistence of a thing is difficult and does not follow from proofs as to the mere absence or impossibility of such thing. A solution concept is given below. 
  - Rigor: Statistical methods are problematic for reasons that include, at a minimum:
    - There does not exist a straightforward or otherwise commonsense way of defining variance, at least not in the sense that would be most useful here. The observation is due to Chebychev (1853). The severity of the bias noted therein salvages the concept, which is used to develop an inference method used later in this project. [To do: applications of Chebychev bias in prime number races permits discrimation as between inferences that would otherwise have appeared to be identical.]
    - [To do: language is not continuous, which is obvious but important. Language models all use some sort of optimization concept and one wonders exactly what the modeler would advise is meant when two words are "averaged." Why distributions would be assumed normal is not obvious to me either--they are in fact known _not_ to be normal. I am not persuaded by observations as to the directionality of two vectors that are purportedly useful because they permit the inference that king is to man as queen is to woman.]
    
All of the above is to provide support, even if heuristically, for the proposition that the mathematical methods that are needed to make any use out of computational approaches to the practice of law are not suitable. 


## Workflow
This project provides a comprehensive workflow for parsing, diffing, indexing, and analyzing documents filed with the SEC. Solution is designed with a view towards extensibility over interpretability and for usability over speed. 

1. **Indexing is via Apache Solr**:
   - Index HTML documents using Apache Solr for search functionality and statistical analysis.
   - [index_documents.sh](./index_documents.sh): Script to index documents.

2. [To do: remainder hereof to be provided upon redaction of related materials.]

    
## Setup and Usage

### Prerequisites

- Apache Solr
- C++
- Perl with `HTML::Diff`
- Python 3
- Qiskit

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/html-processing.git
   cd html-processing
