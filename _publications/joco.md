---
title: "Discount allocation for cost minimization in online social networks"
collection: publications
permalink: /publications/joco
venue: 'Journal of Combinatorial Optimization'
date: 2020-09-01
citation: 'Qiufen Ni, Smita Ghosh, Chuanhe Huang, Weili Wu, and <b>Rong Jin</b>. <i>Journal of Combinatorial Optimization (JOCO)</i>.'
---
[PDF](http://rongjinutd.github.io/files/)

## Abstract
We introduce the discount allocation problem to a new online social networks (OSNs)
scenario where the nodes and the relationships between nodes are determined but the states of edges
between nodes are unknown. We can know the states of all the edges centered on a node only when
it becomes active. Different from most previous work on influence maximization discount allocation
problem in OSNs, our goal is to minimize the discount cost that the marketer spends while ensuring
at least Q customers who adopt the target product in the end in OSNs.We propose an online discount
allocation policy to select seed users to spread the product information. The marketer initially selects
one seed user to offer him a discount and observes whether he accepts the discount. If he accepts the
discount, the marketer needs to observe how well this seed user contributes to the diffusion of product
adoptions and how much discount he accepts. The remaining seeds are chosen based on the feedback
of diffusion results obtained by all previous selected seeds. We propose two online discount allocation
greedy algorithms under two different situations: uniform and non-uniform discounts allocation. We
offer selected users discounts changing from the lowest to highest in the discount rate set until the
users receive the discount and become seed users in non-uniform discount allocation situation, which
saves the cost of firms comparing with the previous method that providing product to users for free.
We present a theoretical analysis with bounded approximation ratios for the algorithms. Extensive
experiments are conducted to evaluate the performance of the proposed online discount allocation
algorithms on real-world online social networks datasets and the results demonstrate the effectiveness
and efficiency of our methods.
