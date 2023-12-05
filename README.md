# SOC-estimation-of-EV
 Dataset and SoC Estimation:
   - Utilized Mendeley dataset with voltage, current, and temperature for lithium-ion batteries.
   - The dataset can be found here : https://data.mendeley.com/datasets/cp3473x7xv/3
   - Applied CNN for SoC estimation, optimizing model with preprocessing for diverse conditions.

Model Architecture:
   - Designed CNN with one convolutional layer, 32 filters, and regression output for EV applications.
   - Compiled model with Adam optimizer, learning rate 0.001, emphasizing precision in SoC prediction.

 Results:
   - Achieved low 2.12% MAE on 80% training, 20% validation split.
   - Visualized loss curves, comparing predicted vs. actual SoC values on a test dataset.
   
