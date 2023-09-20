# INTENSIV

## one_way_anova

(3.746942910153029, 0.024048467532678093)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -2.595849  0.009671
diabetes vs no_diabetes        -1.354127  0.176224

## tukey_hsd

      Multiple Comparison of Means - Tukey HSD, FWER=0.05      
===============================================================
   group1      group2    meandiff p-adj   lower   upper  reject
---------------------------------------------------------------
   diabetes  no_diabetes   0.0545 0.3409 -0.0369   0.146  False
   diabetes pre_diabetes   -0.045 0.6084 -0.1563  0.0662  False
no_diabetes pre_diabetes  -0.0996 0.0243 -0.1888 -0.0103   True
---------------------------------------------------------------

## covariance_analysis

                     sum_sq     df          F    PR(>F)
C(no_diabetes)     1.990572    1.0  12.930456  0.000345
C(pre_diabetes)    0.838493    1.0   5.446720  0.019878
C(diabetes)        0.186975    1.0   1.214559  0.270798
Age                3.588729    1.0  23.311842  0.000002
Residual         111.301856  723.0        NaN       NaN

## interaction_analysis

                     sum_sq     df          F    PR(>F)
C(no_diabetes)     0.445286    1.0   2.888733  0.089632
C(pre_diabetes)    0.180942    1.0   1.173835  0.278976
C(diabetes)        0.186975    1.0   1.212972  0.271111
Age                3.588729    1.0  23.281383  0.000002
C(diabetes):Age    0.008532    1.0   0.055353  0.814064
Residual         111.293324  722.0        NaN       NaN

## interaction_analysis2

              dfn    dfd          F    PR(>F)
diabetes      1.0  592.0  13.449835  0.000267
pre_diabetes  1.0  591.0   6.145323  0.013454

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  6.071548  0.013738    1
1  pre_diabetes  4.967108  0.025834    1
2      diabetes  0.449428  0.502607    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.298246  0.239080  3.934949e-27
1  pre_diabetes       0.149606  0.092379  5.671478e-15
2      diabetes       0.212389  0.136716  2.724899e-12

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    0.600735  0.481562  0.010307
1  pre_diabetes    1.851012  1.142962  0.020211
2      diabetes    1.214730  0.781925  0.477656

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.000000  0.222316             0.000000
7     18-40  Pre-Diabetes            inf  0.615694                  NaN
8     18-40      Diabetes            inf  1.000000                  NaN
3     40-60   No Diabetes       0.402797  0.030049             0.271220
4     40-60  Pre-Diabetes       2.131200  0.194096             0.836333
5     40-60      Diabetes       2.087121  0.242547             0.733741
0       60+   No Diabetes       0.545927  0.015453             0.399131
1       60+  Pre-Diabetes       1.971024  0.034082             1.115899
2       60+      Diabetes       1.225234  0.577482             0.748689

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

