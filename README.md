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
7. Evaluating Neural Toxic Degeneration in Language Models
  - 文本生成的去毒化，做了去毒数据、可控语言生成的实验。实验较全面，角度新颖，是篇佳作。可视结果：https://toxicdegeneration.allenai.org/
8. Learning from the Worst: Dynamically Generated Datasets to Improve Online Hate Detection/Build it Break it Fix it for Dialogue Safety:Robustness from Adversarial Human Attack
  - 两篇增强系统辨别有毒信息能力的方式，核心是加入**人工产生对抗数据**进行迭代。
9. EFFICIENTLY MITIGATING CLASSIFICATION BIAS VIA TRANSFER LEARNING
  - （略读）预训练模型的分类层不放入微调，从未做到去毒
10. **Confronting Abusive Language Online: A Survey from the Ethical and Human Rights Perspective**
  - 对各种负面表达处理的survey，主要偏向世界观角度，之后如有工作可再细读，现主要skim了一遍，大致了解50%核心。包括 A survey of pre-processing techniques to improve short-text quality: a case study on hate speech detection on twitter（还不可阅读，后期关注）
## Representation SBERT
1. **Pretrained Transformers for Text Ranking:BERT and Beyond**
  - Text rank系列方法综述，主要分为有交互（BERT attention）和无交互（双塔）网络学embedding，然后做rerank/rank.
## Meta Learning in NLP
1. Personalizing Dialogue Agents via Meta-Learning
  - 在persona对话数据利用meta learning学习个性特征，没有使用较难获得和定义的persona信息。
## Paraphrase:
## GEC:
## Controllable Text Generation:
