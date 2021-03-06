# The Neuroscience of Program Comprehension

## Stimuli
### Python (Experiment 1)
All stimuli related to our Python experiments (Experiment 1) are available in `./stimuli/python/`.

We have made available stimuli pertaining to the three conditions we test in our work -
- `EN`: Codes with variable names in English.
- `SENT`: English descriptions of these codes.
- `JAP`: Codes with obfuscated variable names.

We have shared three files corresponding to these conditions, each containing all 108 stimuli, as well as three folders each containing individual files for the 108 stimuli across the three conditions. The stimuli vary by problem content (math vs. string manipulation) and problem structure (sequential/for loop/if statement), yielding 6 problem types in total. Note that only 72 stimuli (the first 12 for each of the 6 problem types) were used in the study.

### ScratchJr (Experiment 2)
The stimuli used in the ScratchJr experiment (Experiment 2) are available in `./stimuli/scratchjr/`. Each folder item contains the `.png` image of the code snippet, two videos (match and mismatch; only one of the videos was shown to each participant), and the audio of the sentence describing the video (the audio was not used for the current experiment).

## Data

We make available the data we used for statistical analyses and plotting:
- behavioral responses
- responses to conditions of interest within MD and language fROIs (`data_fROI*`)
- responses to conditions of interest within parcels defined using the code problems > sentence problems contrast (`data_GSS`)
- voxelwise spatial correlation between responses in language fROIs (`data_spcorr`)

Original `.nii` files are available upon request.

## Analyses

We provide the R code that was used for statistical analyses and plot generation. 

## Parcels

We make available the brain parcels used to define functional systems of interest (MD and language). The parcels were defined using the [GcSS method](https://www.ncbi.nlm.nih.gov/pubmed/20410363) using previously collected data from 197 (MD) and 220 (language) participants.
