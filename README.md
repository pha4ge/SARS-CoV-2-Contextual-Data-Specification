# SARS-CoV-2 Contextual Data Specification - Collection template and associated materials for SARS-CoV-2 metadata

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4743829.svg)](https://doi.org/10.5281/zenodo.4743829)
![Pre-print DOI](https://img.shields.io/badge/preprints-10.20944%2Fpreprints202008.0220.v1-yellow)
![License](https://img.shields.io/badge/license-CC--BY%204.0%20International-lightgrey)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/pha4ge/SARS-CoV-2-Contextual-Data-Specification)

## Table of Contents

* [PHA4GE overview](#pha4ge-overview)
* [SARS-CoV-2 contextual data specification overview](#sars-cov-2-contextual-data-specification-overview)
* [Content description](#content-description)
+ [SARS-CoV-2 contextual data specification package](#sars-cov-2-contextual-data-specification-package)
    - [Spreadsheet-based (.xlsx) collection template](#spreadsheet-based--xlsx--collection-template)
    - [The specification contextual data collection template in machine-amenable JSON format](#the-specification-contextual-data-collection-template-in-machine-amenable-json-format)
+ [Standard operating procedure](#standard-operating-procedure)
+ [Supporting materials](#supporting-materials)
    - [PHA4GE to sequence repository field mappings](#PHA4GE-to-sequence-repository-field-mappings)
    - [Submission protocols](#submission-protocols)
        * [NCBI](#ncbi)
        * [ENA](#ena)
        * [GISAID](#gisaid)
* [JSON Specification Generation](#json-specification-generation)
* [Contacts](#contacts)
* [Citation](#citation)
* [License](#license)

## PHA4GE overview

The Public Health Alliance for Genomic Epidemiology ([PHA4GE](https://pha4ge.org)) is a global coalition that is actively working to establish consensus standards, document and share best practices, improve the availability of critical bioinformatic tools and resources, and advocate for greater openness, interoperability, accessibility and reproducibility in public health microbial bioinformatics.

In the face of the current SARS-CoV-2 pandemic, [PHA4GE](https://pha4ge.org) has identified a clear and present need for a fit-for-purpose, open source SARS-CoV-2 contextual data standard. As such, we have developed a SARS-CoV-2 contextual data specification based on harmonizable, publicly available, community standards.

## SARS-CoV-2 contextual data specification overview

Public health genomics contextual data includes sample metadata, lab/clinical/epidemiological data, and analysis methods information. Contextual data enables the interpretation of the sequence data, informs decision making for public health responses, and facilitates scientific understanding of infectious disease. Structured and consistent contextual data can also be more easily processed, aggregated, and reused by both humans and computers for different types of analyses.

The SARS-CoV-2 contextual data specification includes a metadata collection template, reference guide, controlled vocabulary, and mapping to existing standards. We also provide a suite of protocols for submitting sequence data and contextual data to public repositories, enabling global interoperability of the data. The specification and all of the supporting materials are freely available and detailed below.

## Content description

### SARS-CoV-2 contextual data specification package

#### [Spreadsheet-based (.xlsx) collection template](PHA4GE%20SARS-CoV-2%20Contextual%20Data%20Template.xlsx)

It contains the following items (tabs in the spreadsheet):

1. **a template for populating the complete set of contextual data;**

The collection template contains "required" (colour-coded yellow), "strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields. 

2. **guidance for populating the template;**

The reference guide aims to facilitate the use of the collection template. It contains field definitions, further guidance/instructions, and examples of structured data. Mapping of PHA4GE fields to existing metadata standards such as the Sample Application Standard, MIxS v 5.0, and the MIGS Virus Host-associated package can be found in the reference guide.

3. **ontology-mapped controlled vocabulary for the picklists.**

Lists of controlled vocabulary, agreed upon by PHA4GE, are provided here for populating the template.

#### [The specification contextual data collection template in machine-amenable JSON format](PHA4GE_SARS-CoV-2_Contextual_Data_Schema.json)

Due to **JSON** format limitation, it deviates slightly from the collection template where the "required" (colour-coded yellow) fields are set as required and both the "strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields are both set as optional.


### Standard operating procedure

A **Standard Operating Procedure (SOP)** containing instructions for using the collection template.
This SOP provides users with step-by-step instructions for populating the template, looking up standardized terms, and how best to structure sample descriptions. Also included are a number of ethical, practical, and privacy considerations for data sharing. The SOP is available in protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.btpznmp6](https://dx.doi.org/10.17504/protocols.io.btpznmp6).


### Supporting materials

#### [PHA4GE to sequence repository field mappings](PHA4GE%20to%20Sequence%20Repository%20Field%20Mappings.xlsx)

A **mapping file** indicating which PHA4GE fields correspond to which fields within the different repository submission forms is provided to facilitate data transformations for submissions. 

#### Submission protocols

Submission protocols are available for the following data repositories: 

##### NCBI

The entire collection of submission protocols is available as a workflow at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bsypnfvn](http://dx.doi.org/10.17504/protocols.io.bsypnfvn). This workflow includes the following individual protocols:

1. **PHA4GE contextual metadata SOP**
This SOP provides users with step-by-step instructions for populating the collection template. The SOP is available in protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.btpznmp6](https://dx.doi.org/10.17504/protocols.io.btpznmp6)

2. **Overview of NCBI's submission process and the metadata required**
Provides an overview of the submission process and includes a brief training video. The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bsbpnamn](https://dx.doi.org/10.17504/protocols.io.bsbpnamn).

3. **SARS-CoV-2 NCBI submission protocol: SRA, BioSample, and BioProject**
Step-by-step instructions for establishing a new NCBI laboratory submission account, creating and linking a new BioProject to an existing umbrella effort, and submitting raw sequence data with assocated metadata to SRA and BioSample. The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bsypnfvn](https://dx.doi.org/10.17504/protocols.io.bsypnfvn).

4. **SARS-CoV-2 NCBI consensus submission protocol: GenBank**
Step-by-step instructions for submitting SARS-CoV-2 consensus sequencing to NCBI GenBank and linking to existing BioProject, BioSamples, and raw data. The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bid7ka9n](https://dx.doi.org/10.17504/protocols.io.bid7ka9n).

##### ENA

The entire collection os submission protocols is available as a workflow at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.buqnnvve](https://dx.doi.org/10.17504/protocols.io.buqnnvve).

Three separate protocols are included:

1. **SOP for populating EBI submission templates**
The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bh5dj826](https://dx.doi.org/10.17504/protocols.io.bh5dj826).

2. **SARS-CoV-2 EBI submission protocol: ENA, BioSample, and BioProject**
The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bhwdj7a6](https://dx.doi.org/10.17504/protocols.io.bhwdj7a6).

3. **SARS-CoV2 EBI assembly submission protocol**
The protocol is available at protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bhwqj7dw](https://dx.doi.org/10.17504/protocols.io.bhwqj7dw).

##### GISAID

This protocol provides the steps needed to establish a new GISAID submission environment for your laboratory. Once established, this protocol covers genome submission sample metadata to GISAID. The protocol is available in protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bumknu4w](https://dx.doi.org/10.17504/protocols.io.bumknu4w).

## JSON Specification Generation
The [JSON](PHA4GE_SARS-CoV-2_Contextual_Data_Schema.json) is produced automatically from the [csv version](PHA4GE%20SARS-CoV-2%20Standardised%20Terms.csv) of the template using the the script available from [SARS-CoV-2-Data-Spec-JSON](https://github.com/pha4ge/SARS-CoV-2-Data-Spec-JSON) repository.

**Table 1** Terms for SARS-CoV-2 submission template according to the PHA4GE contextual data collection specification in 
[PHA4GE SARS-CoV-2 Standardised Terms](PHA4GE%20SARS-CoV-2%20Standardised%20Terms.csv)  
| Column 	| Description 	|
|:-:	|:-:	|
| Interface Label 	| Column headers in the submission template 	|
| Required/Optional 	| Type of requirement according to PHA4GE's template specification. Limited to the values "Optional", "Recommended" and "Required".  	|
| Definition 	| Short description for the expected interface label value. 	|
| Value Type 	| Expected interface label's value type. Expected values: "String", "Int", "Float", "Bioproject_ID", "Biosample_ID", "SRA_ID", "Genbank_ID", "GISAID_ID", "Email", "Date" and "Integer_or_Range". 	|
| Example 	| Example for the expected interface label value. 	|
| Guidance 	| Detailed description for the expected interface label value. 	|

## Contacts 

For more information and/or assistance, contact `datastructures@pha4ge.org` or the issue page of this repository.

## Citation

Griffiths, E.J.; Timme, R.E.; Page, A.J.; Alikhan, N.; Fornika, D.; Maguire, F.; Mendes, C.I.; Tausch, S.H.; Black, A.; Connor, T.R.; Tyson, G.H.; Aanensen, D.M.; Alcock, B.; Campos, J.; Christoffels, A.; Gonçalves da Silva, A.; Hodcroft, E.; Hsiao, W.W.; Katz, L.S.; Nicholls, S.M.; Oluniyi, P.E.; Olawoye, I.B.; Raphenya, A.R.; Vasconcelos, A.T.R.; Witney, A.A.; MacCannell, D.R. **The PHA4GE SARS-CoV-2 Contextual Data Specification for Open Genomic Epidemiology.** _Preprints_ 2020, 2020080220 (doi: [10.20944/preprints202008.0220.v1](https://www.preprints.org/manuscript/202008.0220/v1)).

## License 

[CC-BY 4.0 International](LISENCE.md)
