# Health Insurance EDA Using Plotly

This repository contains an exploratory data analysis (EDA) of health insurance data using **Plotly** for interactive visualizations. The analysis aims 

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Summary of Findings](#summary-of-findings)
- [License](#license)

## Introduction

This analysis explores key trends and dynamics in the Indian health insurance sector over the past decade, focusing on the performance of public, private, and standalone insurance providers. By examining policy distribution, coverage, premiums, and the role of government-sponsored schemes, we identify shifts in market dominance, consumer behavior, and pricing strategies. The findings offer a data-driven perspective on how the landscape has evolved—from the rise of private and standalone insurers to the continued influence of public sector offerings, particularly in reaching the financially underserved.

## Dataset

The dataset was obtained from the official website of [Insurance Regulatory and Development Authority](https://irdai.gov.in/handbook-of-indian-insurance).

## Summary of Findings

We found that initially the dominance of private companies in the health insurance space was low but from 2018, the both the private insurers and the standalone have overtaken the public insurance companies in the policies distributed.

The consistently top performing insurers from each category are as below:
- Private    : ICICI Lombard, HDFC ERGO, Bajaj Allianz
- Public     : National Insurance and New India Assurance
- Standalone : Star & Allied, Care and Niva Bupa

Though the number of policies sold by the public companies have been lower compared to their private and standalone counterparts, the number of people who benefit from the insurance policies from the public sector, largely outweigh the others in comparison(3x of private on average). But the number of persons covered amongst the public companies is fluctuating wildly over the years. Count of people subscribing to health insurance policies has risen from 216M to 520M in the above span of years, which is roughly a third of the population at the time of publishing.

The entire health insurance sector has been witnessing annual growth in premiums by a compounded yearly growth of 17%. Public insurers had the lowest rate of growth at 13% and standalone providers witnessed the highest at 28% annually. But at any point in time the public sector premium was manifold of the private and standalone separately.

The government of India offers various policies at a subsidised cost aimed towards the financially underprivileged. These policies can be subscribed from both private and public insurance companies. From the treemap, it can be observed that around 85-90% of these policies are subscribed through the four public companies from 2013-2022. 
Reliance, ICICI Lombard, IFFCO Tokio and Bajaj Allianz are the private players who have had a sizeable subscription of these policies from the people.

The median value of a individual health insurance policies have been becoming costlier year on year(10% increase on average). Now, comparing the premiums among various undertakings, we find that the standalone insurance companies have always charged greater than the private insurance companies when compared median to median. The public insurance companies had started with the lowest premium from 2013 but over the years have greatly increased their pricing and are now close to the cost of standalone providers. It is noteworthy to mention that spread of the policy premiums have stayed tight for the public companies relatively, could be a consequence of government intervention or fewer overall variants offered. The story for floater policy is strongly in line with the case of individual policies, standalone providers were the most expensive initially, but public providers has rapidly caught up. The difference being in this case, the divergence amongst the players was low to start with and during most years the public policies were the most expensive. As expected the price of government sponsored policies have remained more or less the same amongst all providers. Even the aggregate cost only grown by a marginal 2% compounded annually over the period.
 
## License
This project is open-source and available for educational and research purposes.
