## one_way_anova

(6.971915634681189, 0.0009612194624364825)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes     1.960218  0.050138
diabetes vs no_diabetes         3.412616  0.000657

## tukey_hsd

      Multiple Comparison of Means - Tukey HSD, FWER=0.05      
===============================================================
   group1      group2    meandiff p-adj   lower   upper  reject
---------------------------------------------------------------
   diabetes  no_diabetes  -2.1231 0.0018 -3.5758 -0.6705   True
   diabetes pre_diabetes  -0.4649 0.8912 -2.8503  1.9206  False
no_diabetes pre_diabetes   1.6582 0.1457 -0.4141  3.7306  False
---------------------------------------------------------------

## covariance_analysis

                        sum_sq      df          F        PR(>F)
C(no_diabetes)     1369.748629     1.0  13.958758  1.921967e-04
C(pre_diabetes)    1090.330705     1.0  11.111281  8.739724e-04
C(diabetes)        2555.044820     1.0  26.037808  3.670537e-07
Age                1365.798990     1.0  13.918508  1.963265e-04
Residual         192822.030289  1965.0        NaN           NaN

## interaction_analysis

                        sum_sq      df          F        PR(>F)
C(no_diabetes)       67.434382     1.0   0.686978  4.072948e-01
C(pre_diabetes)     254.953155     1.0   2.597299  1.072067e-01
C(diabetes)        2555.044820     1.0  26.029157  3.686976e-07
Age                1365.798990     1.0  13.913884  1.968095e-04
C(diabetes):Age      34.070902     1.0   0.347092  5.558314e-01
Residual         192787.959387  1964.0        NaN           NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1827.0  0.533876  0.465075
pre_diabetes  1.0  1837.0  2.156656  0.142125

## chi_square_test

      condition       chi2   p_value  dof
0   no_diabetes  88.129727  0.016262   62
1  pre_diabetes  72.794754  0.164202   62
2      diabetes  76.744911  0.098440   62

## relative_risk_analysis

      condition  relative_risk        ci   p_value
0   no_diabetes       1.013636  0.841389  0.443329
1  pre_diabetes       1.222222  0.506481  0.327631
2      diabetes       1.576923  0.964744  0.034624

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    1.562437  1.412080  0.000041
1  pre_diabetes    0.559216  0.397725  0.001377
2      diabetes    0.735729  0.588608  0.015501

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.893462  1.000000             0.717395
7     18-40  Pre-Diabetes       0.956175  1.000000             0.086703
8     18-40      Diabetes       1.199597  1.000000             0.232739
3     40-60   No Diabetes       1.744865  0.023910             1.453073
4     40-60  Pre-Diabetes       0.275778  0.002005             0.122781
5     40-60      Diabetes       0.893918  0.775392             0.526506
0       60+   No Diabetes       1.184561  0.212791             1.020048
1       60+  Pre-Diabetes       0.831081  0.409930             0.564656
2       60+      Diabetes       0.889526  0.466115             0.692559

## visualize_tukey_results

## plot_interaction_analysis

## visualize_chi_square_results

## visualize_relative_risk_results

## visualize_odds_ratio_results

## visualize_relative_risk_by_age_results

