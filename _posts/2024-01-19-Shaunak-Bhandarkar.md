---
layout: post
title: Sequential Learning and Retrieval in a Sparse Distributed Memory -- the K-Winner Modern Hopfield Network
speaker: Shaunak Bhandarkar
---

Many autoassociative memory models rely on a localist framework, using a neuron or slot for each memory. However, neuroscience research suggests that memories depend on sparse, distributed representations over neurons with sparse connectivity. Accordingly, we extend a canonical localist memory model---the modern Hopfield network (MHN)---to a distributed variant called the K-winner modern Hopfield network, equating the number of synaptic parameters (weights) in the localist and K-winner variants. We study both models' abilities to reconstruct exactly once-presented patterns organized into long presentation sequences, updating the parameters of the best-matching memory neuron (or k best neurons) as each new pattern is presented. We find that, despite compromising slightly on retention of immediate memories, K-winner MHN's exhibit superior retention of older memories.