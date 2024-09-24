---
title: "Learned Spike Encoding of the Channel Response for Low-Power Environment Sensing"
collection: publications
category: conferences
permalink: /publication/2024-03-15-SpikeEncoding
excerpt: ''
date: 2024-03-15
venue: 'IEEE Annual Conference on Pervasive Computing and Communications Workshops (PerCom)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10502414'
# citation: ''
---

Radio Frequency (RF) sensing holds the potential for enabling pervasive monitoring applications. However, modern sensing algorithms imply complex operations, which clash with the energy-constrained nature of edge sensing devices. This calls for the development of new processing and learning techniques that can strike a suitable balance between performance and energy efficiency. Spiking Neural Networks (SNNs) have recently emerged as an energy-efficient alternative to conventional neural networks for edge computing applications. They process information in the form of sparse binary spike trains, thus potentially reducing energy consumption by several orders of magnitude. Their fruitful use for RF signal processing critically depends on the representation of RF signals in the form of spike signals. We underline that existing spike encoding algorithms to do so generally produce inaccurate signal representations and dense (i.e., inefficient) spike trains.In this work, we propose a lightweight neural architecture that learns a tailored spike encoding representations of RF channel responses by jointly reconstructing the input and its spectral content. By leveraging a tunable regularization term, our approach enables fine-grained control over the performance-energy trade-off of the system. Our numerical results show that the proposed method outperforms existing encoding algorithms in terms of reconstruction error and sparsity of the obtained spike encodings.