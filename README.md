# Impact-Analysis-for-Second-Harvest-Heartland

## Increased monthly donations by 20%, enhancing marketing campaigns through effective resource allocation

## Quantified impact of earned media sources on donation amounts accounting for external factors using regression

### Context - Business Problem
I worked as a consultant for Second Harvest Heartland which is one of the largest hunger relief organizations in US to help them understand the factors influencing the donations received. We used the data for their earned media promotions and mapped it to the donations received by each media channels.

### Assumptions
For example, if a TV ad was shown on a given day for a specific region, the donations collected for that region over the next three days may represent the result of that ad's influence, and so on. We had to make a lot of assumptions for this project because the exact impact of a given media mention cannot be accurately determined.

### Technical Approach  1
We used the concept of exponential decay to decrease the impact of media channels according to the predefined weights as per our assumption. We also considered factors such as seasonality, holidays, festivals that may have impacted our analysis.

### Technical Approach - 2
We ran regression models such as LR and SVR since our main purpose was not to forecast donation amounts but to obtain coefficients that represented the influence of media channels on donation amounts. We gave recommendations for SHH stakeholders to enhance their Marketing Mix strategy to target the relevant media channels based on our findings.
