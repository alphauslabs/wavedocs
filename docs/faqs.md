# Guaranteed Commitments FAQs
For Cloud Users Managing Their Cloud Spend in WavePRO
 
---
 
## Section 1: What Are Guaranteed Commitments?
 
**Q. What are Guaranteed Commitments, and how is it different from a standard Reserve Instance or Savings Plan?**
 
A standard Reserved Instance (RI) or Savings Plan (SP) gives you a discount in exchange for committing for a fixed term — typically 1 or 3 years. The risk is that if your usage drops or you no longer need those resources, you keep paying regardless.
 
Guaranteed Commitments are built upon the same native infrastructure as RIs or SPs, but they are uniquely paired with a built-in money-back guarantee and flexible terms as short as 30 days. After the lock-in period, if a commitment goes unused and your monthly savings turn negative, the gap is automatically calculated and refunded — bringing your savings to zero.
 
---
 
**Q. Is this a separate product from cloud vendors, or is it still using native infrastructure?**
 
It is fully native infrastructure. The Reserve Instance or Savings Plan is purchased through the cloud provider ecosystem on your behalf — the underlying compute and services are unchanged. What sets it apart is a refund guarantee — a mechanism that protects against financial loss and ensures cost savings never go negative.
 
---
 
**Q. How to access and manage Guaranteed Commitments?**
 
Guaranteed Commitments are fully visible and manageable through our WavePRO platform. You can view your active commitments, monitor how much of your compute is covered, track your effective savings rate, and see the status of any rebates—all in one place, without needing to login into a separate platform.
 
---
 
**Q. How are Guaranteed Commitments applied when existing native RIs or SPs are already in place?**
 
Commitment applications are reflected exactly according to the cloud vendor's native prioritization logic. However, there is an important limitation to note: existing native RIs or SPs managed in your own account cannot be migrated to Guaranteed Commitments. Only commitments purchased within platform-managed accounts are covered under the Guaranteed Commitments Service. If you are onboarding with a mix of existing native commitments and plan to add Guaranteed Commitments, contact your account team before onboarding to understand exactly which commitments can be covered and how to structure your setup.
 
---
 
## Section 2: How the Rebate Guarantee Works
 
**Q. What does the "money-back guarantee" mean?**
 
If guaranteed commitment ever stops saving you money after the lock-in period, you get the difference back as a rebate. Your savings can never go below zero — you can only save, never lose.
 
---
 
**Q. What happens step-by-step if usage drops significantly?**
 
1️⃣ Usage Drop — Your workload scales down or an instance is shut off, and your usage falls below the commitment level.
 
2️⃣ Risk Premium Reduction — Because the Risk Premium is calculated as a percentage of realized monthly savings, it decreases proportionally as savings decrease. If no savings are realized for the month, no Risk Premium is charged at all.
 
3️⃣ Rebate — After the lock-in period, if the unused commitment results in negative monthly savings, a cash rebate is issued equal to the gap, bringing your net savings back to zero.
 
---
 
**Q. Is there a scenario where end-users end up paying more than expected?**
 
No. After the minimum commitment period, your savings are guaranteed never to fall below zero. If usage drops and no savings are realized in a given month, no Risk Premium is charged. If savings turn negative after the lock-in period, the rebate mechanism issues a refund to bring your savings back to zero. Your worst-case outcome after the commitment period is breaking even — never a loss.
 
Note that during the lock-in period, the rebate protection has not yet activated — the Risk Premium is still charged, but negative savings are not covered until after the lock-in period ends.
 
---
 
**Q. How quickly is a rebate issued, and how will the rebate be received?**
 
Rebates are calculated monthly and issued in the month following the period in which a loss is detected (Month/Year N+1). Please note that rebates are only available after the lock-in period — commitments within their lock-in period are not eligible for rebates. When a rebate is triggered, the monthly Risk Premium is automatically waived, and a rebate is issued — equal to the unused portion of the commitment. This activity is visible and trackable through your WavePRO portal. Your account team can confirm any agreement-specific details regarding disbursement format or timing.
 
---
 
## Section 3: Commitment Term and Flexibility
 
**Q. Is a full year commitment required to acquire savings?**
 
No. One of the core advantages of Guaranteed Commitments is flexible term lengths — starting from as short as 30 days. On a Flexible Plan, you can access savings of approximately 30% over on-demand — matching or exceeding standard 1-year native cloud commitment rates. This is particularly valuable if your infrastructure needs are evolving, you are in a migration phase, or you are not ready to lock into a long-term contract.
 
---
 
**Q. Can users still benefit if commitments are only needed for a few months?**
 
Yes. The Flexible Plan is specifically designed for exactly this situation. You get discounts without the pressure of a long-term commitment. After the lock-in period, the guarantee applies on a rolling monthly basis. If the workload ends early and the commitment goes unused, the guarantee ensures your savings never fall below zero.
 
---
 
**Q. What cloud services are covered by Guaranteed Commitments?**
 
Guaranteed Commitments cover all reservable AWS services that support native commitment discounts, including EC2, RDS, Redshift, ElastiCache, OpenSearch, DynamoDB, SageMaker, Lambda, Fargate, ECS, EKS, Bedrock, and more. Coverage for Azure and GCP services is also available for supported resource types.
 
---
 
## Section 4: Billing and Invoice
 
**Q. Will the Risk Premium always appear on the invoice if no savings are being generated?**
 
No. The Risk Premium is only charged in months where your commitment generates savings. If utilization drops and monthly savings reach zero or below, the Risk Premium is automatically waived for that month. You only pay for the guarantee when your commitment is actively generating savings.
 
Note: Rebates are only applicable when savings turn negative, and are available after the lock-in period (30-day or 1-year, depending on your plan).
 
---
 
**Q. How does the Risk Premium relate to the savings generated?**
 
The Risk Premium is calculated as a percentage of your realized monthly savings — not a flat fee. This means the premium scales proportionally with the value delivered. The rate depends on your commitment term: approximately 50% of savings for a Flexible Plan, and approximately 30% for a High Discount Plan. If no savings are generated, no premium is charged.
 
---
 
## Section 5: Billing and Invoice
 
**Q. What happens to Guaranteed Commitment if the organization switches providers or changes its cloud setup?**
 
The Guaranteed Commitments can be maintained according to the customer's preferences. However, since this transition will be handled on a case-to-case basis, the MSP account team in charge will coordinate the process.
 
---
 
**Q. If usage of the Guaranteed Commitment stops entirely, what happens to the underlying RIs and SPs?**
 
The underlying native RI or SP continues for the remainder of its original term, subject to standard cloud reservation rules. Because the Risk Premium is calculated solely on realized monthly savings, no premium is charged in months where no savings are generated. Please note that rebate eligibility and the status of the Guaranteed Commitment plan in this scenario should be confirmed with your MSP account team, as specific outcomes may vary depending on how and where the native commitment was originally purchased.
 
---
 
**Ready to take your cloud savings to the next level?**
 
Have more questions about your Guaranteed Commitments or savings performance? Reach out to your account team.
 
**Also check out:**
[Using WavePRO to Plan, Purchase, and Track Guaranteed Commitments](gcguide.md)