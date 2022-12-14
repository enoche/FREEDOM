# FREEDOM
Pytorch implementation for "A Tale of Two Graphs: Freezing and Denoising Graph Structures for Multimodal Recommendation" [arxiv](https://arxiv.org/abs/2211.06924).  

- :u5408: This model is integrated into [MMRec](https://github.com/enoche/MMRec) framework.


## Overview of FREEDOM
<p>
<img src="./images/FREEDOM.png" width="400">
</p>

## Data  
Download from Google Drive: [Baby/Sports/Clothing/etc.](https://drive.google.com/drive/folders/13cBy1EA_saTUuXxVllKgtfci2A09jyaG?usp=sharing)  
The data already contains text and image features extracted from Sentence-Transformers and CNN.  

## How to run
1. Put your downloaded data (e.g. `baby`) under `data` dir.
2. Enter `src` folder and run with  
`python main.py -m FREEDOM -d baby`  
You may specify other parameters in CMD or config with `configs/model/*.yaml` and `configs/dataset/*.yaml`.

---
No commercial use. License reserved by authors.
