# Fall

## one_way_anova

(0.5230749166852501, 0.5929190671787293)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes    -0.726222  0.467992
diabetes vs no_diabetes         0.531399  0.595346

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes  -0.0106  0.846 -0.0555 0.0344  False
   diabetes pre_diabetes  -0.0237 0.5666 -0.0784  0.031  False
no_diabetes pre_diabetes  -0.0131 0.7618 -0.0571 0.0308  False
--------------------------------------------------------------

## covariance_analysis

                    sum_sq     df          F    PR(>F)
C(no_diabetes)    0.003846    1.0   0.101597  0.750014
C(pre_diabetes)   0.097127    1.0   2.565825  0.109632
C(diabetes)       0.001891    1.0   0.049958  0.823200
Age               0.434580    1.0  11.480422  0.000741
Residual         27.368437  723.0        NaN       NaN

## interaction_analysis

                    sum_sq     df          F    PR(>F)
C(no_diabetes)    0.011929    1.0   0.314789  0.574930
C(pre_diabetes)   0.008896    1.0   0.234767  0.628158
C(diabetes)       0.001891    1.0   0.049904  0.823294
Age               0.434580    1.0  11.468074  0.000746
C(diabetes):Age   0.008426    1.0   0.222358  0.637391
Residual         27.360011  722.0        NaN       NaN

## interaction_analysis2

              dfn    dfd         F    PR(>F)
diabetes      1.0  592.0  1.052675  0.305311
pre_diabetes  1.0  591.0  0.039203  0.843115

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  0.000000  1.000000    1
1  pre_diabetes  0.392241  0.531124    1
2      diabetes  0.251606  0.615946    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.042254  0.026366  8.613046e-40
1  pre_diabetes       0.028169  0.010428  9.571320e-13
2      diabetes       0.053846  0.025170  2.540453e-14

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    0.957108  0.597222  1.000000
1  pre_diabetes    1.596223  0.590935  0.484284
2      diabetes    0.719316  0.336239  0.467380

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
3     40-60   No Diabetes       0.339726  0.419222             0.138951
4     40-60  Pre-Diabetes            inf  0.602938                  NaN
5     40-60      Diabetes       0.969697  1.000000             0.132506
0       60+   No Diabetes       0.769231  0.668110             0.438033
1       60+  Pre-Diabetes       1.559701  0.616056             0.572632
2       60+      Diabetes       0.958647  1.000000             0.419528

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

