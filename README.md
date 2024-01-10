# AGMH

## Abstract
In recent years, hashing methods have been popular in the large-scale media search for low storage and strong representation capabilities. To describe objects with similar overall appearance but subtle differences, more and more studies focus on hashing-based fine-grained image retrieval. Existing hashing networks usually generate both local and global features through attention guidance on the same deep activation tensor, which limits the diversity of feature representations. To handle this limitation, we substitute convolutional descriptors for attention-guided features and propose an Attributes Grouping and Mining Hashing (AGMH), which groups and embeds the category-specific visual attributes in multiple descriptors to generate a comprehensive feature representation for efficient fine-grained image retrieval. Specifically, an Attention Dispersion Loss (ADL) is designed to force the descriptors to attend to various local regions and capture diverse subtle details. Moreover, we propose a Stepwise Interactive External Attention (SIEA) to mine critical attributes in each descriptor and construct correlations between fine-grained attributes and objects. The attention mechanism is dedicated to learning discrete attributes, which will not cost additional computations in hash codes generation. Finally, the compact binary codes are learned by preserving pairwise similarities. Experimental results demonstrate that AGMH consistently yields the best performance against state-of-the-art methods on fine-grained benchmark datasets.

## Paper
This is the code of "Attributes Grouping and Mining Hashing for Fine-grained Image Retrieval", which has been accepted by ACM MM 2023.
Paper Link: [https://dl.acm.org/doi/abs/10.1145/3581783.3612043](https://dl.acm.org/doi/abs/10.1145/3581783.3612043)

## Implementation
The Environment and Dataset can refer to [SEMICON](https://github.com/aassxun/SEMICON)
