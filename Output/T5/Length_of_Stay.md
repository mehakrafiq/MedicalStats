# Length of Stay

## one_way_anova

(1696.1217694096001, 0.0)

## t_test

                             t_statistic        p_value
pre_diabetes vs no_diabetes    53.479249   0.000000e+00
diabetes vs no_diabetes       -34.933000  1.958167e-194

## tukey_hsd

     Multiple Comparison of Means - Tukey HSD, FWER=0.05      
==============================================================
   group1      group2    meandiff p-adj  lower   upper  reject
--------------------------------------------------------------
   diabetes  no_diabetes     -0.0   1.0 -0.3769  0.3769  False
   diabetes pre_diabetes   10.408   0.0  9.8821  10.934   True
no_diabetes pre_diabetes   10.408   0.0  9.9847 10.8314   True
--------------------------------------------------------------

## covariance_analysis

                       sum_sq      df            F         PR(>F)
C(no_diabetes)    5308.355656     1.0  1070.123555  1.226134e-180
C(pre_diabetes)  15073.977254     1.0  3038.797545   0.000000e+00
C(diabetes)       1728.105803     1.0   348.372801   1.419433e-70
Age                  6.006990     1.0     1.210963   2.713050e-01
Residual          8036.021746  1620.0          NaN            NaN

## interaction_analysis

                      sum_sq      df           F         PR(>F)
C(no_diabetes)    606.910737     1.0  122.279719   1.873995e-27
C(pre_diabetes)  4560.405459     1.0  918.825563  3.096822e-160
C(diabetes)      1728.105803     1.0  348.176890   1.552798e-70
Age                 6.006990     1.0    1.210282   2.714399e-01
C(diabetes):Age     0.441617     1.0    0.088977   7.655206e-01
Residual         8035.580129  1619.0         NaN            NaN

## interaction_analysis2

              dfn     dfd             F  PR(>F)
diabetes      1.0  1487.0  2.852815e+03     0.0
pre_diabetes  1.0  1494.0  3.004882e-26     1.0

## chi_square_test

      condition         chi2        p_value  dof
0   no_diabetes   592.396418  4.643688e-109   25
1  pre_diabetes  1624.000000   0.000000e+00   25
2      diabetes    31.828539   1.630333e-01   25

## relative_risk_analysis

      condition  relative_risk   ci  p_value
0   no_diabetes            0.0  0.0      NaN
1  pre_diabetes            inf  NaN      NaN
2      diabetes            0.0  0.0      NaN

## odds_ratio_analysis

      condition  odds_ratio   ci        p_value
0   no_diabetes         inf  NaN  2.399372e-121
1  pre_diabetes         0.0  0.0  2.200058e-239
2      diabetes         inf  NaN   1.631788e-12

## relative_risk_by_age

  age_group     condition  relative_risk        p_value  confidence_interval
6     18-40   No Diabetes            inf   1.645007e-09                  NaN
7     18-40  Pre-Diabetes            0.0   9.586286e-13                  0.0
8     18-40      Diabetes            inf   1.000000e+00                  NaN
3     40-60   No Diabetes            inf   1.472635e-43                  NaN
4     40-60  Pre-Diabetes            0.0   1.936745e-70                  0.0
5     40-60      Diabetes            inf   8.776790e-03                  NaN
0       60+   No Diabetes            inf   2.071475e-62                  NaN
1       60+  Pre-Diabetes            0.0  9.346410e-147                  0.0
2       60+      Diabetes            inf   5.946386e-13                  NaN

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

