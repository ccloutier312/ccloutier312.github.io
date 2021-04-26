---
layout: page
title: Methods
permalink: /methods/
---

## What are word vector models and how can they be used?

<p>The promise of digital humanities, as discussed by Cameron Blevins, presents the opportunity to utilize quantitative history on traditionally qualitative sources. In discussing the caution that digital humanists take to not repeat the mistakes of “quantitative predecessors”, Blevins asserts that there is “a fear of argumentative overreach based on numerical evidence” (Blevins 2016). While earlier quantitative methods in the field of history failed to recognize the humanity or social and cultural elements in quantitative data, using digital tools offers the opportunity to investigate qualitative questions using quantitative methods. Word embedding models does just that.</p>

<p>In 2015, Benjamin Schmidt explained that word embedding models “merit attention because they allow a much richer exploration of the vocabularies or discursive spaces implied by massive collections of texts than most other reductions out there” (Schmidt 2015). Schmidt’s model, using the Chronicling America corpus, shows binaries within the corpus (for example, “sweet/salty” and “vegetable/meaty”) that are regions in the model, and not defined by single words. These classifications interestingly “exist as a spectrum rather than a class” and not only exist in the model but also “in the real world” (Schmidt 2015). It is with this concept that this project aims to investigate the understanding of gender within the FRUS corpus.</p>

<p>After training a word embedding model with the code (link), a vector space is created in which terms are plotted. The distance between points in the space represents the relationship between each word in the corpus. Each term is given a score based on similarity in usage within the corpus. Reduced down to a linear order of words, word embedding models depict the relations between terms in a corpus. In an introduction to vector space models, Schmidt notes that word embedding models are centered around two objectives: they attempt to first, “reflect similarities in usage between words in distances in space” and second, “reflect similar relationships between words with similar paths in space” (Schmidt 2015).</p>

<p>This project relies on word embedding models as a method to explore how policymakers use terms of gender in policy documents. As we will see in the <a href=“https://ccloutier312.github.io/methods/”>analysis</a>, the words most similar to gendered terms in the corpus are often based on relationships and similar groupings. These terms follow similar paths in the created space and appear to be used in similar contexts when conducting a close reading of the corpus. Therefore, word embedding models have the capability to tell scholars how the corpus writers understand social structures and cultural constructions within the text.</p>
