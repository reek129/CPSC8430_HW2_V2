# CPSC8430_HW2_V2 Deep Learning Homework2: Video Caption Generation using S2VT

## To Execute the S2VT, Kindly follow the following steps

1. Clone this repository
2. Change ModelSaveLoc = "SavedModel_reek_v3" in main_execution() function and testmodel() in Main_Exe (Set as default). Models in this version is executed for 100 epochs
3. To get Bleu score for other 50 models in SavedModel_reek_v2. Kindly Update the ModelSaveLoc to "SavedModel_reek_v2".(SavedModel_reek_v2- Models in this folder is executed for 5 epochs) 
4. To ensure the bash file runs only runs the testing phase. Check "__main__" function and ensure train = False, test=True.

## Bleu Score for 42 models are present in final_result.csv

## Top 2 models were trained for 100 epochs
1. model_v2_batchSize_32_hidSize_256_dropPer_0.2_wordDim_2048.h5 (Bleu Score after 5 eps - 0.704488)
2. model_v2_batchSize_32_hidSize_128_dropPer_0.2_wordDim_2048.h5 (Bleu Score after 5 eps - 0.699342)

## Bleu score after 100 eps
1. model_v2_batchSize_32_hidSize_256_dropPer_0.2_wordDim_2048.h5 (Bleu Score after 5 eps - 0.569901)
2. model_v2_batchSize_32_hidSize_128_dropPer_0.2_wordDim_2048.h5 (Bleu Score after 5 eps - 0.6636857)

### Results from the model **model_v2_batchSize_32_hidSize_128_dropPer_0.2_wordDim_2048.h5** is given in **result3_batchSize_32_hidSize_128_dropPer_0.2_wordDim_2048.txt .**

