# Unmasking Memorization: Assessing Dutch Language Memorization in mT5 Models

This repository consists of the files used for my Master's thesis. The study assesses the level of Dutch Language memorization in mT5 language models. All pre-processing and analysis scripts can be found here, along with the thesis document.

**Data and Results**
- The input data used in this study is in the [data folder](https://github.com/kbberendsen/mt5-memorization/tree/main/data). Here, the masked data is also stored.
- The results after filling in the masks using the mT5 models are in the [results folder](https://github.com/kbberendsen/mt5-memorization/tree/main/results/working_results).

**Code**
- The [code folder](https://github.com/kbberendsen/mt5-memorization/tree/main/code) contains the scripts for data pre-processing, model inference, and analysis.
- The [baseline_preprocessing](https://github.com/kbberendsen/mt5-memorization/blob/main/code/baseline_preprocessing.ipynb) and [unique_preprocessing](https://github.com/kbberendsen/mt5-memorization/blob/main/code/unique_preprocessing.ipynb) scripts are used to clean the respective data.
- The [mask_data](https://github.com/kbberendsen/mt5-memorization/blob/main/code/mask_data.ipynb) script masks the data for the all masking levels, and stores the masked sequences in the 'data' folder.
- The [fill_mask](https://github.com/kbberendsen/mt5-memorization/blob/main/code/fill_mask.ipynb) script presents the masked sequences to the models and stores the results in the 'results' folder.
- The [combine_results](https://github.com/kbberendsen/mt5-memorization/blob/main/code/combine_results.ipynb) script is used to combine all results (spanning various model sizes and masking levels) into a single file for unique and duplicate sequences. This step makes analysis more convenient.

**Analysis**
- The [analysis folder](https://github.com/kbberendsen/mt5-memorization/tree/main/code/analysis) within the 'code' folder contains the script used to analyze the results. The figures in the thesis are also generated in this script.

