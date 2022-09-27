## RNN
- reuse weight matrix
- learn 3 matrix(parameters) in total
- 展开为多层前馈网络，training method: BPTT
- gradients can explode or vanish
- RNN vs LSTM: using gate to pick what to forget and what to remember, solve gradient problem to a certain degree
- 缺点：并行能力差&长时间依赖
## Transformer
- 全局语义信息
## Trend
- CNN+Tansformer
- LSTM+Tansformer
## Pre-training & Fine-Tuning 无标注数据预训练大模型+小样本微调
- based on transformer
- based on MoE (Mixture of Expert)
## BERT
- pre-training method
  - masked language model
  - next sentence prediction
- big & deep
- pre-training based on multi-task
- based on encoder
## GPT
- based on decoder
- generative pre-trained
- GPT3 works without fine-tuning
## transformer in CV
- add attention to existing CNNs
- replace convolution with local attention
- standard transformer on pixels
  - treat an image as a set of pixels value -> DETR
  - VIT image -> patch -> token embedding
- swin transformer based on window attention
## vision and language BERT
- predict masked class
- predict 图文对应
## CLIP
- 构建image和text的联系
## GLIP
## BERT-3
## PaLI
