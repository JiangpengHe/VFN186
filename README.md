# VFN186 Food Image Datasets [IEEE Transaction on MultiMedia 2025] 

This repository contains the **VFN186 food image dataset** that is introduced in **Long-Tailed Continual Learning For Visual Food Recognition** 

The full dataset can be downloaded [[here]](https://drive.google.com/file/d/1Exi8Mw62nF8vS44HkvOwlybrRxqIFauY/view)


### Dataset Structure:
VFN186
    - cropped_new (contains all single food images for the 186 food classes)
        - Each subfolder is named as [food type] == [label]
    - full_data_list.txt (the full list of the original VFN186 data)
    - new_food_list_186_cf.xlsx (the spreadsheet contains the 186 food type with the corresponding matched FNDDS food code and their food consumption frequency values for healthy, type-1 diabetes, and type-2 diabetes)
    - train_test_files (contains the simulated "long-tailed" train and test files for each population)
    
