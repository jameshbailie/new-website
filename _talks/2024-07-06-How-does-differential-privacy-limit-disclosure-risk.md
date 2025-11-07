---
title: "How does differential privacy limit disclosure risk? A precise prior-to-posterior analysis"
collection: talks
type: "Invited talk"
date: 2024-07-06
permalink: /talks/2024-07-06-How-does-differential-privacy-limit-disclosure-risk
location: "ISBA World Meeting"
place: "Venice, Italy"
abstract: "Differential privacy (DP) is an increasingly popular standard for quantifying privacy in the context of sharing statistical data. It has numerous advantages&mdash;especially its composition of privacy loss over multiple data releases and its facilitation of valid statistical inference via algorithmic transparency&mdash;over previous statistical privacy frameworks. Yet one difficulty of DP in practice is setting its privacy loss budget. Such a choice is complicated by a lack of understanding of what DP means in connection to traditional notions of statistical disclosure limitation (SDL). In this talk, we trace the rich literature on SDL back to the foundational 1986 paper by Duncan and Lambert, which defines disclosure in a relative sense as an increase – due to the published data – in one&rsquo;s knowledge of an individual record. We prove that DP is exactly equivalent to limiting this type of &lsquo;prior-to-posterior&rsquo; disclosure, but only when the records are completely independent. More generally, DP is equivalent to controlling conditional prior-to-posterior learning, when conditioning on all other records in the dataset. This connects DP to traditional SDL while also highlighting the danger of viewing data variations as mechanistic&mdash;as does DP&mdash;rather than as statistical&mdash;in which one would explicitly acknowledge the variational dependencies between records. Based on joint work with Ruobin Gong and Xiao-Li Meng."
slides_url: 'true'
conference_url: 'https://www.unive.it/web/en/2208/home'
conference_url_type: "Conference"
---