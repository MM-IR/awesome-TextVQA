# awesome-TextVQA
关于今年顶会顶刊TextVQA技术发展路线的整理

## 1.Structured multimodal Attentions for TextVQA(2020June)
Motivation:
1.现有的SOTA VQA methods

## 2.Multi-Step Inference for Reasoning Over Paragraphs
### 2.1. Motivation:
1.先前的工作只是symbolically或者transformers（黑盒子）。我们提出一个middle ground折中～ a compositional model reminiscent of neural module networks that can perform chained logical reasoning.

模型就是find 相关的句子@context，然后chain他们进去neural modules。

### 2.2. 我们的方法idea
我们的方法来自Neural Module Network，包括三种基本的module: 1)Select: 决定什么信息对于问题而言是重要的；2)CHAIN: capture the interaction from 多个statements。3)PREDICT: 就是输出最终的answer。

这三种basic modules 可以被实例化separately and freely combined。

## 3.
