# Performance Tables
Here shows the performance tables of various AQA benchmarks.
## FineDiving-HM
The FineDiving-HM dataset is proposed by [FineParser(CVPR24)](https://arxiv.org/pdf/2405.06887#pdfjs.action=download), which extends [FineDiving(CVPR22)](https://arxiv.org/pdf/2204.03646) dataset by introducing human mask for each frame.
| Publication | <div style="width: 90pt">Model</div>  | <div style="width: 60pt">w/<br/>exemplar</div> | <div style="width: 60pt">Input<br/> (Train)</div> | <div style="width: 60pt">Input<br/> (Test)</div> | <div style="width: 60pt">Rho ↑</div> | <div style="width: 60pt">RL-2(*100) ↓</div> | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| CVPR2024 | FineParser | ✓ | RGB+Step+Mask | RGB | 0.9435 | 0.2602|
| CVPR2023 | TSA        | ✓ | RGB+Step | RGB | 0.9324 |  0.3022|
| ICCV2021 | CoRe       | ✓ | RGB | RGB | 0.9308 |  0.3148|
| CVPR2020 | MUSDL      | x | RGB | RGB | 0.9241 |  0.3474|
| CVPR2020 | USDL       | x | RGB | RGB | 0.8830 |  0.4800|
| - | I3D+MLP    | x | RGB | RGB | 0.8776 |  0.4967|
| - | MSCADC     | x | RGB | RGB | 0.7688 |  0.9327|
| - | C3D-AVG    | x | RGB | RGB | 0.8371 |  0.6251|
| - | C3D-LSTM   | x | RGB | RGB | 0.6969 |  1.0767|

## FineDiving
The [FineDiving(CVPR22)](https://arxiv.org/pdf/2204.03646) dataset is a diving dataset that includes annotations of sub-action boundaries and action quality scores.
### w/o DN
| Publication | <div style="width: 90pt">Model</div>  | <div style="width: 60pt">w/<br/>exemplar</div> | <div style="width: 60pt">Input<br/> (Train)</div> | <div style="width: 60pt">Input<br/> (Test)</div> | <div style="width: 60pt">Rho ↑</div> | <div style="width: 60pt">RL-2(*100) ↓</div> | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| CVPR2023 | TSA        | ✓ | RGB+Step | RGB |0.8925|0.4782|
| ICCV2021 | CoRe       | ✓ | RGB | RGB |0.8631|0.5565|
| CVPR2020 | MUSDL      | x | RGB | RGB |0.8427|0.5733|
| CVPR2020 | USDL       | x | RGB | RGB |0.8302|0.5927|

### w/ DN
| Publication | <div style="width: 90pt">Model</div>  | <div style="width: 60pt">w/<br/>exemplar</div> | <div style="width: 60pt">Input<br/> (Train)</div> | <div style="width: 60pt">Input<br/> (Test)</div> | <div style="width: 60pt">Rho ↑</div> | <div style="width: 60pt">RL-2(*100) ↓</div> | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| CVPR2023 | TSA        | ✓ | RGB+Step | RGB | 0.9203 | 0.3420 |
| ICCV2021 | CoRe       | ✓ | RGB | RGB | 0.9061 | 0.3615 |
| CVPR2020 | MUSDL      | x | RGB | RGB | 0.8978 | 0.3704 |
| CVPR2020 | USDL       | x | RGB | RGB | 0.8913 | 0.3822 |




## MTL-AQA

## AQA-7

## LOGO

## Rhythmic Gymnastics

## Fis-V



