---
layout: page
title: Wikipedia Article Ecosystem: Leveraging History, Navigation, Collaboration,  and Consumption Behaviors
description: Multi-graph behavioral modeling for content discovery and recommendation
img:
importance: 4
category: past
---

I designed and implemented a multi-graph modeling approach to identify similar Wikipedia articles using behavioral signals—clickstreams, wikilinks, shared editors, and category structure. Instead of defining similarity through text alone, I analyzed how users navigate and construct pages to map how topics are meaningfully connected in practice.

Most similarity systems treat articles as isolated text blocks. My work treats them as behavioral artifacts shaped by user activity and platform affordances—providing a more accurate and interpretable foundation for search and recommendation.

**Extended Abstract Sent to Wiki Workshop '25** [link to preprint](https://wikiworkshop.org/2025/paper/wikiworkshop_2025_paper_25.pdf)


#### Research Question
*How can behavioral interaction data improve article similarity modeling on large user-generated platforms?*

#### Business Impact
Supports better recommendation engines, search ranking, and content discovery systems by integrating real user behavior into similarity metrics.

#### What I did
- **Built four behavioral networks**: clickstreams, wikilinks, editor co-authorship, and category similarity.
- **Merged networks into a unified behavioral multi-graph** using NetworkX.
- **Applied Pareto-based core extraction** to identify key knowledge clusters.
- **Benchmarked the approach against LTRank** to validate interpretability and performance.
- **Created 2D and 3D visualizations** to expose hidden ecosystem structures.

#### Why it matters
This work demonstrates how behavioral data enriches similarity modeling, producing more intuitive and user-centered knowledge discovery tools.


#### Where this work has been presented:
**Methods** 
- Jones, H. Laurie (2024, January 11-11). Wikipedia Article Ecosystem: Leveraging History, Navigation, Collaboration, and Consumption Behaviors. [Wiki Workshop 2025]. Virtual. <https://www.youtube.com/watch?v=lePKDgoxktc>  