# INTENSIV

## one_way_anova

(3.15687361398527, 0.04282036093459741)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -0.350940  0.725687
diabetes vs no_diabetes         2.407163  0.016201

## tukey_hsd

      Multiple Comparison of Means - Tukey HSD, FWER=0.05      
===============================================================
   group1      group2    meandiff p-adj   lower   upper  reject
---------------------------------------------------------------
   diabetes  no_diabetes  -0.0723 0.0418 -0.1425 -0.0021   True
   diabetes pre_diabetes  -0.0839 0.1102 -0.1819   0.014  False
no_diabetes pre_diabetes  -0.0116 0.9363 -0.0905  0.0673  False
---------------------------------------------------------------

## covariance_analysis

                     sum_sq      df          F        PR(>F)
C(no_diabetes)     0.091594     1.0   0.543174  4.612272e-01
C(pre_diabetes)    0.191544     1.0   1.135894  2.866804e-01
C(diabetes)        0.497617     1.0   2.950975  8.601685e-02
Age                5.932331     1.0  35.179961  3.667465e-09
Residual         273.177588  1620.0        NaN           NaN

## interaction_analysis

                     sum_sq      df          F        PR(>F)
C(no_diabetes)     0.238919     1.0   1.416832  2.341000e-01
C(pre_diabetes)    0.010870     1.0   0.064462  7.996106e-01
C(diabetes)        0.497617     1.0   2.950963  8.601763e-02
Age                5.932331     1.0  35.179814  3.668181e-09
C(diabetes):Age    0.167487     1.0   0.993229  3.191035e-01
Residual         273.010101  1619.0        NaN           NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1487.0  0.895513  0.344141
pre_diabetes  1.0  1494.0  1.895021  0.168843

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  2.067123  0.150505    1
1  pre_diabetes  0.351943  0.553015    1
2      diabetes  5.761593  0.016380    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.270270  0.235668  1.769542e-78
1  pre_diabetes       0.251799  0.173810  1.522366e-13
2      diabetes       0.398773  0.299129  1.838587e-10

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    1.225166  1.068312  0.145959
1  pre_diabetes    1.147302  0.791954  0.562277
2      diabetes    0.671907  0.504013  0.015875

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.538462  1.000000             0.384313
7     18-40  Pre-Diabetes            inf  1.000000                  NaN
8     18-40      Diabetes       0.906977  1.000000             0.109193
3     40-60   No Diabetes       0.698662  0.348284             0.531350
4     40-60  Pre-Diabetes       1.326162  0.692342             0.598770
5     40-60      Diabetes       1.452632  0.657151             0.570047
0       60+   No Diabetes       1.089078  0.633392             0.907074
1       60+  Pre-Diabetes       1.266088  0.374043             0.827025
2       60+      Diabetes       0.765486  0.138509             0.560760

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

