# Experiment Data of Paper: Identifying Unreliable Inferences in DNN-Based Image Classification

This page hosts the data of FSE20 Paper 104:  **Identifying Unreliable Inferences in DNN-Based Image Classification**



**Please note the file is in csv (comma-separated values) format, although the file extension is .txt.** 

If we provide the file with extension .csv, google chrome will download it as '.xls' and could cause trouble when opening the file. 




Section 5.1: Effectiveness of Our Approach:

1. the result of manual check for each sample (table 1),  [here](csv_file/1_manual_check_result.txt).




Section 5.2: Pervasiveness of Unreliable Inferences: 

1. the reproduced accuracy for each images by 18 models (table 2), [here](csv_file/2.1_model_actual_accuracy_each_image.txt) (In csv file, "TRUE" for correct classification)

2. the unreliable inferences violating MR-1(table 2), [here](csv_file/2.2_model_actual_MR1_each_image.txt) (In csv file, "TRUE" for correct classification)
3. the unreliable inferences violating MR-2, [here](csv_file/2.3_model_actual_MR2_each_image.txt) (In csv file,"TRUE" for unreliable)



Section 5.3: Effect of Unreliable Inferences: 

1. the comparison of the top-1 accuracy between the unreliable inferences and reliable Inferences for 18 models (figure 6), [here](csv_file/3_effect.txt)




Section 5.4: Effect of Unreliable Inferences: 

1. the top-1 accuracy and the ratio of unreliable inferences of VGG16/Resnet50 during training (figure 8), [here](csv_file/4_trained_model_results.txt)



Section 6.1: Characteristic of Unreliable Inferences:

1. the ratio of unreliable inferences with respect to the ratio of target object size for 18 models (figure 10),  [here](csv_file/5_obj_size.txt)



Section 6.2: The Impact of The Number of Colors in Our Approach

1. The comparison between using 3 colors and 15 colors (Table 3), [here](csv_file/6_number_of_colors.txt) (In csv file,"TRUE" for unreliable)

