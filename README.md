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
## Text Generation:
1. The Amazing World of Neural Language Generation
  - 2020 ACL 一场tutorial的前述材料，没什么实质内容，实质内容在会议中，但视频和ppt暂时还如期公布，后面保持关注。
  - date：2020-11-25
2. The survey: Text generation models in deep learning
  - 深度学习在文本生成的综述，只看了不太熟悉的2.5之后的部分，启发性一般，主要get到VAE的生成能力和GAN中leakGAN较突出，文章没有提预训练模型的生成能力。
  - date：2020-11-26
3. **Evaluation of Text Generation: A Survey 2020-06-26**
  - 58 pages较长，正在阅读
4. **Controllable Text Generation Should machines reflect the way humans interact in society?  2020-03**
  - CMU一篇Thesis Proposal，更长，107 pages
5. **A Survey of Knowledge-Enhanced Text Generation 2020-10-09**
  - 知识增强生成survey，44 pages，正在阅读。
6. Facts2Story-Controlling Text Generation by Key Facts
  - 通过事实句引导文本生成，主要贡献点是定义事实space预测任务和loss function从而转换为text infilling problem.
## Paraphrase:
## GEC:
## Controllable Text Generation:
