# MyPaperList
Reading paper list
## Style Tranfer:
1. **Deep Learning for Text Attribute Transfer: A Survey 2020-11-01** 
  - 文本迁移调研综述，较全面，非监督方法主要分为4类：分解方法（Disentanglement）、回译（back translation）、prototype-based、强化学习，其中prototype-based易控制，效果好，但存在改动性较小、召回耗能、对词汇重叠不够的解决不好。
  - date：2020-11-23
2. Adapting Language Models for Non-Parallel Author-Stylized Rewriting
  - StyleLM 首先在多作者语料作预训练，然后使用encoder-decoder结构对特定作者finetune，此处finetune为无监督方式，主要是DAE loss；
  - date：2020-11-23
3. Unsupervised Text Style Transfer with Padded Masked Language Models
  - 通过量身预训练模型，通过定义的score，找出最应该被替换的text spans，并通过目标预训练模型替换。
  - date：2020-11-23
4. **Parallel Data Augmentation for Formality Style Transfer**
  - 针对正式用语和非正式用语转换的数据扩增技术： 回译（BT）、回译后的Formality discrimination、GEC数据transfer，有启发性。
  - date：2020-11-23
