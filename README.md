# Dual-Filtering-Auxiliary-Transformer (PRCV 2023)
Supplementary material for our PRCV 2023 paper:

> DFAformer: A Dual Filtering Auxiliary Transformer for Efficient Online Action Detection in Streaming Videos.
> Shicheng Jing, Liping Xie.
> PRCV, 2023.
> [[Paper]](https://link.springer.com/chapter/10.1007/978-981-99-8537-1_11)


## Dual Filtering Auxiliary Transformer
<p align="justify">
Online action detection (OAD) aims to identify the specific type of ongoing action frame by frame without future information. The full exploration of historical memory with limited yet redundant information constraints for potential patterns thus becomes an important yet challenging problem. We propose a novel transformer-based framework called <strong>D</strong>ual <strong>F</strong>iltering <strong>A</strong>uxiliary Trans<strong>former</strong> (DFAformer) to achieve this goal. In DFAformer, a two-stage filtering mechanism filters impurities related to background and uninterested actions in the historical memory at the frame and element levels. To make the model concentrate on the ongoing action, we elaborate an auxiliary task, Jaccard Summary Unit, explicitly correlates the past with the future. This auxiliary task guide the learning of model weights without extra computational costs during inference. Experiments on three real-world benchmark datasets demonstrate the superiority of the proposed method.

* Architecture
<p align="center">
<img src=".\DFAformer.png" height = "480" alt="" align=center />
<br><br>
<b>Figure 1.</b> Overall architecture of DFAformer.
</p>

## Citation 
If you find this repository useful, please cite our paper.
```
@InProceedings{10.1007/978-981-99-8537-1_11,
title="DFAformer: A Dual Filtering Auxiliary Transformer for Efficient Online Action Detection in Streaming Videos",
author="Jing, Shicheng and Xie, Liping",
booktitle="Pattern Recognition and Computer Vision",
pages="134--145",
year="2024",
isbn="978-981-99-8537-1"
}
```

## Contact
If you have any questions, please contact: [scjing10@gmail.com](scjing10@gmail.com)
