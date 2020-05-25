**Directions for Help:**

1.Section 4 in report on ‘Proposed Methodology’ is made from *Preprocessing_&_Feature_Extraction.ipynb notebook 
    Input : Alert and Drowsy Videos 
    Output:Label+features* 
       1.1) 6_Participants_ In_First_Zip_File.csv 
       1.2) 5_Participants_In_Fourth_Zip_File.csv
       1.3) 6_Participants_In _Third _Zip_File.csv
       1.4) 5_Participants_In _Second_Zip_File.csv
  All four files were used to create Merged_data.csv 
  
2.Section 4.4 in report on ‘Feature Normalization’ is made *from Normalization.ipynb notebook 
   *Input:Merged_data.csv 
   *Output:
        2.1) final_with_main_features.csv
        2.2) total_with_all_information.csv
        
3.Section 7.1 in report on ‘Basic Classification Models’ is made from Classification_models.ipynb notebook 
   *Input:final_with_main_features.csv
   *Output:*
        3.1)   3.1.1) accuracy
               3.1.2) f1 score
               3.1.3) confusion matrix 
               3.1.4) ROC
        3.2)   3.2.1) ROC Curves
               3.2.2) Calibration Curves
               3.3.3) Comparison of ROC curves
               3.3.4) Comparison of calibration curve
                  
4.Section 7.3 in report on ‘Long Short Term Memory Networks’ is made from LSTM.ipynb
   *Input: final_with_main_features.csv
   *Output:* 
        4.1) ROC Curve
        4.2) Calibration Curve
        
5.For Main_Code.ipynb notebook 
   *Input: final_with_main_features
    Additional File Used: Shape_Predictor.dat
    Output:* 
        5.1)Live results - Alert or Drowsy
        5.2)Curve for state(Alert or drowsy) with frames   .

**OverLeaf Link**: https://www.overleaf.com/project/5e7c5e9b6be44f00017314c6
**Prior Work (Research Paper) Link** : https://arxiv.org/pdf/1904.07312.pdf
