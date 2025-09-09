---
title: "Semester project with Lorenz Zauter"
collection: teaching
type: "Supervision"
permalink: /teaching/SemesterProject2024
venue: "Semester project by Lorenz Zauter in the MSc Applied Mathematics at ETH Zurich
written at DCML, EPF Lausanne, Switzerland"
date: 2024-11-30    
location: 
---

# A Music-Theoretically Informed Metric for Evaluating Generated Harmonic Progressions

### Lorenz Zauter

## Abstract

The coherence of a musical piece is largely determined by its phrases, which in classical music are characterized by the melody, by voice
leading conventions and harmonic rules. While
these rules can be formalized, composers often
bend them, adding to the music’s appeal. Ensuring coherence without monotony in music generation is crucial. Measuring the completeness
of a musical phrase in a data-driven way, adaptable to different composers and corpora, has not
been done until now. This paper proposes a metric to evaluate harmonic progression completeness by learning syntactic closure from the data
rather than presupposing grammar. We embed
chords similarly to word embeddings in Natural
Language Processing, cluster chords with similar
harmonic functions, and factor progressions into
their ‘core’ and cycles of repeating chords. This
method calculates the probability of a sequence
being complete and assesses adherence to the
musical style of the corpus. Existing methods focus on local prediction accuracies and chord similarities, but lack a data-driven metric for evaluating progression completeness. This paper lays the groundwork for such a metric in western classical music.
