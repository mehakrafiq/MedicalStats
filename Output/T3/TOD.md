# TOD

## one_way_anova

(1.0303050016944557, 0.3574207647988519)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -1.330839  0.183758
diabetes vs no_diabetes        -0.703101  0.482275

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes   0.0102 0.7294 -0.0214 0.0417  False
   diabetes pre_diabetes  -0.0077 0.8837 -0.0462 0.0307  False
no_diabetes pre_diabetes  -0.0179 0.3592 -0.0487 0.0129  False
--------------------------------------------------------------

## covariance_analysis

                    sum_sq     df         F    PR(>F)
C(no_diabetes)    0.033947    1.0  1.817329  0.178054
C(pre_diabetes)   0.054862    1.0  2.936990  0.087001
C(diabetes)       0.023785    1.0  1.273322  0.259519
Age               0.186076    1.0  9.961448  0.001665
Residual         13.505355  723.0       NaN       NaN

## interaction_analysis

                    sum_sq     df         F    PR(>F)
C(no_diabetes)    0.006768    1.0  0.361837  0.547677
C(pre_diabetes)   0.015116    1.0  0.808112  0.368979
C(diabetes)       0.023785    1.0  1.271565  0.259848
Age               0.186076    1.0  9.947703  0.001677
C(diabetes):Age   0.000045    1.0  0.002408  0.960877
Residual         13.505310  722.0       NaN       NaN

## interaction_analysis2

              dfn    dfd         F    PR(>F)
diabetes      1.0  592.0  3.351329  0.067653
pre_diabetes  1.0  591.0  4.740166  0.029861

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  1.164645  0.280504    1
1  pre_diabetes  0.780601  0.376957    1
2      diabetes  0.009101  0.923999    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.025404  0.013964  1.241839e-33
1  pre_diabetes       0.006897  0.000965  3.530818e-07
2      diabetes       0.014815  0.003667  1.677546e-09

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    0.421753  0.231831  0.268285
1  pre_diabetes    3.318662  0.464335  0.322613
2      diabetes    1.401384  0.346916  1.000000

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
3     40-60   No Diabetes       0.000000  0.534410             0.000000
4     40-60  Pre-Diabetes            inf  1.000000                  NaN
5     40-60      Diabetes            inf  1.000000                  NaN
0       60+   No Diabetes       0.327928  0.139730             0.167924
1       60+  Pre-Diabetes       3.626812  0.307414             0.505428
2       60+      Diabetes       1.721612  0.737849             0.424302

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

