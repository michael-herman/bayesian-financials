# Bayesian Financials

This is an experimental project that attempts to model financial statements, such as income statments, balance sheets, and cash flow statements, as Bayesian models.

## Motivation

Accounting analysis and statistical analysis (or machine learning) share similar goals -- to better understand an aspect of an organization and to make predictions about the future. Each discipline approaches those goals from opposite approaches.

Machine learning and statistics is a bottom-up approach. Machine learning models use granular data to make predictions about specific things, often within the context of a specific decision or prediction. To accomplish this, these models approximate the complex systems that generate the data, either in an explicit "white-box" model or a hard-to-interpret "black box" model. This ability to model complexity is a major strength of machine learning. Most often, these models aid in very specific decisions, such as which customers to target with marketing campaigns or determining how much merchandise a retail store should order to prevent stock-out while maintaining lean inventory.

Accounting and financial modeling is a top-down approach. Accounting models use aggregated measures (such as totals, averages, and a menagerie of ratios) to create a holistic model for how an organization's activities inter-relate. This holistic approach aids managerial planning by tying the activities of one domain -- say, the amount of new business generated in a period -- to the impact of other domains -- such as financing the cost of acquiring and servicing a customer before that customer generates cash. However, accounting and financial analysis lacks the complexity and accuracy of machine learning models.

Though each approach's strength mitigates the other's weakness, an analytical approach that bridges the two paradigms provides the benefits of each without the weakness of either. Bayesian hierarchical models are particularly well-suited for this type of analysis.

## Example

This is a good place to put an example.

