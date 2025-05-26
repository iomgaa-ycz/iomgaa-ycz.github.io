---
title: "DenseGCN: A multi-level and multi-temporal graph convolutional network for action recognition"
collection: publications
category: manuscripts
permalink: /publication/2023-densegcn
excerpt: 'This paper proposes DenseGCN, a novel multi-level and multi-temporal graph convolutional network for skeleton-based action recognition that effectively captures both spatial and temporal dependencies in human motion sequences.'
date: 2023-08-15
venue: 'IET Image Processing'
paperurl: 'https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.12872'
citation: 'Yu, C., et al. (2023). &quot;DenseGCN: A multi-level and multi-temporal graph convolutional network for action recognition.&quot; <i>IET Image Processing</i>. 17(11), 3299-3312.'
---

## Abstract

This paper presents DenseGCN, a novel multi-level and multi-temporal graph convolutional network designed for skeleton-based action recognition. The proposed method addresses the limitations of existing graph convolutional networks in capturing long-range spatial and temporal dependencies in human motion sequences.

## Key Contributions

- **Multi-level Spatial Modeling**: DenseGCN incorporates multiple levels of spatial graph convolutions to capture both local joint relationships and global body structure dependencies.

- **Multi-temporal Feature Learning**: The network employs temporal convolutions at different time scales to model both short-term motion patterns and long-term action dynamics.

- **Dense Connectivity**: Inspired by DenseNet, the method uses dense connections between different temporal scales to enhance feature reuse and gradient flow.

- **Comprehensive Evaluation**: Extensive experiments on NTU RGB+D and NTU RGB+D 120 datasets demonstrate the effectiveness of the proposed approach.

## Technical Innovation

The DenseGCN architecture combines:
1. **Spatial Graph Convolution Modules** for modeling joint relationships
2. **Multi-scale Temporal Convolutions** for capturing motion dynamics
3. **Dense Skip Connections** for improved feature propagation
4. **Adaptive Graph Topology Learning** for flexible joint relationship modeling

## Experimental Results

The proposed DenseGCN achieves competitive performance on standard benchmarks:
- **NTU RGB+D**: Significant improvements in both cross-subject and cross-view evaluations
- **NTU RGB+D 120**: State-of-the-art results on the large-scale dataset
- **Computational Efficiency**: Maintains reasonable computational complexity while improving accuracy

## Impact and Applications

This work contributes to the field of skeleton-based action recognition by providing a more effective way to model complex human motions. The multi-level and multi-temporal approach has potential applications in:
- Human-computer interaction
- Video surveillance
- Sports analysis
- Healthcare monitoring

