# HIP 69: Re-assertion Fee Reduction

- Author(s): @therealjohnmac50
- Start Date: 2022-07-24
- Category: Economy 
- Original HIP PR: https://github.com/helium/HIP/pull/453
- Tracking Issue: TO DO 
- Status: In Discussion 

# Summary

The average daily mining reward per hotspot is currently equal to around 50,000 DC; and it costs 1,000,000 DC to reassert a hotspot's location. 

As a result, it would take nearly a month for the average hotspot to earn enough to pay for one location reassertion.

Therefore, if we are trying to expand the network and want hotspots in saturated areas to move into less saturated areas (or moreover in lone wolf-like areas), the current reassertion price is not viable and needs to be reduced.

# Stakeholders

In reality, retroactively, this hip effects everyone. Directly, this hip effects everyone that is reasserting their hotspots. 

# Detailed Explanation

The average daily mining reward per hotspot is currently equal to around 50,000 DC; and it costs 1,000,000 DC to reassert a hotspot's location.

As a result, it would take nearly a month for the average hotspot to earn enough to pay for one location reassertion. 

Therefore, if we are trying to expand the network (h3dex targeting) and want hotspots in saturated areas to move into less saturated areas (or moreover in lone wolf like areas), the current reassertion price is not viable and needs to be reduced. 

To clarify, the original/first location assertion price wouldn't be changed, merely the reassertion prices (from the 2nd assertion and on.)

In order to help expand the network, I'm proposing that the reassertion price be changed from 1,000,000 DC, to half which is 500,000 DC. 

Please note that I specifically chose 500,000 DC and not less (say 10,000 DC), to help prevent people from taking advantage of reduced reassertion fees. 

In addition, to prevent location spoofing as a result of reassertion fees deduction, any given individual hotspot may only have its reassertion fees reduced once per year.

Although reduced reassertion fees may also benefit location spoofers, how many people will actually move their hotspots and expand the network and how many gamers would it help as a result? Especially given the once per year per hotspot limit. In other words, the pros outweigh the cons.

With the reassertion fees reduced to 500,000 DC, it would still require the average hotspot to spend 10 days worth of mining for the reassertions. 

Thus, the 500,000 DC fee is still preventing excessive/unnecessary reassertions, while also making it easier for those that want to expand the network and actually move their hotspots locations to that end.

# Drawbacks

- Location spoofers may benefit from reduced reassertion fees. 

# Rationale and Alternatives

- Alternatives may be to the reduction amount. For example, instead of the reassertion fess being reduced to 500,000 DC, an alternative may be to reduce the fee to 800,000 DC.
- Not doing this will result in people who may have moved from an over saturated areas to much less saturated areas, but will not do so on the notion that the reassertion fee in and of itself would cost many months (if not longer) worth of mining.

# Unresolved Questions

- Should exceptions be made (as in to not reduce the reassertion fees) under certain conditions. 

# Deployment Impact

This hip may be implemented by the core software development team, once they write the necessary code.

# Success Metrics

Success will be measured, once we see hotspots in over saturated areas moving to less saturated areas.
