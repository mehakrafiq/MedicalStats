## one_way_anova

(0.8980365004751797, 0.40753578189714934)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes     1.185860  0.235848
diabetes vs no_diabetes         0.845129  0.398149

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes  -0.0056 0.6906 -0.0217 0.0104  False
   diabetes pre_diabetes   0.0056 0.8716 -0.0207  0.032  False
no_diabetes pre_diabetes   0.0112 0.4836 -0.0117 0.0341  False
--------------------------------------------------------------

## covariance_analysis

                    sum_sq      df          F    PR(>F)
C(no_diabetes)    0.023249     1.0   1.940618  0.163759
C(pre_diabetes)   0.000013     1.0   0.001092  0.973636
C(diabetes)       0.010910     1.0   0.910639  0.340062
Age               0.144405     1.0  12.053463  0.000528
Residual         23.541422  1965.0        NaN       NaN

## interaction_analysis

                    sum_sq      df          F    PR(>F)
C(no_diabetes)    0.003499     1.0   0.292097  0.588941
C(pre_diabetes)   0.009881     1.0   0.824852  0.363877
C(diabetes)       0.010910     1.0   0.910771  0.340027
Age               0.144405     1.0  12.055211  0.000528
C(diabetes):Age   0.015393     1.0   1.285069  0.257097
Residual         23.526029  1964.0        NaN       NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1827.0  0.247071  0.619205
pre_diabetes  1.0  1837.0  0.370256  0.542940

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  0.998130  0.317764    1
1  pre_diabetes  0.432981  0.510530    1
2      diabetes  0.165497  0.684145    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.010631  0.006496  2.291005e-73
1  pre_diabetes       0.022222  0.007078  3.485672e-11
2      diabetes       0.016393  0.006775  3.834600e-20

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    1.710227  1.045022  0.222302
1  pre_diabetes    0.522099  0.166296  0.234170
2      diabetes    0.706707  0.292054  0.569195

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
3     40-60   No Diabetes       0.000000  1.000000             0.000000
4     40-60  Pre-Diabetes            inf  1.000000                  NaN
5     40-60      Diabetes            inf  1.000000                  NaN
0       60+   No Diabetes       1.204013  0.649817             0.695485
1       60+  Pre-Diabetes       0.666667  0.461612             0.211491
2       60+      Diabetes       1.000772  1.000000             0.412829

## visualize_tukey_results

## plot_interaction_analysis

## visualize_chi_square_results

## visualize_relative_risk_results

## visualize_odds_ratio_results

## visualize_relative_risk_by_age_results

