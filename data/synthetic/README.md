# Synthetic Data

This directory stores a range of categories of synthetic data.  The data have known ground truth labels, known noise characteristics, and known-and-wide-ranging signal-to-noise-ratios (SNRs). These labels and properties are kept hidden from the participants.  We anticipate having about 5 to ten categories of synthetic data, and each with 3-10 draws.  

This collection will therefore reach up to ~50 individual synthetic spectral specimens.  We therefore have a system for organizing these specimens.  

We group the experiments into **lessons** and within the lessons are the different **specimens**.

We have a disciplined naming convention for organization:

`sub_directory/filename.csv`

The `sub_directory` name will describe the model grid used, such as `01_sonora_bobcat_2018`.  We anticipate more models, such as the PHOENIX stellar models. 


Within that directory, each `filename` composed of two pieces.  The word `lesson` with a running letter suffix `_A`, `_B`, etc is concatenated with a zero-padded running number suffix for each **specimen**: `01`, `02`, etc.:


`lesson_A-specimen01.csv`

