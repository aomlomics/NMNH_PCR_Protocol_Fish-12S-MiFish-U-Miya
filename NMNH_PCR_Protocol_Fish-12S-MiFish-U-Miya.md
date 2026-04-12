---

# MIOP terms
methodology_category: omics analysis
project: "NOAA Ocean Exploration seawater eDNA metabarcoding"
purpose: PCR [OBI:0000415]
analyses: PCR [OBI:0000415]
geographic_location: Atlantic Ocean [GAZ:00000344], Gulf of Mexico [GAZ:00002853], Pacific Ocean [GAZ:00000360]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: 12S mitochondrial ribosomal RNA  [NCIT:C128263]
creator: Steven Auscavitch, Allen Collins
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], agarose gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 480
personnel_required: 1
language: en
issued: 2025-12-19
audience: scientists
publisher: Smithsonian NMNH
hasVersion: 1.1.3
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
inhibition_check_0_1: 0
inhibition_check: not applicable
thermocycler: Eppendorf Mastercycler Nexus Thermal Cycler
assay_name: Fish-12S-MiFish-U-Miya
assay_validation: not provided
targetTaxonomicAssay: Actinopterygii
targetTaxonomicScope: "Also captures non-target: Vertebrates, bacteria"
target_gene: 12S rRNA (SSU mitochondria)
target_subfragment: V5-V6
ampliconSize: 163-185
pcr_primer_forward: GTCGGTAAAACTCGTGCCAGC
pcr_primer_reverse: CATAGTGGGGTATCTAATCCCAGTTTG
pcr_primer_name_forward: MiFish-U-F
pcr_primer_name_reverse: MiFish-U-R
pcr_primer_reference_forward: http://doi.org/10.1098/rsos.150088
pcr_primer_reference_reverse: http://doi.org/10.1098/rsos.150088
pcr_primer_vol_forward: 0.3
pcr_primer_vol_reverse: 0.3
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
pcr_dna_vol: 1
amplificationReactionVolume: 10
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: 2X KAPA HiFi HotStart ReadyMix (Roche)
custom_mm: not applicable
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
pcr_rep: 3
nucl_acid_amp: # use Zenodo DOI for this repository
pcr_cond: initialdenaturation:95_3;denaturation:98_0.33;annealing:64_0.25;elongation:72_0.5;final elongation:72_1;35
annealingTemp: 64
pcr_cycles: 35
pcr_analysis_software: not provided
pcr_method_additional: not provided
barcoding_pcr_appr: two-step PCR
pcr2_thermocycler: Eppendorf Mastercycler Nexus Thermal Cycler
pcr2_dna_vol: 2
pcr2_amplificationReactionVolume: 25
pcr2_commercial_mm: 2X KAPA HiFi HotStart ReadyMix (Roche)
pcr2_custom_mm: not applicable
pcr2_cond: initialdenaturation:95_3;denaturation:98_0.5;annealing:65_0.25;elongation:72_0.5;final elongation:72_1;5-8
pcr2_annealingTemp: 65
pcr2_cycles: 5-8
pcr2_analysis_software: not provided
pcr2_method_additional: not provided

---

# NMNH PCR Protocol 12S rRNA MiFish (Miya)

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Katie Murphy | Smithsonian NMNH | not provided | 2023-02-10 |
| Allen Collins | Smithsonian NMNH | <https://orcid.org/0000-0002-3664-9691> | not provided |
| Steven Auscavitch | Smithsonian NMNH |  <https://orcid.org/0000-0001-5777-4814> | not provided |
| Luke Thompson | NOAA/AOML, MSU/NGI | <https://orcid.org/0000-0002-3911-1280> | 2025-12-19 |
| Sammy Harding | NOAA/AOML, MSU/NGI | <https://orcid.org/0009-0008-8885-6140> | 2025-12-19 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
- External Protocols: Protcols from manufacturers or other groups. 
- Include the link to each protocol.
- Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| AOML 'Omics Protocols | https://github.com/aomlomics/protocols | not applicable | ongoing |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Qubit™ dsDNA HS Assay Kit | https://documents.thermofisher.com/TFS-Assets/LSG/manuals/Qubit_dsDNA_HS_Assay_UG.pdf | Thermo Fisher Scientific | 2026-01-26 |
| KAPA Pure Beads Manual | https://rochesequencingstore.com/wp-content/uploads/2022/07/KAPA-Pure-Beads-Technical-Data-Sheet.pdf | Roche | 2026-01-26 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-12-19 | Initial release |
| 1.1.0 | 2026-01-05 | Updated protocol with NMNH PCR protocol details |
| 1.1.3 | 2026-04-11 | Updated YAML front matter |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| NMNH | National Museum of Natural History |
| NOAA | National Oceanographic and Atmospheric Administration |
| AOML | Atlantic Oceanographic and Meteorological Laboratory |
| MSU | Mississippi State University |
| NGI | Northern Gulf Institute |
| PCR | Polymerase chain reaction |
| eDNA | environmental DNA |
| NTC | No template control |
| EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty is filter extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water is run in place of DNA on a PCR. |

## BACKGROUND

### Summary

The 12S metabarcoding protocol detailed here is designed to prepare 12S fragments for sequencing on Illumina platforms using a two-step amplification process. This protocol was created and is used by the Smithsonian Institution, National Museum of Natural History.

### Method description and rationale

The first step (amplification PCR) will amplify your region of interest and add an iTru tail. This tail acts as a priming site for the second step (indexing PCR) that will add indices and the Illumina-required adapter to your product. The resulting libraries are dual-indexed and can be sequenced on any Illumina sequencer.

### Spatial coverage and environment(s) of relevance

This protocol is designed such that it can be modified for any organism or gene by using custom primers in place of the 12S primers for the amplification PCR, as long as the primers also contain the appropriate iTru Tail. To modify, replace the 12S forward and 12S reverse portions of the primer (in the case below, MiFish_U_F and MiFish_U_R, respectively) with your specific forward and reverse primers. The indexing primers will remain the same regardless of your study, so you will not need to modify these. 

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used such as wearing PPE to avoid skin or eye contact.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes and programming/running PCR thermal cyclers.

### Time needed to execute the procedure

Protocol takes about 8 hours including thermal cycler run time.

## EQUIPMENT

For 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 100-1000 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.1-2.5 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 uL 8-Channel Pipette |Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| **Consumable equipment** |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| 96-well PCR Plate | Armadillo PCR Plate, 96-well, clear, clear wells | ThermoFisher | 3 | |
| PCR Plate Seal | AlumaSeal II Sealing Foils for PCR and Cold Storage | VWR | 2 | Can be substituted with generic, can use tightly-fitted strip caps in place of seal |
| 1000µL Filter Tips | OT-2 Filter Tips, 1000µL | Opentrons | 1 | (box) Can be substituted with generic |
| 200µL Filter Tips | OT-2 Filter Tips, 200µL | Opentrons | 2 | (boxes) Can be substituted with generic |
| 10 ul Filter tips | TipOne Pipette Tips, 10 uL | TipOne | 2 | (boxes) Can be substituted with generic |
| 2X KAPA HiFi Master Mix | 2X KAPA HiFi Master Mix | Roche | 1.2 | (mL) |
| Molecular water | Invitrogen RT-PCR Grade Water | Fisher Scientific | 0.912 | (mL) |
| Forward Primer - 12S MiFish-U-F| 12S MiFish-U-F | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| Reverse Primer - 12S MiFish-U-R | 12S MiFish-U-R | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| iTru-tailed locus-specific primers | iTru-tailed locus-specific primers |  |  |  |
| Indexing primers (i5 & i7) | Indexing primers (i5 & i7) |  |  |  |
| KAPA Pure Beads | KAPA Pure Beads | Roche |  |  |
| Qubit Reagents | Qubit dsDNA Quantification Assay Kit | Invitrogen | 1 | (kit) |
| Clear Qubit Assay tubes | 0.5 mL thin-walled, polypropylene tubes | Invitrogen | 98 | Must be correct tubes to allow for fluorometer to read concentration |
| **Chemicals** |
| RNase AWAY | RNase AWAY Surface Decontaminant | ThermoFisher Scientific | 1 | (bottle) Used to sterilize lab surfaces and equipment |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Must be molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Protocol

#### Step 1 – Quantification of DNA
Step 1 is not always mandatory, especially if you are amplifying a large number of samples for barcoding (instead of metabarcoding). However, not quantifying may affect amplification success and product concentration.

  1. Quantify your DNA sample(s) using QuBit or Quant-iT.

#### Step 2 – 12S PCR 
This protocol describes the use of triplicate reactions. Please note that your project may require more replicates than this; we strongly suggest you review recent literature when planning your project.

  1. Retrieve reagents from the freezer and allow them to thaw at room temperature. Vortex and spin down.

  2. Perform the initial PCR in triplicate using 10 µL reactions. Follow the recipe below to make your master mix (scale up accordingly). Volumes are given in µL. Mix thoroughly, then spin briefly. 

| Component | Per Reaction (uL) | Final Concentration |
| ----- | ----- | ----- |
| Nuclease-free water | 3.4 | not applicable |
| 2X KAPA HiFi master mix | 5.0 | 1X |
| 12S MiFish-U-F with tail (10 μM) | 0.3 | 0.3 μM |
| 12S MiFish-U-R with tail (10 μM) | 0.3 | 0.3 μM |
| Template DNA | 1.0 | varies |

| PCR Primer Name | Direction | Sequence (5’ -> 3’) | Sequence with iTru tails |
| ----- | ----- | ----- |----|----|
| 12S MiFish-U-F_iTru_HS | forward | GTCGGTAAAACTCGTGCCAGC | ACACTCTTTCCCTACACGACGCTCTTCCGATCT xxx GTCGGTAAAACTCGTGCCAGC |
| 12S MiFish-U-R_iTru_HS | reverse | CATAGTGGGGTATCTAATCCCAGTTTG | GTGACTGGAGTTCAGACGTGTGCTCTTCCGATCT xxx CATAGTGGGGTATCTAATCCCAGTTTG |

  3. Aliquot 9.0 µL of master mix into each PCR tube, then add 1.0 µL of template DNA. Cover plate with a silicone mat, then spin to collect liquid to the bottom of wells.

  4. Place tubes/plate into a thermocycler and run the following program:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 95°C | 3min | 1x |
| Denaturation | 98°C | 20s | 35x |
| Annealing | 64°C | 15s | 35x |
| Extension | 72°C | 30s | 35x |
| Final Extension | 72°C | 1min | 1x |
| Hold | 12°C | ∞ | |

  5. After the PCR finishes, go directly to Step 3, or samples may be stored at 4°C for up to 3 days (or at 20°C for longer periods).

#### Step 3 – Gel verification & Pooling
  1. Prepare a 1.5% agarose gel.

  2. Mix 2 µl PCR product from Step 2 with 2 µl 2X loading dye/10X GelRed. Run gels for 6 minutes at 125V.

  3. Product size should be 275–321 bp for MiFish 12S primers with iTru tails and heterogeneity spacers.

  4. Pool PCR replicates for each sample, omitting any that had incorrect bands present.

  5. Go directly to Step 4, or samples may be stored at 4°C for up to 3 days (or at -20°C for longer periods). 

#### Step 4 – PCR Cleanup with KAPA Pure Beads
Clean up your 12S PCR products using either 1.5X KAPA Pure beads
If you have less than 24 uL per sample, please scale the amount of beads accordingly. If you are using a different locus, you may need to adjust the bead ratio based on your amplicon size.

  1. Remove KAPA Pure beads from the fridge and allow to come to room temperature. While you wait, make fresh 80% Ethanol (you need 450 µl per sample).

  2. Vortex the beads until fully resuspended (~30 seconds).

  3. To 24 µL of PCR product, add 36 µL of KAPA Pure beads (1.5X bead-to-sample ratio).

  4. Mix thoroughly by pipetting up/down at least 10 times.

  5. Incubate at room temperature for 5 minutes to bind the DNA to the beads.

  6. Place the plate/tubes on a magnet for ~3 minutes, or until the supernatant is clear and beads are pelleted.

  7. Carefully remove and discard the supernatant, making sure to not disturb the pellet.

  8. With the plate/tubes still on the magnet, wash the beads by adding 200µL of 80% ethanol. Do not mix.

  9. Incubate at room temp for 30 seconds.

  10. Remove and discard the supernatant.

  11. Repeat the ethanol wash (steps 8-10).

  12. Carefully remove any residual ethanol using a P20 pipette.

  13. Allow beads to air dry for 3 to 5 minutes (not longer!).

  14. Remove the plate from the magnet. Add 22 µL of 10 mM Tris-HCl (pH 8.0) (or TLE: 10 mM Tris-HCl, 0.1 mM EDTA) to each well and use a pipette to fully resuspend the beads.

  15. Incubate the plate at room temperature for 5 minutes.

  16. Place the plate back on the magnet for ~3 minutes, or until the supernatant clears.

  17. Carefully transfer 20 µL of the clear supernatant to a new plate/tube, making sure to not disturb the bead pellet.

  18. After the cleanup, go directly to Step 5, or samples may be stored at 4°C for up to 3 days (or at -20°C for longer periods). 

#### Step 5 – Indexing PCR
  1. Determine which indices will be used for which samples; make sure to record these exactly. Each sample needs an i7 and an i5. a. Make sure you use the indices that match the tails on your locus-specific primers (eg. iTru indices w/ iTru-tailed locus primers).

  2. Thaw the 2X KAPA HiFi master mix and indexing primers. Once thawed, briefly vortex the master mix. Invert the indexing primers ~10 times to mix. Spin briefly.

  3. Set up the following 25 µL PCR reactions.
     a. Remember, your indices are sample-specific, so do NOT include them in your master mix if you choose to make one. 

| Component | Per Reaction (uL) | Final Concentration |
| ----- | ----- | ----- |
| Nuclease-free water | 9.0 | not applicable |
| 2X KAPA HiFi master mix | 12.5 | 1X |
| i7 index (10 μM) | 0.75 | 0.3 μM |
| i5 index (10 μM) | 0.75 | 0.3 μM |
| Template (12S tailored product) | 2.0 | varies |

  4. If using a reaction mix (that includes everything except indices and DNA), pipette 21.5 µL of master mix into each well of your plate (or tubes).

  5. Add 0.75 µL of the required i5 primer (S5xx or i5xx) to each well. Next, add 0.75 µL of the required i7 primer (N7xx or i7xx) to each well.

  6. Lastly, add 2 µL of your template DNA (12S PCR product).
    a. Your total reaction volume in each well should be 25 µL.

  7. Using a P20 or P200 pipette, set to ~15 µL, mix up/down 5 times. Avoid making bubbles.

  8. Seal the plate with a silicone mat or plate seal and spin briefly to collect liquid at the bottom of the wells. 

  9. Place the plate (or tubes) into a thermocycler and run the following indexing program with 5-8 cycles:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 95°C | 3min | 1x |
| Denaturation | 98°C | 30s | 5-8x |
| Annealing | 65°C | 15s | 5-8x |
| Extension | 72°C | 30s | 5-8x |
| Final Extension | 72°C | 1min | 1x |
| Hold | 12°C | ∞ | |

  10. After the PCR finishes, go directly to Step 6, or samples may be stored at 4°C for up to 3 days (or at 20°C for longer periods).

#### Step 6 – Gel verification
  1. Prepare a 1.5% agarose gel.

  2. Mix 2 µl PCR product from Step 6 with 2 µl 2X loading dye/10X GelRed. Run gels for 6 minutes at 125V.

  3. Product size should be 344-384 bp for correctly indexed libraries. A second band at ~275-305 bp indicates that not all of your 12S PCR product was indexed. 

#### Step 7 – PCR Cleanup
Clean up your PCR products using KAPA Pure beads. If you have less than 23 uL per sample, please scale the amount of beads accordingly.

  1. Remove KAPA Pure beads from the fridge and allow to come to room temperature. While you wait, make fresh 80% Ethanol (450 µl per sample).

  2. Vortex the beads until fully resuspended (~30 seconds).

  3. In your indexing PCR plate, add 18 µl of KAPA Pure beads to the ~23 µL of PCR product. This represents a ~0.8X bead-to-sample ratio.
    a. This ratio is dependent upon the size of the product. You can use less for larger products (refer to KAPA Pure manual).

  4. Mix thoroughly by pipetting at least 10 times, until the mixture is homogenous.

  5. Incubate at room temperature for 5 minutes to bind the DNA to the beads.

  6. Place the plate/tubes on a magnet for ~3 minutes, or until the supernatant is clear and beads are pelleted.

  7. Carefully remove and discard the supernatant, making sure to not disturb the pellet.

  8. With the plate/tubes still on the magnet, wash the beads by adding 200 µL of 80% ethanol. Do not mix.

  9. Incubate at room temp for 30 seconds.
  
  10. Remove and discard the supernatant.

  11. Repeat the ethanol wash (steps 8-10).

  12. Carefully remove any residual ethanol using a P20 pipette. Let the plate dry on the magnet for 3-5 minutes.

  13. Remove the plate from the magnet. Add 22 µL of 10 mM Tris-HCl (pH 8.0) (or TLE: 10 mM Tris-HCl, 0.1 mM EDTA) to each well and use a pipette to fully resuspend the beads.

  14. Incubate the plate at room temperature for 5 minutes.

  15. Place the plate back on the magnet for ~3 minutes, or until the supernatant clears.

  16. Carefully transfer 20 µL of the clear supernatant to a new plate/tube.

  17. After the cleanup, go directly to Step 8, or samples may be stored at 4°C for up to 3 days (or at -20°C for longer periods). 

#### Step 8 – Library Quantification & Pooling
  1. Quantify your libraries using the Qubit or Quant-iT HS dsDNA assay kit, following manufacturer’s instructions.

  2. Pool each library to be sequenced in equal ng or equimolar amounts in a new 1.5 mL tube:
    a. If you are using a single gene and all samples will be approximately the same size (such as with 12S or COI), you can pool using ng.
    b. If you are using multiple amplicons that vary in size, you should instead pool in equimolar amounts. 

#### Step 9 – Final Pool QC
  1. Use HS dsDNA Qubit or Quant-iT to measure the concentration (ng/µL) of your library pool.

  2. Determine the molarity (nM) of your pool using the equation given in the “Additional Information” section of this guide.

  3. Run a 1:10 dilution of your pool on a HS D1000 tape or on the Bioanalyzer, to ensure the product is the correct size and no adapter-dimer is present.
    a. Alternatively, you can run 2 uL of your undiluted pool on a 1.5% agarose gel with an appropriate ladder. However, this will not be as sensitive as the Tapestation or Bioanalyzer.

  4. Your pool should be stored at -20°C until submitted for sequencing. 

#### Additional Information
If you need to convert from ng/ul to nM, use the following equation:

$$
\frac{\text{concentration (ng/µL)}}{660 \,\text{g/mol} \times \text{average library size (bp)}} \times 10^{6}
= \text{concentration (nM)}
$$

#### Quality Control

An initial quantification of DNA is performed to ensure product concentration and amplification success. PCR triplicates are used to reduce PCR bias and increase reliability. Initial PCR products are verified using gel electrophoresis followed by a cleanup step. PCR products are indexed and once again verified using gel electrophoresis followed by another cleanup step. Libraries are quantified and pooled. The final pool is quantified and stored at -20°C. 

### Basic troubleshooting guide

Please note, if you use alternative locus-specific primers that include inosines, you must use Taq (such as GoTaq) instead of a high fidelity, proof-reading DNA polymerase. If your primers do not contain inosine, then we recommend using a high fidelity enzyme. Based on our experience, we now recommend using KAPA HiFi over NEB Q5, as KAPA HiFi has shown more consistent amplification. Please make sure to adjust thermocycler conditions accordingly.  

For running these libraries on the MiSeq, we recommend spiking 20% PhiX into your pool due to the low complexity of amplicons, assuming your primers did not include heterogeneity spacers. If your locus-specific primers include heterogeneity spacers, then the PhiX spike-in can be decreased to 1%. 

## REFERENCES

1. Glenn, T. C., R. Nilsen, T. J. Kieran, J. W. Finger Jr., T. W. Pierson, K. E. Bentley, S. L. Hoffberg, S. Louha, F. J. Garcia-De Leon, M. A. D. R. Portilla, K. D. Reed, J. L. Anderson, J. K. Meece, S. E. Aggrey, R. Rekaya, M. Alabady, M. Belanger, K. Winker, and B. C. Faircloth. Adapterama I: Universal stubs and primers for thousands of dual-indexed Illumina libraries (iTru & iNext). Preprint at http://biorxiv.org/content/early/2016/06/15/049114
2. Glenn TC, Pierson TW, Bayona-Vásquez NJ, Kieran TJ, Hoffberg SL, Thomas IV JC, Lefever DE, Finger JW, Gao B, Bian X, Louha S, Kolli RT, Bentley KE, Rushmore J, Wong K, Shaw TI, Rothrock Jr MJ, McKee AM, Guo TL, Mauricio R, Molina M, Cummings BS, Lash LH, Lu K, Gilbert GS, Hubbell SP, Faircloth BC. 2019. Adapterama II: universal amplicon sequencing on Illumina plat- forms (TaggiMatrix). PeerJ 7:e7786 http://doi.org/10.7717/peerj.7786.
3. Miya, M., Y. Sato, T. Fukunaga, T. Sado, J.Y. Poulson, K. Sato, T. Minamoto, S. Yamamoto, H. Yamanaka, H. Araki, M. Kondoh, W. Iwasaki. (2015). MiFish, a set of universal PCR primers for metabarcoding environmental DNA from fishes: detection of more than 230 subtropical marine species. Royal Society Open Science, 2: 150088.
4. Bell, J. (2011). Overview of tailed amplicon sequencing approach with MiSeq. Illumina.
5. KAPA Pure Beads technical data sheet, KR1245 – v3.16. July 2016. 6. Herbold, C.W. et al. (2015). A flexible and economical barcoding approach for highly multiplexed amplicon sequencing of diverse target genes. Front Microbiol. https://doi.org/10.3389/fmicb.2015.00731
6. 16S Metagenomic sequencing library preparation. Illumina part # 15044223 Rev. A.
7. Smithsonian Global ARMS Program – 18S Metabarcoding protocol. 

## APPENDIX A: DATASHEETS

Not applicable.
