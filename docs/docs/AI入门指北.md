---
layout: default
title: AI
description: 2026 AI 春招指北
theme: jekyll-theme-caymanqq
---

# 写在前面

AI的知识庞大且复杂，并且短期收益很低，**请务必想清楚为什么要学AI**。如果你只是想找到一份更好的工作，我们认为在这个AI的时代，反而是对AI做各种支持的前后客户端，PM等机会更多，更容易找到一份理想的工作，性价比更高。AI组的研究方向是底层算法、模型、训练方法等AI基建。AI门槛很高，通常需要硕士或者博士才能有不错的产出。其次，并不是只有AI组才能做AI，我们更关注底层算法。请务必思考清楚为什么要学AI为什么要报名AI组，否则你很有可能被刷掉。在这个最火的领域，如果你真心热爱并且决心钻研底层算法，你需要和全世界最顶尖的人才与资源竞争，请做好心理准备。

AI的细分路线非常多，我们非常建议你在了解深度学习的基本知识之后多在细分方向进行一些了解和探索。本指南会按照通用知识-细分方向及前沿来书写，你只需要了解你基础知识+感兴趣的方向（如果学有余力）即可。

其次，现在大语言模型和AI工具非常发达，我们强烈推荐你使用LLM获取信息来提高信息获取的效率，使用AI编程工具来辅助编程。但请注意，不要过度依赖AI工具，**你至少需要理解AI生成的东西并有判断正误的能力**。下面是一些推荐的LLM和AI工具：[deepseek](http://chat.deepseek.com), [gemini](http://gimini.google.com), [grok](https://grok.com/?referrer=website), [chatgpt](http://chat.openai.com), [qwen](http://chat.qwen.ai), [copilot](https://github.com/features/copilot), [cline](https://cline.bot/)。以上工具都是免费的或者至少有免费的功能。

# 基础知识

## Linux / Git

### 操作系统选择

**强烈不建议在 Windows 系统下进行 AI 相关代码的运行**

* 如果你的主要操作系统是 Windows，建议使用 [**WSL2**](https://learn.microsoft.com/en-us/windows/wsl/) （Windows Subsystem for Linux），它对 AI 训练/推理所需要调用 GPU 的过程有非常好的支持，并且非常易于上手使用，可以直接用 VSCode 获得和原生 Linux 几乎相同的体验；

* 如果你想深度体验 Linux，也可以安装 Ubuntu 等常见的发行版（如果想保留原有的 Windows 系统，可以尝试安装双系统，但是要注意做好数据的备份）；

* 如果你使用的是 MacBook，可以直接使用系统自带的终端来完成后续的操作。

### Linux 和 Git 速成

**Linux&#x20;**&#x548C;**&#x20;Git** 的基本知识可以参考 [@Sukuna](https://sukunahust.moe) 的 **Intro to CS**（https://sukunahust.lanzn.com/iThKK1pqq9gj）的第三部分 3.1\~3.3 和 4.3，这些内容能帮你快速掌握 Linux 和 Git 的基本使用方法。随后，建议在实际操作中加以应用，并在遇到问题时查阅相关文档或询问 GPT 。

## Python

### 基础知识

1. **环境搭建**：安装 Python（推荐 3.9 或以上版本，**强烈不推荐最新版**）、Anaconda/miniconda、配置 IDE（如 PyCharm 或 VS Code，**强烈推荐 VSCode**）（如果要用PyCharm可以在JetBrains中注册学生账号使用）

2. **基本语法**：变量、数据类型（整数、浮点数、字符串、列表、字典等）、运算符。

3) **控制流程**：条件语句（if-else）、循环（for、while）。

4) **函数**：定义函数、参数传递、lambda 函数。

5. **模块与包**：导入标准库（如 math、random），理解 pip 安装第三方库

### 进阶内容

1. **面向对象编程**：类、对象、继承、封装。

2. **文件操作**：读取和写入文本文件、处理 CSV 文件。

3) **数据分析基础**：NumPy（数组操作）、Pandas（数据框处理）。

4) **常用库**：熟悉 os、sys、time 等实用模块。

### AI相关Python 技能

1. **科学计算与可视化**：Matplotlib 和 Seaborn（数据可视化）

2. **机器学习基础**：Scikit-learn（简单模型训练，如线性回归、分类）

3. **深度学习入门**：TensorFlow 或 PyTorch 基础（安装、简单神经网络）

4. **数据预处理**：清洗数据、处理缺失值、特征工程

**建议任务**：

- 用 Matplotlib 绘制数据可视化图表。
- 用 PyTorch 搭建并训练一个简单神经网络。

### 推荐课程与教程

1. [**廖雪峰的网站**](https://liaoxuefeng.com/books/python/introduction/index.html)

在网站上大部分python语法知识均有涵盖，大概学习到面向对象编程，最好网上找一些习题帮助自己巩固

* [**哈佛大学CS50课程网址**](https://cs50.harvard.edu/ai/2020/)

一门非常基础的 AI 入门课，让人眼前一亮的是 12 个设计精巧的编程作业，都会用学到的 AI 知识去实现一个简易的游戏 AI，比如用强化学习训练一个 Nim 游戏的 AI，用 alpha-beta 剪枝去扫雷等等，可以加强理解AI中python语言的作用。

* [**UCB CS61A**](https://cs61a.org/)

这个课程较难，主要是在介绍python的高级语言特质与抽象，强调掌握用程序来解决实际问题，而不关注底层的硬件细节

**python学习是为了AI程序编写服务的，应该需要在阅读与理解经典架构的基础上，通过代码复现的方式加强对python语言的理解与运用**

## Pytorch or Tensorflow

建议初学者先学习 pytorch，学术界一般都使用 pytorch，工业界有部分使用 TensorFlow

一个比较详细的 pytorch 参考教程 https://tingsongyu.github.io/PyTorch-Tutorial-2nd/

（如果你对自己的英语能力非常有信心，你也可以直接啃文档[Pytorch文档](https://pytorch.org/docs/stable/index.html)）

常用且重要的函数与类：

* `torch.utils.data.Dataset()`, `torch.utils.data.DataLoader()`等数据基类

* `torch.cat()`, `torch.stack()`, `torch.reshape`, `torch.view`等张量操作函数

* `torch.nn.Module`, `torch.nn.Sequential`, `torch.nn.Parameter`等模型操作函数

## 服务器 / ssh

在你尝试简单的模型（如手写数字分类）时，你可以简单地使用 CPU 来完成模型的训练和推理。但当你试图训练或推理更大的模型，或使用更大的数据集时，GPU 可以大大增加模型训练和推理的速度（原因之一是 GPU 能同时计算很多向量操作）。

在 AI 领域，目前主流的 GPU 是 NVIDIA（英伟达） 的，如果你的电脑有英伟达的独显，那么你可以在 Pytorch 中通过 CUDA 库来调用对应 GPU（**注意：需要在安装 pytorch 时安装 cuda 版本的 pytorch，而不是 cpu 版本的 pytorch**）

如果你的电脑没有英伟达的独显，那么你可能就需要使用第三方的 GPU 服务器租赁服务，在 autodl（https://www.autodl.com/）上可以按小时租赁 GPU 服务器，比较适合练习，可以用相对合理的价格租到个人一般不会购买的 GPU，例如 RTX 4090 的价格为 2.08/时。**需要注意的是，在使用完毕服务器后需要及时关闭，否则会不断扣费，直到耗尽账户中的余额**。**因此，不建议一次性在 autodl 中充值很多钱，建议一次充值 5\~10 元，避免大量损失。**

租赁的服务器需要使用 ssh 连接，非常推荐你使用 **VSCode**，利用 **Remote-SSH** 插件可以获得和本地 GPU 几乎一致的代码编写/运行体验。

关于 autodl 的具体使用，可以参考 autodl 的官方文档，提供了非常详细的使用方法，甚至包含了视频教程：https://www.autodl.com/docs/

## 数学知识

数学知识是人工智能与AI的基础，优秀的数学能力可以让你在科研的道路上更加顺利。但同时，深度学习也不一定需要非常强大的数学知识，通常一知半解也足够，但我们认为多了解和掌握数学知识仍是必要的。该部分加粗的部分为重点知识，推荐必看，加\*号的知识为部分领域用到或者已经过时的知识，推荐遇到了再看同时，**推荐的课程和教材适合有时间的时候系统学习**，我们**建议直接从知识要点入手**而不是系统的学习数学知识，系统学习效率过低，而且很多知识可能很久都用不到。

### 线性代数

线性代数是人工智能的核心数学基础之一，它为神经网络、机器学习算法和数据处理提供了必要的理论工具。在AI领域，线性代数的应用无处不在，从简单的向量运算到复杂的矩阵分解，都是构建和理解AI模型的基石。

**知识要点：**

* **向量与矩阵运算**（加减乘法、转置、逆矩阵）

* 矩阵分解（特征值分解、奇异值分解SVD、QR分解）

* **线性变换与空间映射**

* 向量空间、子空间、基与维度

* 范数（L1、L2范数等）

* **矩阵求导**

* \*低秩近似

* \*主成分分析(PCA)

**不错的教材或课程**

* **《线性代数及其应用》(Gilbert Strang)**

  * MIT的线性代数经典教材，内容全面且注重应用

  * 特别关注矩阵分解、特征值等在机器学习中常用的概念

* [**Gilbert Strang的MIT线性代数公开课**](https://www.bilibili.com/video/BV16Z4y1U7oU/)

  * 结合教材的视频课程，讲解生动，深入浅出

  * 特别推荐关于特征值、SVD和正定矩阵的章节

* **[3B1B线性代数](https://www.bilibili.com/video/BV1ys411472E/)系列视频《线性代数的本质》**

  * 以直观的可视化方式解释线性代数概念

  * 建立对向量空间、线性变换等概念的几何直觉

  * 短小精悍，非常适合入门和巩固概念

* **《深度学习中的线性代数》(Mike X Cohen)**

  * 专注于深度学习中用到的线性代数知识

  * 包含大量Python代码示例，理论结合实践

* **《The Matrix Calculus You Need For Deep Learning》**

  * 免费在线资源，专注于深度学习中的矩阵微积分

  * 对理解反向传播算法特别有帮助

  * 链接：<https://explained.ai/matrix-calculus/>

### 概率论

**知识要点：**

* **概率基础**（条件概率、贝叶斯定理）

* **随机变量与概率分布（**&#x9AD8;斯分布、伯努利分布等）

* **期望、方差、协方差**

* 联合分布与边缘分布

* **最大似然估计(MLE)与最大后验估计(MAP)**

* 信息论基础（熵、交叉熵、KL散度）

* \*蒙特卡洛方法

* \*贝叶斯推断

* \*马尔可夫链与隐马尔可夫模型

**不错的教材或课程**

* **《Pattern Recognition and Machine Learning》(Christopher Bishop)**

  * 机器学习中的概率方法经典教材

  * 第一、二章对概率论在机器学习中的应用有很好的介绍

* **《概率图模型：原理与技术》(Daphne Koller)**

  * 深入介绍概率图模型，包括贝叶斯网络和马尔可夫随机场

  * 适合进阶学习

* **《统计学习方法》(李航)**

  * 结合机器学习算法讲解相关概率统计知识

  * 特别适合想了解概率在机器学习中应用的读者

* **MIT 6.041 Probabilistic Systems Analysis and Applied Probability**

  * 全面系统的概率论课程，有完整的视频和讲义

  * 涵盖从基础到高级的概率论知识

* **《Information Theory, Inference, and Learning Algorithms》(David MacKay)**

  * 将信息论、概率推断与机器学习结合起来

  * 免费电子版：<http://www.inference.org.uk/mackay/itila/>

## 基础算法&模型

基础算法和模型是人工智能的基座，我们会提供知识要点和一些学习资料。由于AI的知识非常庞杂，我们建议你在学习资料里找对应知识要点的部分进行观看和学习来获得最高效率。同时知识要点中涉及的知识点也是面试和熬测的重要内容。

### 知识要点

#### 基础算法：

* 前向和反向传播(激活函数, 学习率, 梯度传播等)

* 优化算法(Adam, SGD, RMSprop等)

* 损失函数(MSE, MAE, Cross Entropy Loss, KLD等)

* 正则化

* 逻辑回归

* 线性分类神经网络

* 多层感知机(MLP)

#### 神经网络模型：

* MLP(多层感知机)

* CNN(卷积神经网络)

* RNN(循环神经网络)

* LSTM(长短时记忆神经网络)/GRU(门控循环单元)

* DNN(稠密神经网络)

* GAN(生成对抗网络)

* VAE/AE(自编码器/变分自编码器)

* [Diffusion](https://docs.qq.com/doc/DVkhEd3J5eURFYVdG)(扩散模型)

* Transformer

* Flow

* .......

### 不错的教材or课程

* [3B1B深度学习系列视频](https://space.bilibili.com/88461692/lists/1528929?type=series)

  * 3B1B的科普视频，短小精悍，非常适合帮助你对AI和深度学习有个大概的认知和了解。其对于梯度下降，Transformer等概念的讲解形象易懂，对初学者非常友好。

* [吴恩达深度学习](https://www.bilibili.com/video/BV11H4y1F7uH/?spm_id_from=333.337.search-card.all.click)

  * 吴恩达深度学习比较入门和简单，非常适合小白和非计算机背景的同学对计算机。但是他的视频很长，建议按照上面的要点选择性观看，不懂的内容（例如向量化，梯度消失和爆炸等）建议优先问LLM（大语言模型）获取知识的效率更高。

  * 该课程为英文，B站视频有中文字幕，非常适合了解AI的英文原意是什么样的，但同时对英语水平提出了一些要求

* [动手学深度学习(官网电子书)](https://zh.d2l.ai) [动手学深度学习(李沐老师视频版)](https://www.bilibili.com/video/BV1if4y147hS/)**&#x20;**

  * 李沐老师的这本书非常详细，章节设置较为合理，是不错的进阶教材。同样的，这本书非常厚，我们建议在获得了一定的基础知识的情况下多用书中的例子进行动手。

  * 这本书代码有很多版本，我们建议使用pytorch进行学习

* [李宏毅老师视频](https://www.bilibili.com/video/BV1YsqSY8EiW/)

  * 李宏毅老师讲解非常清晰，而且时长相对较短，也非常适合进行入门。

  * 同时李宏毅老师的[Diffusion](https://www.bilibili.com/video/BV1mLbQeRExa/)视频，[Transformer](https://www.bilibili.com/video/BV1wB4y1o7is/)视频，[AE](https://www.bilibili.com/video/BV16s4y1R7YA/)视频等等模型讲解视频非常详细，讲得非常好。

## 英语与文献阅读（进阶）

对于AI来说，英语是国际通行语言，而且很多概念都是英文的，没有翻译或者翻译过来很奇怪。学习人工智能不可避免的要阅读英文文献和英文文档，进行英语写作和交流。我们不推荐没有任何经验的小白直接啃英文原文，即使你英语很好，大量的专有名词也会劝退。我们建议先从基础和经典论文的讲解看起， 比如[李沐老师的论文讲解合集](https://space.bilibili.com/1567748478/lists/32744?type=season)，[B站UP主deep\_thoughts](https://space.bilibili.com/373596439)的论文讲解等。推荐从经典的论文[GAN](https://arxiv.org/abs/1406.2661)和[Transformer](https://arxiv.org/abs/1706.03762)看起。对于经典的论文，一定要弄懂其中的每段话和每个公式，同时需要注意积累专有概念的表达。

当你啃完一些经典论文之后，论文讲解视频已经不能满足你的知识获取了，这时候可以搜索相关领域或者子方向的论文进行阅读。计算机的绝大多数论文都在[arxiv](http://arxiv.org)上进行发布，这个网站免费且资源丰富。其余一些论文可能会发在各种期刊或者会议上，推荐使用[google scholar](https://scholar.google.com/)进行检索。同时推荐使用[zotero](https://www.zotero.org/)进行论文的分类管理。需要查找对应方向的SOTA工作和bencmark可以访问[paper with code](https://paperswithcode.com/)，也推荐使用paper with code和github查找对论文的复现代码并动手进行复现。

当你已经在AI领域耕耘了一段时间，论文写作是不可避免的问题，当然论文写作更多的需要老师和师兄的指导，每个实验室的标准和习惯略有不同，这里仅做粗浅的介绍。推荐使用latex和[overleaf](https://www.overleaf.com/)进行论文写作。论文写作教程可以查看[ 顶会论文写作建议 ](https://uestc.feishu.cn/docx/IBH8dc765oKde8xt5RmceGEGnXg?from=from_copylink)。

# 细分方向

## CV(Computer Vision)

计算机视觉（Computer Vision, CV）旨在赋予机器模拟人类视觉系统的能力，使其能够从图像或视频中提取高层次语义信息。随着深度学习技术的突破，神经网络已成为CV领域的核心方法。CV 是一个极其广大的范围，含有几十种任务，我们可以进行如下的分类：

**CV研究按层次感知可分为下面三个方向：**

* 低层次感知：例如图片级别的猫狗分类，还有密集预测中 low-level 的任务，如边缘检测、光流估计等，依赖局部特征提取与几何建模而不用过度依赖语义信息

* 中层次感知：聚焦像素级，语义级理解，如语义分割、目标检测、深度估计等，依赖全局特征提取和中等层级的语义信息

* 高层次认知：涉及语义推理与跨模态交互，例如多模态大模型的视觉问答（VQA）和文本生成图像（如DALL·E）

CV在互联网中的教程是AI领域中最多的一个，入门推荐[CS231n](https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click\&vd_source=2de662427ef7fd9ea3c711a0e9fcbb56)，如果你想投入这个方向，我们希望你对于最基本的一些CNN网络有所了解，例如AlexNet，GoogleNet，VGG，UNet等。如果这些都不够体现你的才华，你可以在中层次任务中选取任意一个任务深入了解这个任务中的经典网络结构和设计理念，例如语义分割中的 UNet，SegNet，Mask2Former 等；目标检测中的 YOLO，RCNN，DETR系列网络。如果这仍装不下你的才华，你可以进一步了解高层次认知的任务和网络，例如Diffusion，BEiT，DeiT等等

## NLP(Natural Language Processing)

自然语言处理（Natural Language Processing, NLP）是人工智能的一个重要分支，致力于让计算机理解、解释和生成人类语言。NLP技术使计算机能够处理、分析和生成自然语言文本，实现人机交互的自然化。随着深度学习和大模型的发展，NLP领域取得了革命性的突破。

**NLP研究可以按照任务复杂度和语义理解层次分为以下几个方向：**

* **基础语言处理**：包括分词、词性标注、命名实体识别等基础任务，这些任务是构建高级NLP应用的基石。代表技术有BiLSTM-CRF、BERT序列标注等。

* **语义理解与表示**：专注于理解文本的含义，包括词向量学习、语义角色标注、句法分析等。代表技术有Word2Vec、GloVe、ELMo、BERT等预训练模型。

* **复杂语言理解**：涉及更高级的语义理解任务，如文本分类、情感分析、机器阅读理解、自然语言推理等。这些任务需要模型具备更强的语义理解和推理能力。

* **文本生成与对话系统**：包括机器翻译、文本摘要、对话生成、故事生成等生成式任务。代表技术有Seq2Seq、Transformer、GPT系列模型等。

* **多模态NLP**：结合文本与其他模态（如图像、音频、视频）的信息处理，如视觉问答(VQA)、多模态情感分析等。代表模型有CLIP、DALL-E、Flamingo等。

* **大型语言模型(LLM)**：基于Transformer架构的超大规模预训练语言模型，如GPT-4、Claude、Llama等，具有强大的通用能力和涌现能力。

NLP入门推荐学习Stanford的[CS224n](https://web.stanford.edu/class/cs224n/)课程，以及Jurafsky和Martin的《[Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/)》教材。如果你想投入这个方向，建议先掌握基础的语言模型概念，如n-gram、RNN、LSTM等，然后深入学习Transformer架构及其变体，这是当前NLP领域的核心技术。

对于进阶学习，可以选择特定任务深入研究，如机器翻译中的注意力机制、文本生成中的解码策略、对话系统中的上下文建模等。如果你对大模型感兴趣，可以学习预训练-微调范式、提示工程([Prompt Engineering](https://github.com/dair-ai/Prompt-Engineering-Guide))、RLHF(人类反馈的强化学习)等技术。其他推荐的课程有[人大高瓴大模型综述](https://github.com/RUCAIBox/LLMSurvey)。此外你也可以了解一下RAG，CoT等技术以及[Dify](https://dify.ai/)，[langchain](https://www.langchain.com/)等大模型应用工具。

NLP是一个发展迅速且应用广泛的领域，从搜索引擎、智能助手到内容创作、自动翻译，都有NLP技术的身影。如果你对语言和计算机的交互充满热情，NLP将是一个既有挑战性又充满机遇的研究方向！

## Speech and Audio

语音的任务大致分为两大类，第一类是声音的理解，第二类是声音的重建。这延申出了ASR（语音识别）和TTS（语音合成）两个主要的大方向。此外，也有很多其他方向比如说SE（Speech Enhancement），SVS（Singing Voice Synthesis）等等。语音是一项非常古老的技术，甚至远早于互联网和AI。语音的教程相对较少，推荐[李宏毅老师的视频](https://www.bilibili.com/video/BV1E24y1R7Cj)，和[CMU WAVLab的视频](https://www.youtube.com/@wavlab3016/videos)。比较经典的论文有:[HiFi-GAN](https://arxiv.org/abs/2010.05646)、[VITS](https://arxiv.org/abs/2106.06103)、[wav2vec](https://arxiv.org/pdf/1904.05862)，语音大模型方向模型：[VALL-E](https://www.microsoft.com/en-us/research/project/vall-e-x/)、[Tortoise-TTS](https://github.com/neonbjb/tortoise-tts)、[whisper](https://github.com/openai/whisper)、[HuBERT](https://arxiv.org/abs/2106.07447)、[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)，建议对语音感兴趣的同学从一些常用的语音处理库和语音基础概念开始学习，比如常用库librosa, soundfile, [kaldi](https://kaldi-asr.org/), [espnet](https://espnet.github.io/espnet/)等，常用的概念有MFCC (梅尔频率倒谱系数)、F0（基频）、频谱(Spectrogram)、谐波(Harmonics)、声码器(Vocoder)等。你也可以从兴趣出发，比如说Vocaloid，GSV等技术开始学起。此外，[B站UP主皮皮虾勇闯天涯](https://space.bilibili.com/2033385699)的视频是语音入门和语音总体概述非常不错的视频。语音是一个相对没那么卷但是也快要卷到头的方向，如果你热爱语音技术，相信你可以获得很大的收获！

## Embodied AI

具身智能（Embodied AI）旨在通过物理或虚拟实体与环境的动态交互，实现智能系统的自主感知、决策与行动闭环，是AI领域中处于最上层的任务。其核心在于将智能体（Agent）与本体（Embodied Body）深度融合。具身智能 = 本体（物理载体） + 智能体（感知-决策-执行闭环），通过与环境的实时交互实现任务目标，其发展历程可划分为：

* 早期探索：基于规则控制的机器人（如工业机械臂）

* 深度学习驱动：结合视觉、语言模型的多模态交互（如自动驾驶）

* 通用智能体阶段：利用大模型实现跨任务泛化（如人形机器人

与AI其他领域（统称为离身智能（Disembodied AI））的区别在于：离身智能依赖旁观式数据（如ChatGPT、图像分类模型），缺乏物理交互能力，而具身智能：通过主动交互学习（如机器人抓取、视觉导航），需解决物理仿真、多模态对齐等挑战。分为三个模块：本体（物理平台+仿真平台），感知（目标检测，语义分割，视觉-语音导航），交互与学习（规划（world model），学习（例如PPO学习算法））

投身这个方向需要你对AI各个领域都有一定了解，包括但不限于CV，多模态，RL等，其中CV与多模态的知识用于具身智能中对外界环境的感知，RL等知识用于与环境的交互，规划和学习。这个领域上手难度高且网上缺乏系统的学习资源，可以参考这个github repo进行学习：https://github.com/tianxingchen/Embodied-AI-Guide

## RL(Reinforce Learning)

RL是非监督学习的代表，根据模型与环境的实时交互获取奖励进行自我迭代更新。

在面对人类难以完全覆盖的数据集上，RL具有广泛的运用前景，如路径规划、机器人、大模型的数据。

前置知识：

* 贝尔曼方程、动态规划、状态四元组

* Sarsa、Q-learning：[Demo](https://cs.stanford.edu/people/karpathy/reinforcejs/)

* On-policy ，off-policy，value-base，policy-base

* Gymnasium: Atari or Atari 2600+

入门可以将Gymnasium库的Atari的若干小游戏跑一跑，尝试[DQN](https://www.nature.com/articles/nature14236)、PG、TD3、[PPO](https://arxiv.org/abs/1707.06347)等各种基础模型。一些教学：[Hands-on-RL(SJTU)](https://hrl.boyuai.com/)，[David Silver(UCL)](https://www.bilibili.com/video/BV1kb411i7KG?from=search\&seid=12335836101694062300) [李宏毅(NTU台大)](https://www.bilibili.com/video/BV1UE411G78S?from=search\&seid=9725909430531578664) [周博磊(UCLA)](https://github.com/zhoubolei/introRL)  。

需要注意的是，RL的算法现在基本上都是用PPO，实际效果差异多在奖励的设计上，所以同学们在学习搭建模型时如果遇到不收敛的情况，也有可能是你的奖励设计不合理。

前沿方向：[RL paper](https://github.com/yingchengyang/Reinforcement-Learning-Papers)，具身智能，自监督学习，RLHF，[多智能体](https://github.com/LantaoYu/MARL-Papers)等等。

## AI4Sci(AI for Science)

AI for Science (AI4Sci) 是人工智能与各科学领域交叉融合的前沿方向，旨在利用AI技术加速科学发现、优化实验设计和提升理论建模能力。随着深度学习和大模型的发展，AI已从传统的数据分析工具转变为科学研究的核心驱动力，能够处理高维复杂数据并发现人类难以察觉的模式。

**AI4Sci研究可按应用领域分为以下几个主要方向：**

* **生物医学AI**：包括蛋白质结构预测(AlphaFold)、药物发现、基因组学分析和医学影像诊断等，利用深度学习模型处理生物大数据，加速新药研发和疾病诊断

* **物理与化学AI**：涉及分子动力学模拟、量子化学计算、材料设计与发现，通过神经网络模型预测物质性质和化学反应路径

* **地球与环境科学AI**：应用于气候模型、地震预测、生态系统监测等，结合卫星图像和传感器数据进行环境变化分析

* **天文与宇宙学AI**：用于天体分类、宇宙结构模拟、引力波检测等，处理海量天文观测数据

* **科学大模型**：如Galactica、AlphaGeometry等专注于科学知识的大型语言模型，能够理解和生成专业科学内容

AI4Sci领域要求交叉学科背景，既需要扎实的AI技术基础，也需要对特定科学领域有深入理解。入门推荐学习资源包括Stanford的CS-X系列课程(如[CS279: Computational Biology](https://web.stanford.edu/class/cs279/))、MIT的[6.874](https://mit6874.github.io/)(Computational Systems Biology)以及各大顶会(NeurIPS、ICLR、ICML)中的AI4Science workshop。

核心技术包括图神经网络(GNN)、几何深度学习、物理信息神经网络(PINN)、可解释AI和自动实验设计等。经典论文如AlphaFold、E3NN(等变神经网络)、SE(3)-Transformer等值得深入研究。

AI4Sci是一个快速发展且影响深远的方向，如果你对科学有浓厚兴趣并具备编程能力，这个领域将为你提供将AI技术应用于解决重大科学挑战的机会，有望在药物发现、气候变化、新材料设计等领域产生突破性进展。

**P.S.组内成员研究方向有限，可能有些方向没涉及到，并且NLP、AI4Sci方向仅供参考。**

# 其他资源推荐

## 相关网站

[ UESTC AI社 指南](https://uestc.feishu.cn/docx/QqQddDFLpoE3D1x2UF2cmjQdn9g?from=from_copylink)    [arxiv](http://arxiv.org)    [paperwithcode](https://paperswithcode.com/)    [kaggle](https://www.kaggle.com/)    [github](http://github.com)    [huggingface](http://huggingface.co)    [魔塔社区](https://www.modelscope.cn/)     [autodl](https://www.autodl.com/)    [fast.ai](http://fast.ai)

## 相关博主

[AndrejKarpathy](https://www.youtube.com/@AndrejKarpathy)    [3blue1brown](https://www.youtube.com/@3blue1brown)    [李沐](https://space.bilibili.com/1567748478)    [deep\_thoughts](https://space.bilibili.com/373596439)    [五道口纳什](https://space.bilibili.com/59807853)    [ZOMI酱](https://space.bilibili.com/517221395)   [文哲](https://space.bilibili.com/472543316)

