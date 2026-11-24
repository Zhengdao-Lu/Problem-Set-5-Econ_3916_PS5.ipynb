# Problem-Set-5-Econ_3916_PS5.ipynb

I'd hold off on signing. On the simulated test set, approving everyone was already at 93.37%. LASSO was at 50% on the same set.

I'd take LASSO forward for validation at the 10.23% decline cut-off. At that cut-off it picked up 100 of the 199 defaults and rejected 443 people who would have repaid. The estimated cost went down from $800.20 to $616.87 per application as opposed to approving everyone. That's a saving of $183.33 per application or about 23%. Both the recalibrated rules ended up costing more on the same test set.

I went with the cutoff on the validation data. I assumed a missed default cost us 60% of the loan principal and that turning down a good applicant cost us 8% of principal in lost interest margin plus $150 in lost goodwill.

I'd sign if that same cut-off delivered tangible savings over the alternative of approving everyone on a new, representative sample with known repayment outcomes and using the lender's own cost estimates.
