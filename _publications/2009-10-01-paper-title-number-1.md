---
title: "Attention-Refined Unrolling for Sparse Sequential micro-Doppler Reconstruction"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'IEEE Journal of Selected Topics in Signal Processing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10543012'
---

The reconstruction of micro-Doppler signatures of human movements is a key enabler for fine-grained activity recognition wireless sensing. In Joint Communication and Sensing (JCS) systems, unlike in dedicated radar sensing systems, a suitable trade-off between sensing accuracy and communication overhead has to be attained. It follows that the micro-Doppler has to be reconstructed from incomplete windows of channel estimates obtained from communication packets. Existing approaches exploit compressed sensing, but produce very poor reconstructions when only a few channel measurements are available, which is often the case with real communication patterns. In addition, the large number of iterations they need to converge hinders their use in real-time systems. In this work, we propose and validate STAR, a neural network that reconstructs micro-Doppler sequences of human movement even from highly incomplete channel measurements. STAR is based upon a new architectural design that combines a single unrolled iterative hard-thresholding layer with an attention mechanism, used at its output. This results in an interpretable and lightweight architecture that reaps the benefits of both model-based and data driven solutions. STAR, is evaluated on a public Joint Communication and Sensing (JCS) dataset of 60 GHz channel measurements of human activity traces. Experimental results show that it substantially outperforms state-of-the-art techniques in terms of the reconstructed micro-Doppler quality. Remarkably, STAR, enables human activity recognition with satisfactory accuracy even with 90% of missing channel measurements, for which existing techniques fail.