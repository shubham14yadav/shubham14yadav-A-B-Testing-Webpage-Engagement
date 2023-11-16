# A-B-Testing-Webpage-Engagement
<br> 
We have two groups:<br><br>

Group A (Control) with an average engagement time of 60 seconds. Group B (Test) with an average engagement time of 65 seconds. Both groups had the same sample size (100) and standard deviation (10 seconds). 
<br><br>Data Visualization: The histogram shows the distribution of engagement times for both groups. 
[!shubham14yadav-A-B-Testing-Webpage-Engagement](data_viz.png)
This visual representation helps us see the overlap and differences between the two groups.

Statistical Testing: We performed an independent t-test on the two groups. The t-test returned two values:

t_stat (T-statistic): -3.597, which indicates the difference in means in terms of standard error. p_value: 0.0004, which is the probability of observing a difference as large as what is observed, even if the two groups are actually the same (null hypothesis is true).

Interpretation: The p-value is significantly less than the common alpha level of 0.05, suggesting that the difference in mean engagement time between the two groups is statistically significant. Since Group B (Test) has a higher mean time spent, we could infer that the new page design (tested in Group B) might be more effective in engaging users than the current design (used in Group A).
