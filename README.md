
# FBNet

**SDRNet: Camouflaged Object Detection via Frequency-aware Localization Perception and Boundary-aware Detail Enhancement**  
Accepted by KBS (Knowledge-Based Systems)

## Abstract
Although existing camouflaged object detection (COD) approaches have developed various strategies to improve performance, there remains plenty of room for further improvement. The primary challenges lie in identifying the positions of potential camouflaged objects and discerning their subtle boundaries, as the foreground and the background share visually similar properties. In this paper, we propose a novel camouflaged object detection approach to address intrinsic similarity and edge disruption through a dual-branch architecture, i.e., a frequency-aware coarse localization branch and a fine-grained detail preservation branch. Specifically, in the frequency-aware coarse localization branch, different features are first transformed from the RGB domain to the frequency domain by the proposed frequency feature learning (FFL) module, and then we design a pyramid-like frequency aggregation (PFA) module to integrate multi-level frequency features in a feature shrinking manner to obtain a localization map where the potential positions of camouflaged objects are highlighted. In the fine-grained detail preservation branch, the cross-level contextual supplement (CCS) module is proposed to enhance the feature representation by introducing the adjacent information to compensate for the weakness. Furthermore, we propose the reverse detail enhancement (RDE) module to capture and recover the subtle indistinguishable boundaries by emphasizing the detail learning in the decoder. Extensive experimental results on three public benchmarks demonstrate the superiority and effectiveness of the proposed network. The code, trained model and predicted maps will be available upon acceptance of this paper for publication.
## Links

- [Paper](#)  
- [Results](#)  
- [Pretrained models](#)  


