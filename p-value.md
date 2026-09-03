# p-value
Assuming H0 is true, the probability of observing a test statistic
**at least as extreme** as the one from the sample(observed value). We want to know how surprised the result is.
Example:如果你在赌场看到有人连续赢了8把,你想问的是"这么牛的连胜(8把、9把、10把...)有多罕见",而不是"恰好赢8把不多不少"有多罕见——因为赢9把、10把只会让你更加怀疑"这局有鬼",这些情况理应都算进"证据强度"里。
 Small p-value ⇒ data
is unlikely under H0 ⇒ reject H0 if p-value < threshold (α).

# Type I & II errors

|            | H0 true          | H0 false          |
|------------|------------------|-------------------|
| Reject H0  | Type I error (α) | Correct           |
| Fail reject| Correct          | Type II error (β) |

- **Type I error (false positive):** reject H0 when it's actually true.
  e.g. concluding a drug works when it doesn't.
- **Type II error (false negative):** fail to reject H0 when it's actually false.
  e.g. concluding a drug doesn't work when it does.

- α = P(Type I error) = significance level (set before test, e.g. 0.05)
- β = P(Type II error); **power = 1 − β**
- Trade-off: lowering α (stricter) tends to increase β, and vice versa.

# How to calculate p-value