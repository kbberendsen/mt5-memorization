# Unmasking Memorization: Assessing Dutch Language Memorization in mT5 Models

This repository consists of the files used for my Master's thesis. The study assesses the level of Dutch Language memorization in mT5 language models. All pre-processing and analysis scripts can be found here, along with the thesis document.

**Data and Results**
- The input data used in this study is in the 'data' folder. Here, the masked data is also stored.
- The results after filling in the masks using the mT5 models are in the 'results' folder.

**Code**
- The 'code' folder contains the scripts for data pre-processing, model inference, and analysis.
- The 'baseline_preprocessing' and 'unique_preprocessing' scripts are used to clean the respective data.
- The 'mask_data' script masks the data for the all context lengths, and stores the masked sequences in the 'data' folder.
- The 'fill_masks' script presents the masked sequences to the models and stores the results in the 'result' folder.
- The 'combine_results' script is used to combine all results (spanning various model sizes and context lengths) into a single file for unique and duplicate sequences. This makes analysis more convenient.

**Analysis**
- The 'analysis' folder within the 'code' folder contains the script used to analyze the results. The figures in the thesis are also generated in this script.

