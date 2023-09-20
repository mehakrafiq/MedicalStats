# Length of Stay

## one_way_anova

(0.9804963262174998, 0.37562241493259874)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -1.192965  0.233364
diabetes vs no_diabetes        -0.916063  0.360015

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes   0.8009 0.6264 -1.2386 2.8403  False
   diabetes pre_diabetes  -0.2548 0.9685  -2.737 2.2274  False
no_diabetes pre_diabetes  -1.0557 0.4269 -3.0465 0.9352  False
--------------------------------------------------------------

## covariance_analysis

                       sum_sq     df          F        PR(>F)
C(no_diabetes)    2868.129942    1.0  36.732559  2.180621e-09
C(pre_diabetes)    180.216994    1.0   2.308065  1.291413e-01
C(diabetes)        199.693709    1.0   2.557507  1.102085e-01
Age                708.767816    1.0   9.077293  2.678384e-03
Residual         56452.858037  723.0        NaN           NaN

## interaction_analysis

                       sum_sq     df         F    PR(>F)
C(no_diabetes)     508.678231    1.0  6.505730  0.010958
C(pre_diabetes)     60.076626    1.0  0.768349  0.381020
C(diabetes)        199.693709    1.0  2.553979  0.110454
Age                708.767816    1.0  9.064772  0.002697
C(diabetes):Age      0.209645    1.0  0.002681  0.958718
Residual         56452.648392  722.0       NaN       NaN

## interaction_analysis2

              dfn    dfd         F    PR(>F)
diabetes      1.0  592.0  2.293735  0.130431
pre_diabetes  1.0  591.0  1.855286  0.173689

## chi_square_test

      condition       chi2   p_value  dof
0   no_diabetes  64.301417  0.047453   47
1  pre_diabetes  64.222865  0.048109   47
2      diabetes  41.792422  0.687531   47

## relative_risk_analysis

      condition  relative_risk        ci   p_value
0   no_diabetes       1.076923  0.738343  0.350188
1  pre_diabetes       3.333333  1.582604  0.000768
2      diabetes       1.562500  0.834262  0.081664

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    0.714938  0.593385  0.031987
1  pre_diabetes    1.537114  1.095458  0.025383
2      diabetes    1.080547  0.769942  0.703309

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.794643  0.795721             0.537455
7     18-40  Pre-Diabetes       1.298246  1.000000             0.357295
8     18-40      Diabetes       1.151515  1.000000             0.232416
3     40-60   No Diabetes       0.313679  0.000230             0.221602
4     40-60  Pre-Diabetes       3.256962  0.002607             1.596812
5     40-60      Diabetes       1.863636  0.130015             0.903721
0       60+   No Diabetes       0.704751  0.100438             0.530357
1       60+  Pre-Diabetes       1.426923  0.151667             0.943673
2       60+      Diabetes       1.125352  0.638117             0.753698

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

