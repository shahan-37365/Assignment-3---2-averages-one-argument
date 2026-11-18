 Statistical Summary & Item-by-Item BreakdownUsing our cleaned teaching price ledger (teaching_prices_audited_clean.csv), here are the computed metrics for each item across the 12-week observation period:
Oil B: Mean = 324.83 PKR, Median = 324.00 PKR, First-to-Last Change = $+17.45\%$ (Start: 298.0, End: 350.0).
Pulse C: Mean = 205.91 PKR, Median = 206.00 PKR, First-to-Last Change = $+6.75\%$ (Start: 200.0, End: 213.5).
Staple A: Mean = 158.71 PKR (skewed by an unverified 1,250 PKR outlier; 111.26 PKR excluding it), Median = 112.50 PKR, First-to-Last Change = $+19.31\%$ (Start: 101.0, End: 120.5).
Sweetener D: Mean = 167.15 PKR, Median = 167.50 PKR, First-to-Last Change = $+23.83\%$ (Start: 149.0, End: 184.5).
Which statistic to report and why:
For Oil B, Pulse C, and Sweetener D, where price distributions are symmetric and free of extreme distortions, both mean and median yield nearly identical stories. However, the median is preferred for general reporting because it resists minor weekly noise.
For Staple A, the median (112.50 PKR) must be reported instead of the mean. Because of an extreme unverified data entry error (1,250 PKR), the mean is artificially inflated to 158.71 PKR, which misrepresents the actual typical price hovering around 110 PKR.2.
 Impact of Flagged Values on Staple A With the flagged outlier (1,250.0 PKR): Mean = 158.71 PKR | Median = 112.50 PKR.Without the flagged outlier: Mean = 111.26 PKR | Median = 112.50 PKR.
Explanation of the Difference:
The median is virtually unaffected ($112.50$ vs $112.50$) because it only cares about the middle data point when sorted, completely ignoring the numerical magnitude of extreme values. Conversely, the mean is pulled upward by over 47 PKR by a single extreme data point because it sums every value equally. This proves why the newsroom neighbors keep arguing: one neighbor looked at an uncleaned mean distorted by errors, while the other looked at a stable median.3.
Draft Referee's Note (Labeled Sentences: O = Observation, E = Possible Explanation)
[O] Over the twelve-week teaching observation period, all four tracked grocery items recorded net percentage price increases ranging from $+6.75\%$ to $+23.83\%$.
[E] (Possible explanation) Whether a staple "really" went up depends entirely on whether one relies on the distorted mean or the stable median when data errors are present.
[O] For Staple A, the median price remained steady at 112.50 PKR, whereas the uncleaned mean surged to 158.71 PKR solely due to one unverified outlier.
[E] (Possible explanation) Therefore, the neighbor arguing via the median is correct for daily typical costs, while the neighbor citing the mean was misled by an uncleaned ledger error.

