# On the optimality of timer based caching policies for decreasing hazard rates.

[## Andres Ferragut - Universidad ORT Uruguay.](https://aferragu.github.io.) 

### Abstract:
Consider a local memory system receiving requests from a given catalog: the typical caching objective is to maximize its hit rate, i.e. the number of items that are served directly from the cache. Two main alternatives have been studied: replacement policies (such as LRU) and timer-based policies (TTL).
In previous work, we have explored the role of the hazard rate function of the inter-request times in the optimal TTL policy. Recently, Towsley et al. also identified that the optimal non-anticipative replacement policy involves the hazard rate function.
In this talk we will discuss how these two concepts relate: we show that, in large scale systems, the optimal non-anticipative policy converges to a fixed threshold policy, and that this threshold also characterizes the optimal TTL policy. Thus TTL caching is asymptotically optimal, and we can approximate the maximal hit rate by that of the TTL policy fluid limit. This enables us to compute new a universal performance bound for caching performance. We also remark that, in the case of increasing hazard rates, caching is far from optimal and introduce the notion of optimal timer-based pre-fetching.


