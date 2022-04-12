# MATLAB 新聞摘要產生模型使用 GPT-2 (New Summarization with GPT-2) 
本範例利用 MATLAB 預訓練GPT-2模型來實現新聞文章內容摘要產生，從BBC爬取文章後透過 MATLAB 文獻處理工具箱(Text Analytics Toolbox)處理原始文字
並使用 RAKE 模型產生關鍵字。

![Script Snapshot](https://i.imgur.com/nkERQOf.png)

---
版本號 Version Dev.0 (版本 R2022a)
---
1. 需先下載 MATLAB Deep Learning Team - <a href=https://github.com/matlab-deep-learning/transformer-models>transformer repo</a>
2. 將下載的資料夾加入MATLAB Path
```
addpath 資料夾路徑/transformer
```



### MATLAB工具箱需求 (MATLAB Toolbox Requirement)
* Text Analytics Toolbox 

#### MATLAB 支援版本
    - R2020b
    - R2021a
    - R2021b
    - R2022a
