# MatPlotLib-Challenge
The data from this study presents the results of 249 mice with SCC tumors (Skin Cancer) treated with various drug regimens by Pymaceuticals, which specializes in anti-cancer medications. Over a 45-day period, Capomulin was tested against other regimens, revealing three main observations:

1. The summary statistics indicate that Capomulin and Ramicane are the most effective in reducing tumor volume, with mean volumes of 40.68 and 40.22, respectively, and low standard deviations (4.99 for Capomulin and 4.85 for Ramicane). In contrast, Ketapril had the highest mean tumor volume of 55.24 and the largest variability (standard deviation of 8.28), with Naftisol following closely behind. This suggests that Capomulin and Ramicane provide the most consistent and reliable tumor reduction.

2. When investigating tumor volume outliers for Capomulin, Ramicane, Infubinol, and Ceftamin, it was found that Infubinol had a clear outlier at 72.23, significantly larger than other values in that regimen. Capomulin, Ramicane, and Ceftamin showed potential outliers at 30.49, 32.98 (low), 43.05 (high), and 45.00 (low), respectively, reflecting some deviations in tumor responses across treatments.

3. A positive correlation between mouse weight and tumor volume was observed, with mouse ID-1509 showing a correlation coefficient of 0.84, indicating that larger mice tend to have larger tumors, which could provide additional insights into the dosage or effectiveness of treatments based on weight.s.lts.
## Dependencies
![image](https://github.com/user-attachments/assets/9ca32f6a-5baf-4ded-9221-acab1051a327)
## Resources
Import, read and merge the resources
![image](https://github.com/user-attachments/assets/6f3328d8-9a1c-492f-a095-b9e828f55ec6)
## Summary Statistics
Statistical Analysis
![image](https://github.com/user-attachments/assets/733cb60d-add6-4a9c-a876-001a6ae94ec6)
A bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using Pandas.
![image](https://github.com/user-attachments/assets/7ce8418b-7acc-46fd-b290-0a4e4ac66323)
A bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using PyPlot.
![image](https://github.com/user-attachments/assets/349e2728-f3bb-44de-a6c7-571ad3b33198)
A pie chart, using Pandas, showing the distribution of unique female versus male mice used in the study
![image](https://github.com/user-attachments/assets/03182ac2-40aa-44b8-8d8e-4c3e312b7b28)
A pie chart, using PyPlot, showing the distribution of unique female versus male mice used in the study
![image](https://github.com/user-attachments/assets/a6753acd-bbf0-4a1c-8abb-4eb0ab13bd77)
A box plot that shows the distribution of the tumor volume for each treatment group.
![image](https://github.com/user-attachments/assets/e7d47cb6-d499-4fcc-8e4e-68fc4f990625)
The correlation between mouse weight and the average tumor volum
![image](https://github.com/user-attachments/assets/238bc406-52f3-46d7-8780-078472202751)
