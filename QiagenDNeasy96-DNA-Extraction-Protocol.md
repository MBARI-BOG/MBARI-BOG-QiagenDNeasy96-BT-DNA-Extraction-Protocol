---
# MIOP terms
methodology_category: sample extraction and purification
project: Marine Biodiversity Observation Network (MBON)
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Monterey Bay [GAZ:00002509]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000033]
environmental_medium: sea water [ENVO:00002149], filter paper [OBI:0000151]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Jacoby Baker https://orcid.org/0000-0002-0673-7535
materials_required: centrifuge [OBI:0400106], incubator [OBI:0000136]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 1320
personnel_required: 1
language: en
issued: 2023-11-07
audience: scientists
publisher: Monterey Bay Aquarium Research Institute, Chavez Lab
hasVersion: 3
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 1000
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: physical
nucl_acid_ext_sep: centrifugation
nucl_acid_ext: # https://files.zymoresearch.com/protocols/_d4302_d4306_d4308_zymobiomics-96_magbead_dna_kit.pdf
nucl_acid_ext_kit: Qiagen DNeasy 96 Blood & Tissue Kit
nucl_acid_ext_modify: # Sterivex was lysed with 1000 uL of ZymoBIOMICS Lysis Solution, use of KingFisher Flex Purification System for bead cleanup and final elution
dna_cleanup_0_1: # 1.0
dna_cleanup_method: # ZymoBIOMICS 96 Magbead DNA Kit
concentration: not applicable
concentration_method: Quant-iT dsDNA Assay Kit High Sensitivity
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# Environmental DNA (eDNA) extraction using Qiagen DNeasy 96 Blood and Tissue Kit V.3

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Jacoby Baker | MBARI | 0000-0002-0673-7535 | 2023-11-07 |
| N. Kobun Truelove | MBARI | 0000-0002-2236-1849 | 2023-11-07 |
| Kathleen J. Pitz | MBARI | 0000-0002-4931-8592 | 2023-11-07 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protcols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| Qiagen DNeasy 96 Blood and Tissue Kit Protocol  | Content Cell | Content Cell | yyyy-mm-dd   | External      |
| Environmental DNA (eDNA) extraction using Quagen DNeasy 96 Blood and Tissue Kit V.3 | https://mbari-bog.github.io/MBON-Protocols/eDNA_extraction_V3.html | Content Cell | yyyy-mm-dd   | Internal      |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | yyyy-mm-dd | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

## BACKGROUND

This document describes the required protocol to conduct [insert name of the method/protocol].

### Summary

This protocol is a modified version of the Qiagen DNeasy 96-sample protocol: Purification of Total DNA from Animal Tissues.

This work was supported by the David and Lucile Packard Foundation, and NASA award 80NSSC21M0032 and NOAA award NA22NOS0120184 in support of the CeNCOOS MBON.

### Method Description and Rationale

This protocol was developed to extract environmental DNA from filtered seawater samples. It has been applied to 0.22μm PVDF and 0.7μm GFF filters.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to extract DNA from filtered sea water samples taken from marine coastal stations.

sea water [ENVO:00002149]
http://purl.obolibrary.org/obo/ENVO_00002149

## PERSONNEL REQUIRED

1 Technician

### Safety

Identify hazards associated with the procedure and specify protective equipment and safety training required to safely execute the procedure

### Training Requirements

Sterile technique, pipetting skills.

### Time Needed to Execute the Procedure

22 hours including an overnight incubation.

## EQUIPMENT

- Opentrons Consumables: If using Opentrons OT-2 Robot for KF Plate Prep.
- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| incubator | Gyromax 702 | Amerex instruments | 1 |  |
| centrifuge | Sorvall Legend XTR centrifuge | Thermo scientific | 1 |  |
| **Consumable equipment** |
| Qiagen DNeasy 96 Blood & Tissue Kit | Qiagen DNeasy 96 Blood & Tissue Kit | Qiagen |  |  |
| **Chemicals** |
| ethanol (96-100%) | Content Cell | Content Cell |  |  |
| RNase Away | RNase Displace | FoxWest sales |  | CAT# 1401 |
| EtOH wash | 70% ethanol |  |  |  |
| NF H20 | Nuclease-Free water | Invitrogen |  | CAT# AM9932 |

## STANDARD OPERATING PROCEDURE

In the following SOP, please use the exact names of equipment as noted in the table above.

Provide a step-by-step description of the protocol. The identification of difficult steps in the protocol and the provision of recommendations for the execution of those steps are encouraged.

### Preparation

**Important points before starting (from the original Qiagen DNeasy 96 Blood and Tissue Kit Protocol)**

- If using the DNeasy 96 Blood & Tissue Kit for the first time, read “Important Notes” (page 15).
- All centrifugation steps are carried out at room temperature (15–25°C).
- Optional: RNase Away may be used to digest RNA during the procedure. RNase A is not provided in the DNeasy 96 Blood & Tissue Kit (see “Copurification of RNA”, page 19).

**Things to do before starting**

- Buffer AL should be premixed with ethanol before use. Add 90 ml ethanol (96–100%) to the bottle containing 86 ml Buffer AL or 260 ml ethanol to the bottle containing 247 ml Buffer AL and shake thoroughly. Mark the bottle to indicate that ethanol has been added. (Please note that, for purification of DNA from animal blood, Buffer AL must be used without ethanol. Buffer AL can be purchased separately if the same kit will be used for purification of DNA from animal blood.)
- Buffer AW1 and Buffer AW2 are supplied as concentrates. Before using for the first time, add the appropriate amount of ethanol (96–100%) as indicated on the bottle to obtain a working solution.
- Buffer ATL and Buffer AL may form precipitates upon storage. If necessary, warm to 56°C for 5 min until the precipitates have fully dissolved.
- Mix Buffer AW1 before use by inverting several times.
- Preheat an incubator to 56°C for use in step 4.
- If using frozen tissue, equilibrate the sample to room temperature. Avoid repeated thawing and freezing of samples since this will lead to reduced DNA size.

**Pre-procedure**

0.1	Organize a 96-well sample layout spreadsheet to identify which samples are in each well location. Don’t forget to include extraction blanks (EB; x1), PCR blanks (x2), and artificial communities (x1)
0.2	Preheat incubator to 56°C for later use
0.3	Place clean and sterile 3 or 5 mm TissueLyser beads into each of the collection microtubes.

**Note:** Be sure to label your plates along the plate skirt.


### Extraction

1.  Place eDNA water filters into the collection microtubes. Be sure to have an organization chart to identify location of each sample in the 96-well-plate format.

    **Note:** Use a plate template sheet to organize the location of the samples, blanks, and artificial community. Using two pairs of forceps, carefully roll the filter into a ‘tube’ shape so that it can fit within the collection microtube. When placing the rolled filter into the tube, make sure the eDNA filter residue is facing the inner portion of the tube so the bead can pass and properly lyse the material. It helps to keep the filter to the top of the collection microtube as the diameter is larger and the bead can more easily pass. 

    **IMPORTANT:** Between each filter, be sure to clean and sterilize forceps with a RNase away, 2X NF H2O, and EtOH wash. 

    Keep the clear covers from the collection microtube racks for use in step 3.

2. Prepare a proteinase K-Buffer ATL working solution containing 30 μl proteinase K stock solution and 270 μl Buffer ATL per sample, and mix by vortexing (we increased the overall volume to 300 μl so the filter would be submerged in the proteinase K-Buffer ATL working solution). For a set of 96 samples, use 3 ml proteinase K stock solution and 27 ml Buffer ATL (this has a 4-sample buffer for errors in pipetting). Pipette 300 μl working solution into each collection microtube containing the eDNA filter samples. Seal the microtubes securely using the caps provided.

    **Note:** Move each column of tubes to a new box before uncapp9ng and adding the proteinase K-Buffer ATL working solution. This is done to help prevent cross contamination between samples when uncapping the tubes after the filters are loaded. After the prot. K-ATL solution is added cap tubes with new caps. 

    **Note:** Check Buffer ATL for precipitate. If necessary, dissolve the precipitate by incubation at 56°C for 5 min before preparing the working solution.

    **IMPORTANT:** After preparation, the proteinase K–Buffer ATL working solution should be dispensed immediately into the collection microtubes containing the tail or tissue samples. Incubation of the working solution in the absence of substrate for >30 min reduces lysis efficiency and DNA purity.

    2.5. Bead beat the microtubes in the bead beater at 30hz for 2 minutes. 
    **Note:** Make sure that the bead beater is balanced.

3. Ensure that the microtubes are properly sealed to avoid leakage during shaking. Place a clear cover (saved from step 1) over each rack of collection microtubes, and mix by inverting the rack of collection microtubes. To collect any solution from the caps, centrifuge the collection microtubes. Allow the centrifuge to reach 3000 rpm, and then stop the centrifuge. It is essential that the samples are completely submerged in the proteinase K–Buffer ATL working solution after centrifugation.

	If the proteinase K–Buffer ATL working solution does not completely cover the sample, increase the volume of the solution to 300 μl per sample (additional reagents are available separately; see page 56 for ordering information). Do not increase volumes above 300 μl as this will exceed the capacity of the collection microtubes in subsequent steps.

	Keep the clear covers from the collection microtube racks for use in step 5.

4. Incubate at 56°C overnight or until the samples are completely lysed. Place a weight on top of the caps during the incubation. Mix occasionally during incubation to disperse the sample, or place on a rocking platform.

	After incubation the lysate may appear viscous, but should not be gelatinous as it may clog the DNeasy 96 membrane. If the lysate appears very gelatinous, see the “Troubleshooting Guide”, page 47, for recommendations.

	**Note:** It is important to make sure there is a weight or something holding the lids of the caps down as the head builds pressure in the collection microtubes and can lift the caps off of the tubes, potentially releasing DNA and cross-contaminating samples.

	**Note:** Do not use a rotary- or vertical-type shaker as continuous rotation may release the caps. If incubation is performed in a water bath make sure that the collection microtubes are not fully submerged and that any remaining water is removed prior to centrifugation in step 5.

5. Ensure that the microtubes are properly sealed to avoid leakage during shaking. Place a clear cover over each rack of collection microtubes and shake the racks vigorously up and down for 15 s. To collect any solution from the caps, centrifuge the collection microtubes. Allow the centrifuge to reach 3000 rpm, and then stop the centrifuge.

	**IMPORTANT:** The rack of collection microtubes must be vigorously shaken up and down with both hands to obtain a homogeneous lysate. Inverting the rack of collection microtubes is not sufficient for mixing. The genomic DNA will not be sheared by vigorous shaking. 

	Ensure that lysis is complete before proceeding to step 6. The lysate should be homogeneous following the vigorous shaking. To check this, slowly invert the rack of collection microtubes (making sure that the caps are tightly closed) and look for a gelatinous mass. If a gelatinous mass is visible, lysis needs to be extended by adding another 100 μl Buffer ATL and 15 μl proteinase K, and incubating for a further 3 h. It is very important to ensure that samples are completely lysed to achieve optimal yields and to avoid clogging of individual wells of the DNeasy 96 plate.

6. Carefully remove the caps. Add 615 μl premixed Buffer AL–ethanol to each sample. For a 96-well plate, aliquot out 61.5 ml of Buffer AL-ethanol from the stock bottle to use for the 96 samples plus a 4-sample buffer for error.

	**Note:** Ensure that ethanol has been added to Buffer AL prior to use (see “Buffer AL”, page 18).

	**Note:** A white precipitate may form upon addition of Buffer AL–ethanol to the lysate. It is important to apply all of the lysate, including the precipitate, to the DNeasy 96 plate in step 9. This precipitate does not interfere with the DNeasy procedure or with any subsequent application.

7. Ensure that the microtubes are properly sealed to avoid leakage during shaking. Place a clear cover over each rack of collection microtubes and shake the racks vigorously up and down for 15 s. To collect any solution from the caps, centrifuge the collection microtubes. Allow the centrifuge to reach 3000 rpm, and then stop the centrifuge.

	Do not prolong this step.

	**IMPORTANT:** The rack of collection microtubes must be vigorously shaken up and down with both hands to obtain a homogeneous lysate. Inverting the rack of collection microtubes is not sufficient for mixing. The genomic DNA will not be sheared by vigorous shaking. The lysate and Buffer AL–ethanol should be mixed immediately and thoroughly to yield a homogeneous solution.

8. Place two DNeasy 96 plates on top of S-Blocks (provided). Mark the DNeasy 96 plates for later sample identification.

9. Remove and discard the caps from the collection microtubes. Carefully transfer the lysate (transfer a maximum of 800 μl of lysate so the flow-through doesn’t come in contact with the bottom of the spin column) of each sample from step 7 to each well of the DNeasy 96 plates.

	Take care not to wet the rims of the wells to avoid aerosols during centrifugation. Do not transfer more than 800 μl per well.

	**Note:** Lowering pipet tips to the bottoms of the wells may cause sample overflow and cross-contamination. Therefore, remove one set of caps at a time, and begin drawing up the samples as soon as the pipet tips contact the liquid. Repeat until all the samples have been transferred to the DNeasy 96 plates.

	**Note:** If the volume of proteinase K–Buffer ATL working solution was increased in steps 3 or 5, transfer no more than 800 μl of the supernatant from step 7 to the DNeasy 96 plate. Larger amounts will exceed the volume capacity of the individual wells. Discard any remaining supernatant from step 7 as this will not contribute significantly to the total DNA yield.

10. Seal each DNeasy 96 plate with an AirPore Tape Sheet (provided). Centrifuge for 10 min at 4700 rpm (our centrifuge cannot reach 6000 rpm).

	AirPore Tape prevents cross-contamination between samples during centrifugation. After centrifugation, check that all of the lysate has passed through the membrane in each well of the DNeasy 96 plates. If lysate remains in any of the wells, centrifuge for a further 10 min.

11. Remove the tape. Carefully add 500 μl Buffer AW1 to each sample.

	**Note:** Ensure that ethanol has been added to Buffer AW1 prior to use. It is not necessary to increase the volume of Buffer AW1 if the volume of proteinase K–Buffer ATL working solution was increased in steps 3 or 5.

12. Seal each DNeasy 96 plate with a new AirPore Tape Sheet (provided). Centrifuge for 5 min at 4700 rpm.

13. Remove the tape. Carefully add 500 μl Buffer AW2 to each sample.

	**Note:** Ensure that ethanol has been added to Buffer AW2 prior to use.

	It is not necessary to increase the volume of Buffer AW2 if the volume of proteinase K–Buffer ATL working solution was increased in steps 3 or 5.

14. Centrifuge for 15 min at 4700 rpm.
  Do not seal the plate with AirPore Tape.
  The heat generated during centrifugation ensures evaporation of residual ethanol in the sample (from Buffer AW2) that might otherwise inhibit downstream reactions.

    14.5. If there is still liquid in the spin-column or flow-through touching the bottom of the spin column, repeat the drying step (Centrifuge for an additional 10 minutes at 4700 rpm.)

15. Place each DNeasy 96 plate in the correct orientation on a new rack of Elution Microtubes RS (provided).

16. To elute the DNA, add 100 μl Buffer AE to each sample, and seal the DNeasy 96 plates with new AirPore Tape Sheets (provided). Incubate for 1 min at room temperature (15–25°C). Centrifuge for 3 min at 4700 rpm.

17. After DNA is eluted, transfer 50 μl into a new skirted 96-well plate (what we have been using for bead clean-ups) and seal with the heat sealer, and label plate for archiving (plate_name  archive DNA  date).

18. Transfer the remaining DNA into a second new skirted 96-well plate. This aliquot will be used for further lab work. Label plate (plate_name  lab DNA  date).

### Quality Control

Total DNA is quantified using a Quant-iT kit on a plate reader.

### Basic Troubleshooting Guide

- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

- Qiagen Inc., November 2023 DNeasy Blood and Tissue Handbook; available online from Qiagen Inc.


## APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
