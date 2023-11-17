**************************
Contributors: <br /> 
Da Gong, University of California, Riverside <br /> 
Andong Yan, University of California, Riverside <br /> 
Qi Zhang, Autonomous University of Barcelona <br /> 
*************************
risk_level_cleaned_1215.csv is the cleaned risk level dataset. 

Our data starts from April 2 2021, ends on Dec 15, 2022. The official data reporting ends on Dec 26, 2022, we have the raw data but have not cleaned it yet (the data format in the last ten days is super tricky). 

risk_exp_county is the indicator that determines if the county is classified as a Risk region or not at that day. 

risk_cum_county is the cumulative days of the county being a Risk region since April 02, 2021.

risk_exp_pref is the indicator that  determines if any county within this prefecture is classified as a Risk region or not on that day. 

risk_prop_pref is the proportion of counties within this prefecture classified as a Risk region on that day. 

If you want to generate your own treatment variable, you can use high_risk, mid_risk and low_risk. just keep in mind that there are 4 adjustment to the criteria of high/mid/ low risk (it's recorded in the readme.txt)

You want to use the shapfiles (county.shp and pref.shp) to identify the geographic location. (Notes: Shapefiles are not included due to storage limitations on GitHub. However, they are publicly available on the internet. Alternatively, you can reach me via email.)

**If you plan to use the COVID risk level dataset in your research, we kindly request that you cite our work:** 

Gong, Da and Shang, Zhuocheng and Su, Yaqin and Yan, Andong and Zhang, Qi, Economic Impacts of China’s Zero-COVID Policies (April 17, 2023). Available at SSRN: https://ssrn.com/abstract=4422902 or http://dx.doi.org/10.2139/ssrn.4422902
