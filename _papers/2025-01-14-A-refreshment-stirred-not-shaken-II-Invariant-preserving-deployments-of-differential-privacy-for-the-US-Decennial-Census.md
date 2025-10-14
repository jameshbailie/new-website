---
title: "A refreshment stirred, not shaken (II): Invariant-preserving deployments of differential privacy for the US Decennial Census"
collection: papers
category: privacy
permalink: /papers/2025-01-14-A-refreshment-stirred-not-shaken-II-Invariant-preserving-deployments-of-differential-privacy-for-the-US-Decennial-Census
date: 2025-01-14
venue: 'Preprint'
authors_short: '!!me!!, R Gong, XL Meng'
authors_long: '!!me!!, Ruobin Gong, Xiao-Li Meng'
citation: 'James Bailie, Ruobin Gong and Xiao-Li Meng (2025). “A Refreshment Stirred, Not Shaken (II): Invariant-preserving Deployments of Differential Privacy for the US Decennial Census”. doi: <a href="https://doi.org/10.48550/arXiv.2501.08449" target="_blank">10.48550/arXiv.2501.08449</a>'
abstract: "Through the lens of the system of differential privacy specifications developed in Part I of a trio of articles, this second paper examines two statistical disclosure control (SDC) methods for the United States Decennial Census: the Permutation Swapping Algorithm (PSA), which is similar to the 2010 Census's disclosure avoidance system (DAS), and the TopDown Algorithm (TDA), which was used in the 2020 DAS. To varying degrees, both methods leave unaltered some statistics of the confidential data – which are called the method's invariants – and hence neither can be readily reconciled with differential privacy (DP), at least as it was originally conceived. Nevertheless, we establish that the PSA satisfies \\(\\varepsilon\\)-DP subject to the invariants it necessarily induces, thereby showing that this traditional SDC method can in fact still be understood within our more-general system of DP specifications. By a similar modification to \\(\\rho\\)-zero concentrated DP, we also provide a DP specification for the TDA. Finally, as a point of comparison, we consider the counterfactual scenario in which the PSA was adopted for the 2020 Census, resulting in a reduction in the nominal privacy loss, but at the cost of releasing many more invariants. Therefore, while our results explicate the mathematical guarantees of SDC provided by the PSA, the TDA and the 2020 DAS in general, care must be taken in their translation to actual privacy protection – just as is the case for any DP deployment."
version_history: 'The third part of a trio of papers, which were originally presented together as the working paper <a href="/papers/2023-05-04-Can-swapping-be-differentially-private-A-refreshment-stirred-not-shaken" target="_blank">Can Swapping be Differentially Private? A Refreshment Stirred, not Shaken</a>.'
bibtex_url: 'true'
preprint_url: 'true'
arxiv_url: 'https://arxiv.org/abs/2501.08449'
talk_url: '/talks/TODO'
---

See also <a href="/papers/2025-01-01-A-refreshment-stirred-not-shaken-I-Five-building-blocks-of-differential-privacy" target="_blank">Part I</a> and <a href="/papers/2025-04-16-A-refreshment-stirred-not-shaken-III-Can-swapping-be-differentially-private" target="_blank">Part III</a>.