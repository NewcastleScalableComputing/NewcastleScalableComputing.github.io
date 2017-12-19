---
layout: post
title: December Double-Bill
speaker: Peter Michalák and Stephen Bonner
comments: true
category: upcoming
tags: meeting <+ tags +>
---

__Time and Location:__ Monday 4th December 2017 11:00-12:00, Urban Sciences Building USB3.032


__Evaluating the Quality of Graph Embeddings via Topological Feature Reconstruction, Stephen Bonner__

In this talk we will investigate three state-of-the-art, but competing,
approaches for generating graph embeddings using unsupervised neural
networks. Graph embeddings aim to discover the 'best' representation
for a graph automatically and have been applied to graphs from numerous
domains, including social networks. We evaluate their effectiveness at
capturing a good representation of a graph's topological structure by
using the embeddings to predict a series of topological features at the
vertex level. We hypothesise that an 'ideal' high quality graph
embedding should be able to capture key parts of the graph's topology,
thus we should be able to use it to predict common measures of the
topology, for example vertex centrality. This could also be used to
better understand which topological structures are truly being captured
by the embeddings. We first review these three graph embedding
techniques and then evaluate how close they are to being 'ideal'. We
provide a framework, with extensive experimental evaluation on
empirical and synthetic datasets, to assess the effectiveness of
several approaches at creating graph embeddings which capture detailed
topological structure.

[[Slides]]({site.url}/assets/slides/20171204_Bonner_graph_embeddings.pdf)


__PATH2iot: A Holistic, Distributed Stream Processing System, Peter Michalák__

The PATH2iot open-source platform presents a new approach to stream processing for Internet of Things applications by automatically partitioning and deploying the computation over the available infrastructure (e.g. cloud, field gateways and sensors) in order to meet non-functional requirements including energy, performance and security. The user gives a high-level declarative description of computation in the form of Event Processing Language queries. These are compiled, optimised, and partitioned to meet the non-functional requirements using database system techniques and cost models extended to meet the needs of IoT analytics. The paper describes the PATH2iot system, illustrated by a real-world digital healthcare analytics example, with sensor battery life as the main non-functional requirement to be optimised. It shows that the tool can automatically partition and distribute the computation across a healthcare wearable, a mobile phone and the cloud - increasing the battery life of the smart watch by 453% when compared to other possible allocations. The PATH2iot system can therefore automatically bring the benefits of fog/edge computing to IoT applications.
