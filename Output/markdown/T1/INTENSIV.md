## one_way_anova

(86.5721391611755, 9.259718233695341e-37)

## t_test

                             t_statistic       p_value
pre_diabetes vs no_diabetes    12.757937  1.258457e-35
diabetes vs no_diabetes         6.245474  5.241195e-10

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj  lower   upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes  -0.1505   0.0 -0.2082 -0.0928   True
   diabetes pre_diabetes   0.2813   0.0  0.1865  0.3761   True
no_diabetes pre_diabetes   0.4318   0.0  0.3494  0.5142   True
--------------------------------------------------------------

## covariance_analysis

                     sum_sq      df          F        PR(>F)
C(no_diabetes)    14.630002     1.0  95.540816  4.569106e-22
C(pre_diabetes)   14.434538     1.0  94.264342  8.452236e-22
C(diabetes)        0.093749     1.0   0.612224  4.340459e-01
Age                5.915543     1.0  38.631290  6.234122e-10
Residual         300.897095  1965.0        NaN           NaN

## interaction_analysis

                     sum_sq      df          F        PR(>F)
C(no_diabetes)     2.599886     1.0  16.972527  3.949902e-05
C(pre_diabetes)    4.805437     1.0  31.370771  2.431906e-08
C(diabetes)        0.093749     1.0   0.612009  4.341265e-01
Age                5.915543     1.0  38.617746  6.277311e-10
C(diabetes):Age    0.047658     1.0   0.311122  5.770561e-01
Residual         300.849437  1964.0        NaN           NaN

## interaction_analysis2

              dfn     dfd           F        PR(>F)
diabetes      1.0  1827.0  118.820373  7.539529e-27
pre_diabetes  1.0  1837.0   16.887620  4.140445e-05

## chi_square_test

      condition        chi2       p_value  dof
0   no_diabetes  113.410717  1.754044e-26    1
1  pre_diabetes  122.580339  1.722955e-28    1
2      diabetes   19.558994  9.754045e-06    1

## relative_risk_analysis

      condition  relative_risk        ci        p_value
0   no_diabetes       0.193878  0.169180  2.080494e-123
1  pre_diabetes       1.464286  1.042473   1.390660e-02
2      diabetes       0.455399  0.358201   6.745662e-11

## odds_ratio_analysis

      condition  odds_ratio        ci       p_value
0   no_diabetes    3.432205  2.994986  2.827400e-24
1  pre_diabetes    0.157987  0.112476  1.023375e-23
2      diabetes    0.543190  0.427255  1.643965e-05

## relative_risk_by_age

  age_group     condition  relative_risk       p_value  confidence_interval
6     18-40   No Diabetes       1.333333  5.584261e-01             0.906793
7     18-40  Pre-Diabetes            inf  1.000000e+00                  NaN
8     18-40      Diabetes       0.495575  4.343373e-01             0.059663
3     40-60   No Diabetes       2.855407  1.089806e-04             2.221443
4     40-60  Pre-Diabetes       0.145989  1.232623e-06             0.070910
5     40-60      Diabetes       0.777846  4.636832e-01             0.410198
0       60+   No Diabetes       2.688042  3.795673e-12             2.240085
1       60+  Pre-Diabetes       0.201637  4.108963e-14             0.135992
2       60+      Diabetes       0.712401  3.582389e-02             0.547667

## visualize_tukey_results

## plot_interaction_analysis

## visualize_chi_square_results

## visualize_relative_risk_results

## visualize_odds_ratio_results

## visualize_relative_risk_by_age_results

