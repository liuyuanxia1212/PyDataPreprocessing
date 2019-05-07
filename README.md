# Python数据预处理源码
> 机器学习和自然语言（QQ群号：436303759）是一个研究深度学习、机器学习、自然语言处理、数据挖掘、图像处理、目标检测、数据科学等AI相关领域的技术群。其宗旨是纯粹的AI技术圈子、绿色的交流环境。

## 本书介绍

大数据应用技术与我们日常生活密切相关，涉及到吃、穿、住、行、支付方式、智能交通等多个方面。大数据与人工智能首要解决的是数据问题，通常我们对多年积累的文档、音视频、数据库文件及其网络爬取数据统称为原始数据，这些原始数据存在不完整、不一致、有缺少值、异常值等情况，严重影响到数据建模的执行效率，甚至可能导致模型结果的偏差，因此我们要对原始数据进行预处理。数据预处理主要是将原始数据经过文本抽取、数据清理、数据集成、数据处理、数据变换、数据降维等处理后，不仅提高了数据质量，而且更好的提升算法模型性能。其在数据挖掘、自然语言处理、机器学习、深度学习算法中广泛应用。目前，市场上并没有关于数据预处理专门的书籍，数据预处理基本上以章节的形式散落在一些技术书籍之中。大家最为常见的几本数据预处理著作也停留在早期的理论阶段。市场急需一个结合前沿技术工业应用的数据预处理书籍。本书是一门基于Python语言编写的数据预处理教材。数据预处理在大数据和人工智能方面有着广泛的应用。本书结合学术理论和工程应用将循循渐进，逐步学习到数据预处理技术。习惯于数据语料的拿来主义之后，当面对新的任务时候，却不知道如何下手？有的同学在处理英语时候游刃有余，面对中文数据预处理却不知所措。基于以上几个问题，结合作者工程经验，整理出了数据预处理教材，本书主要包括以下特色：
第一，本书在创作形式方面，对工程项目进行整理所得，结合严谨的学术指导，各章节联系紧密。每章节通过导读进行目标学习，各节将技术点分割讲解，最后采用综合案例实战，力图使读者趣味学习中掌握实用技术。
第二，本书在内容方面，主要面向的是所有希望从事大数据开发的IT从业人员，要求读者具备一定的Python语言基础，适应国内市场，读者面广泛；当前市场中的同类书较少，国内外的相关教材知识点覆盖面不全。本书涵盖了实际开发中所有的重要知识点，内容详尽，代码可读性及可操作性强。
第三，本书在技术知识方面，主要包括当前流行的工业技术，其中包括：scrapy网络爬虫技术、pywin32文本抽取、yield生成器、正则清洗网页数据、清洗字符串、中文的繁简转换、缺失值 的处理、噪声数据、异常数据清洗、结巴分词精讲、HanLP精讲、停用词的处理、NLTK的安装使用、特征数据的提取、词袋模型、词集模型、词向量转化、数据均衡、语料库技术、TFIDF、特征降维、特征选择、主成分分析、可视化技术、XGBoost竞赛神器、XGBoost调参、算法性能评估和开发网络数据中的实际应用。
第四，本书在权威方面，涵盖学术带头人、一线实践工程师、一线教师等共同编著，并由学术领域专家和BAT技术工程师联合作技术顾问，指导改进而成。且本书代码齐全，读者可在GitHub上下载源码并进行交流讨论。

总之，大数据与人工智能技术炙手可热，其对应岗位也逐年增加，薪资也较为诱人。我们在做大数据与人工智能处理时候，不可避免的会遇到数据的问题。现实中的数据是不完整的，存在缺失值、干扰值等等脏数据，我们没有办法直接挖掘数据价值，也不能直接将其在人工智能设备中应用。为了提高数据挖掘的质量产生了数据预处理技术。数据预处理是一项很庞杂的工程，当你面对一堆数据举足无措的时候，当你不了解数据预处理背后坑，当你算法性能迟迟不能提升的时候。本书可以帮助你解决以上问题。

## 读者对象

在初期学习阶段，大家精力着重于算法模型和调参上。实际情况是，有时候在算法改进上花费很多功夫，却不如在数据质量上的些许提高来的明显。另外，习惯于数据语料的拿来主义之后，当面对新的任务时候，却不知道如何下手？有的同学在处理英语时候游刃有余，面对中文数据预处理却不知所措。基于以上几个问题，结合作者工程经验，整理出了数据预处理一书。此外，目前市场上数据分析和数据处理的书籍中，更多层面是具备统计背景的学者编写，很多都是基于数据采集和整理的。数据采集以后如何将数据与算法对接？如何对手上拿到的数据深加工？这就是本门课程所需要解决的问题，且对广大的学生群体、前沿技术爱好者及工作人群都是适用的。本书的特点是示例代码丰富，实用性、操作性和系统性较强，适合于大数据从业者，AI技术开发人员、培训机构及大中专教学用书。

## 本书组织

本书由三个部分12章组成，第一部分是数据预处理基础知识从第一章至第二章共计二章。主要介绍数据预处理基本概念、工作流程、应用场景、开发环境、入门演练和Python科学计算工具包Numpy、SciPy、Panda的实际应用。读者如果具备数据预处理基础，可跳过此部分。第二部分数据预处理实战进阶从第三章至第十章共计八章。第三章主要介绍数据采集与存储，涉及数据结构类型和采集方式，其中着重介绍了爬虫技术；第四章主要介绍不同格式的文本信息抽取和文件读取；第五章主要介绍了高效读取文件、正则清洗文本信息、网页数据清洗和文本批量清洗工作；第六章主要介绍了中文分词精讲、封装分词工具包、NLTK词频处理、命名实体抽取和批量分词处理工作；第七章主要介绍了特征向量化处理，其中涉及数据解析、缺失值处理、归一化处理、特征词文本向量化、词频-逆词频、词集模型、词袋模型和批量文本特征向量化工作；第八章主要介绍基于Gensim文本特征向量化，涉及构建语料词典、词频统计、词频-逆词频计算、主题模型和特征降维等。第九章主要介绍了主成分分析PCA降维技术的原理和实际案例；第十章主要介绍了matplotlib数据可视化分析案例。第三部分数据预处理实际应用从第十一章到第十二章共计二章。主要介绍竞赛神器XGBoost算法原理和应用及其如何优化调参，并结合实际案例指导调参工作；第十二章主要介绍数据预处理在文本分类中的实际应用。具体各章节内容介绍如下：

- 第1章 概述：大数据技术与我们日常生活密切相关，数据量级是大数据的前提。原始数据存在大量不完整、不一致、有异常的情况，严重影响到数据利用，甚至可能导致结果的偏差。因此，数据预处理便应运而生。本章首先做数据预处理的概述，使读者对其有个整体认识。然后介绍Python数据预处理的开发工具与运行环境，达到工欲善其事必先利其器的效果；最后综合中文分词的实战案例，让读者入门数据预处理。
- 第2章 Python 科学计算工具：Python语言及其应用，可谓如火如荼，遍地开花，读者对其并不陌生。本章主要针对科学计算工具包Numpy、SciPy、Panda和Matplotlib，分别从包的简介、安装、特点和常见方法几个方面介绍，本章知识也是后续章节的基础。合使用，无论你是做科研还是工程开发都是一把利器。
- 第3章 数据采集与存储：随着网络和信息技术的不断普及，人类产生的数据量正在呈指数级增长。数据的形式也更加丰富，主要包括结构化，半结构化，非结构化。面对以上数据形式应当采用怎么样的数据采集策略？如何实现网络爬虫抓取网页信息？如何对提取的网页信息进行本地化存储？本章将带你逐步深入。
- 第4章 文本信息抽取：通过数据采集我们获取的数据信息五花八门、杂乱无章。我们需要对不同类型的数据集成，并将集成数据传入到电脑之中，通过算法模型挖掘其潜在的价值，为智能应用做支撑。
- 第5章 文本数据清洗：数据清理指删除、更正错误、不完整、格式有误或多余的数据。数据清理不仅仅更正错误，同样加强来自各个单独信息系统不同数据间的一致性。本章着重介绍正则清洗文本数据，正则处理网页数据和正则处理简繁中文字体。最后，结合高效读取文件的方法完成批量的文本数据清洗工作。
- 第6章 文本中文分词处理：中文分词技术属于自然语言处理技术范畴，中文分词是其他中文信息处理的基础。本章首先介绍中文分词相关概念和应用，接着对停用词和词性进行剖析，最后完成30万新闻文本的批量分词处理工作。
- 第7章 文本特征向量化：特征向量化属于数据预处理重要的一部分，大家应该并不陌生。其根本目的就是将文本数据进行向量化，便于算法模型对数据处理。本章首先介绍解析特征集和标签集，以及解析数据中缺失值处理问题与对策。着重介绍下归一化处理方法，最后，我们对比词集模型和词袋模型完成新闻文本特征向量化。
- 第8章 Gensim文本向量化：Gensim一种非结构化文本处理工具包，可以便捷的构建语料库，其内置的诸多子模块可以高效的生成TF-IDF向量，并支持大数据文本批量处理。同时内置多种主题模型可以满足多种任务需求。本章采用工具实现特征向量化模型支持二次开发，大大节约数据预处理和算法模型训练时间。
- 第9章 PCA降维技术：主成分分析（英语：Principal components analysis，PCA）是一种分析、简化数据集的技术。主成分分析经常用于减少数据集的维数，同时保持数据集中的对方差贡献最大的特征。常常应用在文本处理、人脸识别、图片识别、自然语言处理等领域。可以做在数据预处理阶段非常重要的一环，本文首先对基本概念进行介绍，然后给出PCA算法思想、流程、优缺点等等。最后通过一个综合案例去实现应用。
- 第10章 数据可视化分析：在自然语言处理相关工作过程中，数据可视化的方法能够使得数据分析的结果更加一目了然，所谓一图胜千言就是这个意思。本章主要介绍数据可视化方法之一的Matplotlib操作，通过本章的学习使大家对Matplotlib操作更加轻车熟路。
- 第11章 XGBoost 竞赛神器：本章介绍一款号称竞赛神器的XGBoost，很多Kaggle（一个数据科学竞赛的平台）比赛的冠军采用的都 是XGBoost算法。此外，XGBoost近些年在学术界取得的成果连连捷报，在诸多算法模型和深度学习框架之 下，XGBoost为何如此闪光？最直接的原因是其运行速度快（以特征为单位并行处理），内置交叉验证，正则 化提升，适合不均衡数据，支持自定义优化目标和评价指标，自动处理缺失值和字符型特征，自动处理相关特 征，总之省心又省事。接下来我们从认知XGBoost到如何使用，模型参数调优等方面深入学习。 
- 第12章 XGBoost实现30万条新闻数据文本分类：随着互联网技术的快速发展，浩如烟海的文献资料和数据进行自动分类、组织和管理，已经是一个具有重要用途的研究课题。人们对数据的处理和加工得到了信息，信息在各行各业都有极为重要的地位，越来越多的用户利用互联网发布信息、获取信息。现如今，这个数据以爆炸形式增长的年代，对杂乱无章的数据分析、归类变得十分的重要。由于采用人工的方法去处理这么庞大的数据耗时耗力，于是出现了文本分类技术。前文我们一系列的数据预处理工作，面对处理后的数据如何进行工程化应用。本章将数据预处理后的新闻数据结合文本分类技术实际场景应用。

## 源码获取说明

本书的源码支持GitHUb下载[https://github.com/bainingchao/PyDataPreprocessing](https://github.com/bainingchao/PyDataPreprocessing "https://github.com/bainingchao/PyDataPreprocessing")，源码下载默认如下：

- PyDataPreprocessing：本书源代码的根目录
- Chapter+数字：分别代表对应章节的源码
- Corpus：本书所有的训练语料
- Files： 所有文件文档
- Packages：本书所需要下载的工具包

## 勘误

由于笔者能力有限，时间仓促，书中难免有错漏，欢迎读者批评指正。

本书勘误交流QQ群：947999023

AI技术交流QQ总群：436303759

## 作者介绍

> 白宁超

白宁超，男，工程师，现工作于四川省计算机研究院。主要从事大数据分析、自然语言处理和机器学习等方面的研究工作。近3年，主持和参与国家自然基金项目和四川省科技支撑计划项目3项，在核心学术期刊发表论文2篇，获得软件著作权5项，出版专著1部。

> 唐聃

唐聃，男，教授，中科院工学博士。主要从事编码理论与智能服务、领域大数据与人工智能等方面的研究工作。现为四川省学术和技术带头人后备人选，软件自动生成与智能服务四川省重点实验室副主任，2016年入选中国科学院西部之光人才计划（中国科学院西部青年学者A类）。主持省部级以上项目10余项，在国内外核心学术期刊发表论文14篇，获国家发明专利4项（授权），出版专著1部，获四川省科技进步二等奖及三等奖各一项。

> 文俊

文俊，男，大数据算法工程师，就职于成都广播电视台橙视传媒大数据中心。拥有多年丰富的工作经验，曾以技术总监身份主持研发多个商业项目，负责公司核心算法模型构建。主要研究方向包括数据挖掘、机器学习、自然语言处理、深度学习以及云计算。

> 田霖

田霖，男，大学教师，现任职于成都东软学院计算机科学与工程系。研究方向包括数据挖掘和强化学习，曾参与四川省智慧环保、四川省涉税信息等多个省级项目。

> 于小明


## 本书特色

本书源于在指导学生进行课题实验过程中，大部分精力放在算法模型和调参上，实际效果并不理想，有时候不如数据质量的提升效果明显。另外，习惯于数据语料的拿来主义之后，当面对新的任务时候，却不知道如何下手？有的同学在处理英语时候游刃有余，面对中文数据预处理却不知所措。基于以上几个问题，结合作者工程经验，整理出了数据预处理教材，本书主要包括以下特色：
第一，本书在创作形式方面，对工程项目进行整理所得，结合严谨的学术指导，各章节联系紧密。每章节通过导读进行目标学习，各节将技术点分割讲解，最后采用综合案例实战，力图使读者趣味学习中掌握实用技术。
第二，本书在内容方面，主要面向的是所有希望从事大数据开发的IT从业人员，要求读者具备一定的Python语言基础，适应国内市场，读者面广泛；当前市场中的同类书较少，国内外的相关教材知识点覆盖面不全。本书涵盖了实际开发中所有的重要知识点，内容详尽，代码可读性及可操作性强。
第三，本书在技术知识方面，主要包括当前流行的工业技术，其中包括：scrapy网络爬虫技术、pywin32文本抽取、yield生成器、正则表达式、清洗网页数据、清洗字符串、中文的繁简互相转换、缺失值 的处理、噪声数据、异常数据清洗、结巴分词精讲、HanLP精讲、停用词的处理、NLTK的安装使用、特征数据的提取、词袋模型、词集模型、词向量转化、数据均衡、语料库技术、TFIDF、主成分分析、可视化技术、XGBoost竞赛神器、XGBoost调参、算法性能评估和相关深度学习技术。
第四，本书在权威方面，本书作者涵盖学术、工程人员共同编著，之后由学术领域专家和BAT技术工程师联合作技术顾问，指导建议汇总而成。且本书代码齐全，在GitHub为读者开辟专门的讨论区，此外，各章节配有教学PPT以供大家学习。


## 开发环境说明 开发环境说明

- 开发语言: Python3.7
- 系统环境：window10 
- 编程环境：Sublime 
- 软件环境：Anaconda4.5 
- 插件版本：均支持最新版本



## 技术交流群

机器学习和自然语言（QQ群号：436303759）是一个研究深度学习、机器学习、自然语言处理、数据挖掘、图像处理、目标检测、数据科学等AI相关领域的技术群。其宗旨是纯粹的AI技术圈子、绿色的交流环境。为解决成员交流中的时间壁垒，为提高群体技术交流效率。本群倡导"AI技术视频共享"项目，纯粹的收集大家珍藏的技术视频资源，汇少成多，更多的服务大家。本群中的技术视频均由成员无偿自愿上传，以供所有共享者学习。择其部分视频供无共享者成员学习，此技术视频属于公益无偿的，仅供个人学习。不可进行商业活动，违者自行承担后果。本群禁止有违背法律法规和道德的言谈举止。群成员备注格式：城市-自命名。微信订阅号：datathinks

截止2019年4月10日经过严格视频质量审核通过的视频为8类包括Python Web技术视频3套、大数据技术视频3套、机器学习技术视频3套、深度学习技术视频8套、数据科学视频6套、数据挖掘视频2套、自然语言处理视频6套和图像处理视频2套，共计33套，约1300G。具体如下：

- Python Web技术视频
  - Django网站开发（贡献者：顽主）
  - Python Web开发完整视频（贡献者：顽主）
  - Python最新就业班（贡献者：顽主）
- 大数据技术视频
  - Hadoop44集入门视频（贡献者：数据思维）
  - Hadoop全套视频（贡献者：数据思维）
  - Hadoop实战视频（贡献者：数据思维）
- 机器学习技术视频
  - 吴恩达机器学习视频（贡献者：烟花易冷）
  - 机器学习视频（贡献者：Candymoon）
  - 2017机器学习升级（贡献者：北京-sunboy）
- 深度学习技术视频
  - Tensorflow源码级技术分享（贡献者：数据思维）
  - 深度神经网络算法全套（贡献者：流音）
  - 吴恩达深度学习视频（贡献者：烟花易冷）
  - 神经网络算法与推荐系统实战（贡献者：水上书）
  - 深度学习（贡献者：顽主）
  - 深度学习实战视频-人脸检测（贡献者：张顺）
  - Tensorflow实战视频-文本分类（贡献者：张顺）
  - TensorFlow打造唐诗生成网络（贡献者：张顺）
- 数据科学视频
  - Scrapy爬虫框架进阶课程（贡献者：数据思维）
  - 分布式爬虫实战视频（贡献者：Timothy）
  - Python数据分析与机器学习实战（贡献者：小佐）
  - 廖雪峰商业爬虫（贡献者：顽主）
  - Python量化金融项目（贡献者：顽主）
  - Python数据分析与机器学习实战（贡献者：顽主）
- 数据挖掘视频
  - 大数据数据分析与挖掘（贡献者：顽主）
  - Python3数据分析与挖掘实战（贡献者：顽主）
- 自然语言处理视频
  - 知识图谱视频（贡献者：Candymoon）
  - 自然语言处理（贡献者：微笑，向着太阳）
  - 知识图谱（贡献者：微笑，向着太阳）
  - 机器学习之自然语言处理（贡献者：大白菜）
  - 自然语言处理之序列模型（贡献者：无为而立）
  - 文本挖掘与自然语言处理（贡献者：海蓝你喜欢吗）
- 图像处理视频
  - 中科院图像处理系列课程（贡献者：顽主）
  - 2018深度学习之目标检测  （贡献者：顽主）
