# Portfolio 5: fMRI Decoding - Group Level Analysis
This repository contains all the code in Portfolio 5: fMRI Decoding - Group Level Analysis. This code was adapted from code provided by Mikkel Wallentin as part of the Advanced Cognitive Neuroscience (F23) at the Cognitive Science MSc, Aarhus University. 

Included in this repository is code used for the group level analysis as well as a the second-level classification completed previously. This classification was done with the goal of descerning trials as instances of either positive or negative emoji presentation.

## Author
Marc Barcelos (MAB), [202302260@post.au.dk](mailto:202302260@post.au.dk)

## This repository contains the following

```

├── README.md
├── setup.sh
├── activate.sh
├── requirements.txt       
├── code    <--- code for replicating analysis
    ├── analysis   
      ├── 14_Nilearn_faceWord_classification_vs4  <--- functions used in analysis
      ├── marc_17_Nilearn_faceWord_classification_searchlight_group  <--- functions used in analysis
```

## Data Organisation
The raw data used when running these scripts cannot be published on GitHub due to GDPR constraints, but all analysis steps are evident in the provided scripts. The data utilized in this study was structured in the following manner, and running the code requires you to have your data organized in the same manner.

````
├── Repository/directory containing the code
├── 816119          <--- fMRI neuroimaging data
│   └── InSpePosNegData    <--- Contains fMRI data in BIDS format
│        └── BIDS_2023E    <--- All BIDS data
├── 835482         <--- Freesurfer output data and labels
│   ├── 0subid     <--- `subid` should be replcaed by subject ID
````
