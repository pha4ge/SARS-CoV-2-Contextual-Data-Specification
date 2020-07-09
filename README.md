# SARS-CoV-2 Contextual Data Specification - Collection template and associated materials for SARS-CoV-2 metadata

## Overview
The Public Health Alliance for Genomic Epidemiology ([PHA4GE](https://pha4ge.org)) is a global coalition that is 
actively working to establish consensus standards, document and share best practices, improve the availability of 
critical bioinformatic tools and resources, and advocate for greater openness, interoperability, accessibility and 
reproducibility in public health microbial bioinformatics. 

In the face of the current SARS-CoV-2 pandemic, [PHA4GE](https://pha4ge.org) has identified a clear and present need 
for a fit-for-purpose, open source SARS-CoV-2 contextual data standard. As such, we have developed an extension to the 
[INSDC](http://www.insdc.org/) pathogen package, providing a SARS-CoV-2 contextual data specification based on 
harmonisable, publicly available, community standards.


## SARS-CoV-2 metadata specification
Public health genomics contextual data includes sample metadata, lab/clinical/epidemiological data, and methods 
information. Contextual data enables the interpretation of the sequence data, informs decision making for public health 
responses, and facilitates scientific understanding of infectious disease. 

Contextual data that are structured and consistent can be more easily understood and processed by both humans and 
computers, and can be more easily aggregated and reused for different types of analyses. Therefore, this specification 
is implementable via a contextual data template package: containing collection template, reference guide, controlled 
vocabulary and mapping to existing standards, as well as an array of protocols and tools to support the harmonisation and 
submission of sequence data and contextual information to public repositories. The specification and all of the 
supporting materials are freely available in this repository.


## Content description

**Table 1:** Resources that form the PHA4GE SARS-CoV-2 contextual data specification package available  in this repository.
| File Name 	| Resource 	| Description 	|  	|
|-	|-	|-	|-	|
| [PHA4GE SARS-CoV-2 Contextual Data Template.xlsx](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20SARS-CoV-2%20Contextual%20Data%20Template%202.1.xlsx) 	| Collection template and controlled vocabulary pick lists 	| Spreadsheet-based collection form containing different fields (identifiers and accessions, sample collection and processing, sequencing, host information, host exposure information, bioinformatics and QC metrics, author acknowledgements). Fields are colour-coded to indicate required, recommended or optional status. Many fields offer pick lists of controlled vocabulary. Vocabulary lists are also available in a separate tab. 	|  	|
| [PHA4GE SARS-CoV-2 Contextual Data Template.xlsx](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20SARS-CoV-2%20Contextual%20Data%20Template%202.1.xlsx)	| Reference guide 	| Field definitions, guidance, and examples are provided as a separate tab in the collection template .xlsx file. 	|  	|
| [PHA4GE Contextual Data SOP 1.0.docx](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20Contextual%20Data%20SOP%201.0.docx)	| Collection template SOP 	| Step-by-step instructions for using the collection template are provided in the SOP. Ethical, practical, and privacy considerations are also discussed. Examples and instructions for structuring sample descriptions as well as sourcing additional standardized terms (outside those provided in pick lists) are also discussed. 	|  	|
| [PHA4GE SARS-CoV-2 Contextual Data Template.xlsx](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20SARS-CoV-2%20Contextual%20Data%20Template%202.1.xlsx) 	| PHA4GE fields to metadata standards mapping 	| PHA4GE fields are mapped to existing metadata standards such as the [Sample Application Standard](https://www.niaid.nih.gov/research/human-pathogen-and-vector-sequencing-metadata-standards), [MIxS 5.0](https://gensc.org/mixs/), and the [MIGS Virus Host-associated attribute package](https://www.ncbi.nlm.nih.gov/biosample/docs/packages/MIGS.eu.host-associated.5.0/). Mappings are available in the Reference guide tab. Mappings highlight which fields of these standards are considered useful for SARS-CoV-2 public health surveillance and investigations, and which fields are considered not applicable. 	|  	|
| [PHA4GE to Sequence Repository Field Mappings.xlsx](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20to%20Sequence%20Repository%20Field%20Mappings%201.0.xlsx) 	| ENA, NCBI and GISAID submission requirements to PHA4GE field mappings 	| Many PHA4GE fields have been sourced from public repository submission requirements. The different repositories have different requirements and field names. Repository submission fields have been mapped to PHA4GE fields to demonstrate equivalencies and divergences. 	|  	|
|  	| Data submission protocol (NCBI) 	| The SARS-CoV-2 submission protocol for NCBI provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
|  	| Data submission protocol (ENA) 	| The SARS-CoV-2 submission protocol for ENA provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
| [PHA4GE SARS-CoV-2 GISAID Submission Protocol](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20SARS-CoV-2%20GISAID%20Submission%20Protocol.pdf) 	| Data submission protocol (GISAID)	| The SARS-CoV-2 submission protocol for GISAID provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
| [PHA4GE_SARS-CoV-2_Contextual_Data_Schema.json](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE_SARS-CoV-2_Contextual_Data_Schema.json) 	| JSON structure of PHA4GE specification 	| A JSON structure of the PHA4GE specification has been provided for easier integration into software applications. 	|  	|

### Collection template and controlled vocabulary pick lists
The PHA4GE SARS-CoV-2 Contextual data Collection Template can be used for data management, and consists a 
spreadsheet-based (.xlsx) collection template, a reference guide, and a controlled vocabulary list. This information 
does not have to be shared, but sharing with public repositories is encouraged when permitted. 

Fields are grouped according to whether they describe sampling, host information (symptoms, exposures etc), sequencing, 
bioinformatics and quality control metrics, etc. The collection template contains "required" (colour-coded yellow), 
"strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields. In many fields, picklists of 
ontology-mapped controlled vocabulary are offered to better standardize data values. 

### Reference guide
To facilitate the use of the collection template, a reference guide with field definitions, further 
guidance/instructions, and examples of structured data is available.

### Collection template SOP
A Standard Operating Procedure (SOP) containing instructions for using the collection template. 

The template SOP provides users with step-by-step instructions for populating the template, looking up standardized 
terms, and how best to structure sample descriptions. The SOP also highlights a number of ethical, practical, and 
privacy considerations for data sharing.

### PHA4GE fields to metadata standards mapping 
Minimum information checklists are community standards that describe attributes of genomes in a standardized way. There are several existing standards that are useful for structuring SARS-CoV-2 contextual data. The PHA4GE SARS-CoV-2 specification implements these standards, and maps to standardized fields where applicable. Mapping of PHA4GE fields to the Sample Application Standard, MIxS v 5.0, and the MIGS Virus Host-associated package can be found in the reference guide. 


### ENA, NCBI and GISAID submission requirements to PHA4GE field mappings
Mapping of the The PHA4GE SARS-CoV-2 Contextual data Collection Template fields to standards and public repository 
submission requirements (NCBI, ENA and GISAID).

### Data submission protocol (NCBI)
The NCBI data submission process is covered by three separate protocols:
* [SARS-CoV-2 NCBI submission protocol: SRA, BioSample, and BioProject](http://dx.doi.org/10.17504/protocols.io.bf7bjrin)
    * Step-by-step instructions for establishing a new NCBI laboratory submission account and for creating and linking a new BioProject to an existing umbrella effort.
    * Submit SARS-CoV-2 raw data to SRA (Sequence Read Archive) and metadata to BioSample.
* [SARS-CoV-2 NCBI assembly submission protocol: GenBank](http://dx.doi.org/10.17504/protocols.io.bg2tjyen)
    * Submit SARS-CoV-2 consensus sequences to NCBI GenBank, linking to existing BioProject, BioSamples, and raw data. 
    * *Required:* established BioProject and BioSamples
* [SOP for populating NCBI submission templates for SARS-CoV-2 (BioSample, SRA, and GenBank)](http://dx.doi.org/10.17504/protocols.io.bf89jrz6)
    * Consult the PHA4GE contextual data specification included on this page **FIRST**, before starting your submission process or populating the templates.
    * This protocol serves and an extra reference to help map the NCBI template fields to the PHA4GE metadata specification, however, the primary PHA4GE guidance should be followed first to ensure the correct controlled vocabulary terms are used to populate the fields. 
    * Guidance included in this protocol: 
        * BioSample metadata template (modified for PHA4GE)
        * SRA metadata template
        * GenBank source modifier template (modified for PHA4GE)

### Data submission protocol (ENA) 
The data submission process is split into three separate protocols. 

* [SOP for populating the three templates for SARS-CoV-2 submission to EBI](https://dx.doi.org/10.17504/protocols.io.bh5dj826)
* [SARS-CoV-2 EBI submission protocol for Biosamples and seqeuence read data](https://dx.doi.org/10.17504/protocols.io.bhwdj7a6)
* [SARS-CoV-2 EBI submission protocol for genome assemblies](https://dx.doi.org/10.17504/protocols.io.bhwqj7dw)

### Data submission protocol (GISAID)
[This protocol](https://github.com/pha4ge/SARS-CoV-2-Contextual-Data-Specification/blob/master/PHA4GE%20SARS-CoV-2%20GISAID%20Submission%20Protocol.pdf) 
provides the steps needed to establish a new GISAID submission environment for your laboratory. Once established,  
this protocol covers genome submission sample metadata to GISAID. 
**The protocol is available in protocols.io under the DOI [dx.doi.org/10.17504/protocols.io.bh98j99w](dx.doi.org/10.17504/protocols.io.bh98j99w).**

### JSON structure of PHA4GE specification
The versioned specification contextual data collection template in machine-amenable JSON format. Due to JSON format 
limitation, it deviates slightly from the collection template where the "required" (colour-coded yellow) fields are 
set as required and both the "strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields 
are both set as option. 

The JSON is produced automatically from the csv version of the template using the [this]() script.

**Table 2** Terms for SARS-CoV-2 submission template according to the PHA4GE contextual data collection specification  
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


