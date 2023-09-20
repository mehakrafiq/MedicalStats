# Fall

## one_way_anova

(1.4643342192622864, 0.23153759978231395)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -0.555115  0.578905
diabetes vs no_diabetes         1.514273  0.130175

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes  -0.0246 0.2753 -0.0623  0.013  False
   diabetes pre_diabetes  -0.0343 0.2765 -0.0869 0.0183  False
no_diabetes pre_diabetes  -0.0097 0.8532  -0.052 0.0326  False
--------------------------------------------------------------

## covariance_analysis

                    sum_sq      df          F        PR(>F)
C(no_diabetes)    0.011188     1.0   0.229682  6.318241e-01
C(pre_diabetes)   0.177769     1.0   3.649425  5.626495e-02
C(diabetes)       0.000176     1.0   0.003611  9.520910e-01
Age               1.493078     1.0  30.651394  3.596536e-08
Residual         78.912761  1620.0        NaN           NaN

## interaction_analysis

                    sum_sq      df          F        PR(>F)
C(no_diabetes)    0.017135     1.0   0.351690  5.532407e-01
C(pre_diabetes)   0.006443     1.0   0.132232  7.161761e-01
C(diabetes)       0.000176     1.0   0.003610  9.520961e-01
Age               1.493078     1.0  30.644867  3.608764e-08
C(diabetes):Age   0.031916     1.0   0.655066  4.184263e-01
Residual         78.880845  1619.0        NaN           NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1487.0  1.244325  0.264819
pre_diabetes  1.0  1494.0  0.667353  0.414106

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  0.403132  0.525476    1
1  pre_diabetes  0.335191  0.562618    1
2      diabetes  2.145101  0.143026    1

## relative_risk_analysis

      condition  relative_risk        ci        p_value
0   no_diabetes       0.052541  0.040615  1.035193e-111
1  pre_diabetes       0.041916  0.019678   1.000719e-16
2      diabetes       0.080569  0.049155   8.429676e-24

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    1.208431  0.934136  0.440194
1  pre_diabetes    1.356310  0.636739  0.588334
2      diabetes    0.635542  0.387741  0.109079

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.000000  1.000000             0.000000
7     18-40  Pre-Diabetes            inf  1.000000                  NaN
8     18-40      Diabetes            inf  1.000000                  NaN
3     40-60   No Diabetes       0.215686  0.139687             0.132523
4     40-60  Pre-Diabetes            inf  0.249417                  NaN
5     40-60      Diabetes       1.725888  1.000000             0.237267
0       60+   No Diabetes       1.069065  0.787161             0.780846
1       60+  Pre-Diabetes       1.287564  0.703456             0.599491
2       60+      Diabetes       0.785994  0.427497             0.470413

## visualize_tukey_results

![visualize_tukey_results](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\visualize_tukey_results.png)

## plot_interaction_analysis

![plot_interaction_analysis](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\plot_interaction_analysis.png)

## visualize_chi_square_results

![visualize_chi_square_results](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\visualize_chi_square_results.png)

## visualize_relative_risk_results

![visualize_relative_risk_results](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\visualize_relative_risk_results.png)

## visualize_odds_ratio_results

![visualize_odds_ratio_results](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\visualize_odds_ratio_results.png)

## visualize_relative_risk_by_age_results

![visualize_relative_risk_by_age_results](D:\OneDrive - National University of Sciences & Technology\Desktop\upwork\MedicalStats\Plots\visualize_relative_risk_by_age_results.png)

