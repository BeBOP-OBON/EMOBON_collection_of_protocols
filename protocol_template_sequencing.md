# Protocol Template

MIOP protocol template

## Minimum Information about an Omics Protocol (MIOP)

See https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml for list and definitions.

| MIOP Term  | Value |
| ------------- | ------------- | 
| methodology category  |  |
| project  |  |
| purpose  |  |
| analyses  |  |
| geographic location  |  |
| broad-scale environmental context  |  |
| local environmental context  |  |
| environmental medium  |  |
| target  |  |
| creator  |  |
| materials required  |  |
| skills required  |  |
| time required  |  |
| personnel required  |  |
| language  |  |
| issued  |  |
| audience  |  |
| publisher  |  |
| hasVersion  |  |
| license  |  |
| maturity level  |  |

## AUTHORS

| PREPARED BY All authors known to have contributed to the preparation of this protocol, including those who filled in the template.  | AFFILIATION | ORCID (visit https://orcid.org/ to register) | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | Content Cell | yyyy-mm-dd |
| Content Cell  | Content Cell  | Content Cell | yyyy-mm-dd |

## PROTOCOL REVISION RECORD

Version numbers start at "1.0.0" when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0). Please store all versions in the gDrive folder designated to your institute.

| VERSION  | RELEASE DATE This is the date when a given protocol version was finalised | DESCRIPTION OF REVISIONS Please include a brief description of what was changed relative to the previous version |
| ------------- | ------------- | ------------- |
| 1.0.0  | 2023-02-15  | Initial release  |
| Content Cell  | Content Cell  | Content Cell  |

## RELATED PROTOCOLS IN YOUR FOLDER

This is a list of other protocols deposited in your folder which should be known to users of this protocol. For example, if you create a derivative or altered protocol, you would link to the original protocol in the section below. Please include the link to each related protocol. Also include the version number of that protocol when you linked to it.

| PROTOCOL NAME AND LINK  | VERSION The version of the protocol you linked to | RELEASE DATE This is the date corresponding to the version listed to the left |
| ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | yyyy-mm-dd  |
| Content Cell  | Content Cell  | yyyy-mm-dd  |

## RELATED EXTERNAL PROTOCOLS

This is a list of other protocols that are not in your folder which should be known to users of this protocol. These include, e.g., kit manuals. Please upload all relevant external protocols to Appendix A and link to them here.

| EXTERNAL PROTOCOL NAME AND LINK  | ISSUER / AUTHOR Please note who authored the protocol (this may also be a company name) | ACCESS DATE This is the date you downloaded or scanned the protocol and uploaded it. |
| ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | yyyy-mm-dd  |
| Content Cell  | Content Cell  | yyyy-mm-dd  |

## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |

## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

# BACKGROUND

This document describes the required protocol to conduct insert name of the method/protocol.

## Summary

Sequencing will be performed at a centralized sequencing facility to reduce biases as much as
possible. The Water Column WaSOP1 and the Soft sediment samples for microorganisms will be
analysed using metagenomics. All other samples will be analysed using DNA metabarcoding
methodologies. Samples and analyses details are summarized in the Table below.


| Protocol | Sample | Analyses|Details|Primer references|
| ----- | ----- | ----- | ----- | ----- |
| WaSOP 1 | Microorganisms (3 um fraction) | Metagenomes |150 bp fragments, paired reads, 50 M reads per sample | |
| WaSOP 1 | Microorganisms (0.2 um fraction) | Metagenomes |150 bp fragments, paired reads, 50 M reads per sample | |
| WaSOP 1 | Microorganisms (3 um fraction) | Metabarcodes |ITS amplicon, paired reads, 1 M reads per sample per amplicon |ITS1F (Bruns and Gardes, 1993) and ITS2 (White et al., 1990) |
| WaSOP 1 | Microorganisms (0.2 um fraction) | Metabarcodes |ITS amplicon, paired reads, 1 M reads per sample per amplicon |ITS1F (Bruns and Gardes, 1993) and ITS2 (White et al., 1990) |
| WaSOP 2 | Plankton >20 um | Metabarcodes |18S v4 region, COI amplicon, paired reads, 1 M reads per sample per amplicon |18S v4 region: to be decided, COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| WaSOP 3 | Plankton >200 um | Metabarcodes |18S v4 region, COI amplicon, paired reads, 1 M reads per sample per amplicon |18S v4 region: to be decided, COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| SoSOP 1, SoSOP 2, SoSOP 3 | Microorganisms | Metagenomes |150 bp fragments, paired reads, 1 M reads per sample | |
| SoSOP 1, SoSOP 2, SoSOP 3 | Meiobenthos | Metabarcodes |18S v1-v2 region, COI amplicon, paired reads, 50 M reads per sample per amplicon |18S v1-v2 region: SSU_FO4 (Fonseca et al., 2010) and SSU_R22 (Blaxter et al., 1998) or SSU_R22mod (Sinniger et al., 2016), COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| SoSOP 1, SoSOP 2, SoSOP 3 | Macrobenthos | Metabarcodes |18S v1-v2 region, COI amplicon, paired reads, 50 M reads per sample per amplicon |18S v1-v2 region: SSU_FO4 (Fonseca et al., 2010) and SSU_R22 (Blaxter et al., 1998) or SSU_R22mod (Sinniger et al., 2016), COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| HaSOP | Sessile fraction | Metabarcodes |18S v1-v2 region, COI amplicon, paired reads, 1 M reads per sample per amplicon |18S v1-v2 region: SSU_FO4 (Fonseca et al., 2010) and SSU_R22 (Blaxter et al., 1998) or SSU_R22mod (Sinniger et al., 2016), COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| HaSOP | Motile 0.5 mm fraction | Metabarcodes |18S v1-v2 region, COI amplicon, paired reads, 1 M reads per sample per amplicon |18S v1-v2 region: SSU_FO4 (Fonseca et al., 2010) and SSU_R22 (Blaxter et al., 1998) or SSU_R22mod (Sinniger et al., 2016), COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |
| HaSOP | Motile 0.1 mm fraction | Metabarcodes |18S v1-v2 region, COI amplicon, paired reads, 1 M reads per sample per amplicon |18S v1-v2 region: SSU_FO4 (Fonseca et al., 2010) and SSU_R22 (Blaxter et al., 1998) or SSU_R22mod (Sinniger et al., 2016), COI: mlCOIintF and jgHCO2198 (Leray et al., 2013) |







# STANDARD OPERATING PROCEDURE

In the following SOP, please use the exact names of equipment as noted in the table above.

## Protocol

Provide a step-by-step description of the protocol. The identification of difficult steps in the protocol and the provision of recommendations for the execution of those steps are encouraged.

Preparation

Please specify the preparatory actions you took before you collected the samples and note what equipment was needed to do so (e.g. disinfection of work surfaces, preparations to the equipment you intend to use later on).

1.  Step 1
2.  Step 2

### Sequencing

Please specify the actions you took to sequence the DNA and note what equipment was needed to do so (loading of sequencing machine, details about the sequencing run, sequencing institution (if out of house), sequencing primers used).

1. Step 1

| Sequencing Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| content | forward | content |
| content | reverse | content |


2. Step 2

    a. Sub-step a

    b. Sub-step b

## Quality control

Describe and explain criteria used to validate results of the standard operating procedure.

## Basic troubleshooting guide

Identify known issues associated with the procedure, if any.
Provide troubleshooting guidelines when available.

# REFERENCES

Insert all references cited in the document.
Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1

# APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
