# Hybrid Clustering of Shared Images on Social Networks for Digital Forensics



## Abstract

Clustering the images shared through social network (SN) platforms according to the acquisition cameras embedded in smartphones is regarded as a significant task in forensic investigations of cybercrimes. The sensor pattern noise (SPN) caused by the camera sensor imperfections during the manufacturing process can be extracted from the images and used to fingerprint the smartphones. The process of content compression performed by the SNs causes loss of image details and weakens the SPN, making the clustering task even more challenging. In this paper, we present a hybrid algorithm capable of clustering the images captured and shared through SNs without prior knowledge about the types and number of the acquisition smartphones. The hybrid method exploits batch partitioning, image resizing, hierarchical and graph-based clustering approaches to cluster the images. Using Markov clustering, the hierarchical clustering is conducted in such a way that the representative clusters with a higher probability of belonging to the same camera are selected for merging, which accelerates the clustering. For merging the clusters, the adaptive threshold updated iteratively through the hybrid clustering is used, which results in more precise clusters even for images from the same model of smartphones. The results on the VISION dataset, including both native and shared images, prove the effectiveness and efficiency of the hybrid method in comparison with the state-of-the-art SPN-based image clustering algorithms.

## File

[Hybrid Clustering of Shared Images on Social Networks for Digital Forensics.pdf](https://github.com/samueleevangelisti/PresentazioneCBD/blob/master/Hybrid%20Clustering%20of%20Shared%20Images%20on%20Social%20Networks%20for%20Digital%20Forensics.pdf)

## References

1. Main article : [Rahimeh Rouhi, Flavio Bertini, Danilo Montesi, Xufeng Lin, Yijun Quan, and
Chang-Tsun Li, Hybrid Clustering of Shared Images on Social Networks for
Digital Forensics. IEEE Access 2019](https://ieeexplore.ieee.org/abstract/document/8753503)
1. Markov clustering : [Stijn Van Dongen, Graph Clustering Via a Discrete Uncoupling Process.
SIAM J. Matrix Anal. Appl. 2008](https://epubs.siam.org/doi/abs/10.1137/040608635)
1. Vision dataset : [Dasara Shullani, Marco Fontani, Massimo Iuliani, Omar Al Shaya &
Alessandro Piva, VISION: a video and image dataset for source identification.
EURASIP Journal on Information Security 2017](https://jis-eurasipjournals.springeropen.com/articles/10.1186/s13635-017-0067-2)
