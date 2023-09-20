# TOD

## one_way_anova

(0.11305435281558858, 0.8931091575009511)

## t_test

                             t_statistic   p_value
pre_diabetes vs no_diabetes     0.207233  0.835858
diabetes vs no_diabetes         0.457008  0.647734

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj   lower  upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes  -0.0033 0.8925 -0.0206 0.0139  False
   diabetes pre_diabetes  -0.0017 0.9856 -0.0257 0.0224  False
no_diabetes pre_diabetes   0.0017 0.9776 -0.0177  0.021  False
--------------------------------------------------------------

## covariance_analysis

                    sum_sq      df          F    PR(>F)
C(no_diabetes)    0.000105     1.0   0.010157  0.919735
C(pre_diabetes)   0.001375     1.0   0.133317  0.715065
C(diabetes)       0.001661     1.0   0.161025  0.688268
Age               0.109964     1.0  10.660925  0.001117
Residual         16.709734  1620.0        NaN       NaN

## interaction_analysis

                    sum_sq      df          F    PR(>F)
C(no_diabetes)    0.008930     1.0   0.865713  0.352284
C(pre_diabetes)   0.010301     1.0   0.998646  0.317788
C(diabetes)       0.001661     1.0   0.161016  0.688276
Age               0.109964     1.0  10.660342  0.001117
C(diabetes):Age   0.009402     1.0   0.911466  0.339868
Residual         16.700333  1619.0        NaN       NaN

## interaction_analysis2

              dfn     dfd         F    PR(>F)
diabetes      1.0  1487.0  1.514718  0.218615
pre_diabetes  1.0  1494.0  0.003360  0.953784

## chi_square_test

      condition      chi2   p_value  dof
0   no_diabetes  0.027188  0.869032    1
1  pre_diabetes  0.000000  1.000000    1
2      diabetes  0.006323  0.936620    1

## relative_risk_analysis

      condition  relative_risk        ci       p_value
0   no_diabetes       0.009917  0.005616  3.026706e-57
1  pre_diabetes       0.011628  0.002885  1.887110e-10
2      diabetes       0.013333  0.004268  5.481528e-14

## odds_ratio_analysis

      condition  odds_ratio        ci   p_value
0   no_diabetes    1.269941  0.719196  0.584596
1  pre_diabetes    0.898955  0.223027  0.702596
2      diabetes    0.759768  0.243206  0.721688

## relative_risk_by_age

  age_group     condition  relative_risk   p_value  confidence_interval
3     40-60   No Diabetes       3.838710  0.373045             0.539253
4     40-60  Pre-Diabetes            inf  1.000000                  NaN
5     40-60      Diabetes       0.097561  0.173371             0.013412
0       60+   No Diabetes       0.702281  0.784150             0.386691
1       60+  Pre-Diabetes       0.992568  1.000000             0.245226
2       60+      Diabetes       1.714074  0.748373             0.425370

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

