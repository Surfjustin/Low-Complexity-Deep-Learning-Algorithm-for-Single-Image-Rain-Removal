# Low-Complexity Deep Learning Algorithm for Single Image Rain Removal

## Abstract
With the advancement of artificial intelligence (AI) technology, many products have gradually integrated AI to enhance functionality and convenience, particularly in the fields of electric vehicles and unmanned aerial vehicles (UAV). Currently, most electric vehicles are equipped with Advanced Driver Assistance Systems (ADAS) to reduce driver fatigue and provide real-time support in critical situations. Real-time image processing is crucial to the effectiveness of ADAS. However, external factors such as weather conditions can degrade image quality, thereby affecting the system’s decision-making accuracy and compromising driving safety.

In addition, UAV are increasingly used in rescue operations, offering rapid search and detection capabilities. Nevertheless, adverse weather, especially rainy conditions, can negatively impact image quality, reducing UAV performance and affecting rescue efficiency.

To address these issues, this study proposes a computationally efficient and low-complexity image deraining model, composed of three modules: the Rain Streak Extractor (RSE), the Rain Streak Denoiser (RSD), and the Efficient Restored-Feature Block (ERB). Experimental results show that compared with recent image deraining methods, the proposed model significantly reduces computational cost, parameter count, and network depth, achieving up to 4T reduction in computation. Moreover, the proposed method maintains competitive visual quality in deraining performance.

<p align="center">
  <img src="./RWW.jpg" height="600px">
</p>

# Dataset
## Synthetic Datasets
| Datasets | #train | #test | label |
   | :------- | -----: | ----: | :-----: |
   | Rain12|-| 12   |-|
   | Rain100L| 200    | 100   | -|
   | Rain100H| 1800   | 100   | -|
   | Rain1200| 12000  | 1200  | -|
   | Rain1400| 12600  | 1400  | - |
   
# Pre-trained Model
**Use NVIDIA GeForce GTX3090**  
**Rain100L & Rain12 ./experiments/Rain100L**  
**Rain100H ./experiments/Rain100H**  

# Results
##FLOPs & Parameters & Layer analysis
<p align="center">
  <img src="./FLOPs.jpg" height="600px">
</p>