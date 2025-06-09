# SPPrompt-Water
The code repository of this project is for the paper titled **"Breaking the Scale Barrier: A Scale-Progressive Water Body Extraction Framework Inspired by Human Cognitive Mechanisms."** We will make the dataset and the usage of the code public here. The abstract of the paper is as follows

**Abstract** 

Water bodies are typical natural features that exhibit significant variations in scale and appearance in high-resolution remote sensing imagery due to the influence of factors such as topography, temperature, sediment content, and aquatic vegetation. Existing deep learning-based water body segmentation networks typically adopt a local sliding-window approach for training and inference. However, this strategy limits the receptive field and hampers the model’s ability to utilize contextual information for identifying large-scale, complex-textured water bodies, often resulting in misclassification. To address these limitations, We propose a Scale-Progressive Prompt Water Body Extraction Framework (SPPrompt-Water), inspired by the hierarchical “global-to-local” cognitive mechanisms of human vision. The framework employs progressive prompting to facilitate cross-scale contextual knowledge transfer, thereby enabling high-precision water body extraction. To support this framework, we design an enforced prompt-based parallel simulation training strategy, which leverages cross-scale sample simulation and label decomposition to obtain object-level supervision within the same scene. Through parallel contrastive training, the model learns to perform segmentation with enforced prompt guidance. Extensive experiments conducted on the GID and CWBSD datasets demonstrate that the proposed method effectively balances spatial continuity in large-scale water bodies with boundary precision in small-scale ones. Our method achieves mean Intersection over Union (mIoU) scores of 83.22% and 92.27% on the respective datasets, outperforming existing approaches by 8.22% and 6.65%. These results validate the effectiveness of the proposed framework and offer a novel solution for high-precision dynamic monitoring of water bodies using remote sensing imagery.

# datasets
We will make the test data from the Complex Water Bodies Segmentation Dataset (CWBSD) mentioned in the paper publicly available on Baidu Netdisk.

# code
The code of this project will be made public after the publication of the paper.

