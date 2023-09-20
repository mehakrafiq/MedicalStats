## one_way_anova

(4.82574790276262, 0.008115810254152204)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes     2.022218  0.043314
diabetes vs no_diabetes         2.725927  0.006473

## tukey_hsd

      Multiple Comparison of Means - Tukey HSD, FWER=0.05      
===============================================================
   group1      group2    meandiff p-adj   lower   upper  reject
---------------------------------------------------------------
   diabetes  no_diabetes  -0.0323 0.0214 -0.0608 -0.0038   True
   diabetes pre_diabetes   0.0007 0.9993  -0.046  0.0474  False
no_diabetes pre_diabetes    0.033 0.1371 -0.0076  0.0736  False
---------------------------------------------------------------

## covariance_analysis

                    sum_sq      df          F        PR(>F)
C(no_diabetes)    0.271295     1.0   7.245741  7.167223e-03
C(pre_diabetes)   0.000031     1.0   0.000830  9.770127e-01
C(diabetes)       0.000456     1.0   0.012181  9.121306e-01
Age               0.970519     1.0  25.920568  3.897258e-07
Residual         73.573635  1965.0        NaN           NaN

## interaction_analysis

                    sum_sq      df          F        PR(>F)
C(no_diabetes)    0.008189     1.0   0.218635  6.401336e-01
C(pre_diabetes)   0.007906     1.0   0.211072  6.459795e-01
C(diabetes)       0.000456     1.0   0.012176  9.121458e-01
Age               0.970519     1.0  25.911570  3.915407e-07
C(diabetes):Age   0.011907     1.0   0.317913  5.729287e-01
Residual         73.561727  1964.0        NaN           NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1827.0  1.318136  0.251077
pre_diabetes  1.0  1837.0  1.336032  0.247885

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  8.782065  0.003042    1
1  pre_diabetes  1.884536  0.169819    1
2      diabetes  5.245366  0.022005    1

## relative_risk_analysis

      condition  relative_risk        ci        p_value
0   no_diabetes       0.033288  0.025043  1.030113e-121
1  pre_diabetes       0.069767  0.035497   5.685542e-15
2      diabetes       0.068966  0.043837   3.030091e-31

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    2.079197  1.564185  0.003453
1  pre_diabetes    0.561294  0.285579  0.112728
2      diabetes    0.525297  0.333900  0.024722

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
6     18-40   No Diabetes       0.000000  1.000000             0.000000
7     18-40  Pre-Diabetes            inf  1.000000                  NaN
8     18-40      Diabetes            inf  1.000000                  NaN
3     40-60   No Diabetes       2.108232  0.387517             1.048029
4     40-60  Pre-Diabetes       0.564202  0.461066             0.076857
5     40-60      Diabetes       0.486735  0.299528             0.118618
0       60+   No Diabetes       1.398959  0.217526             1.004492
1       60+  Pre-Diabetes       0.756952  0.514446             0.368094
2       60+      Diabetes       0.768717  0.361797             0.475810

## visualize_tukey_results

## plot_interaction_analysis

## visualize_chi_square_results

## visualize_relative_risk_results

## visualize_odds_ratio_results

## visualize_relative_risk_by_age_results

