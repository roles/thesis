# 基于深度学习的癌症分类模型研究

## 第一章

### 1.1 课题意义

#### 1.1.1 癌症治疗的研究现状及癌症基因组学

癌症作为一个重要的健康问题，在发达国家中已经成为了第二大致死病因，其致病原因主要与老龄化和人们生活习惯密切相关。
对于癌症治疗，早期诊断、全球性的医疗帮助和癌症疗法的发展都使得癌症病人的存活率显著的提升， 如今，患有各种不同癌症的病人有接近三分之二能够得以最终治愈。
在癌症传统的治疗手段中，手术切除是一种针对局部肿瘤的有效治疗方法，而20世纪20年代的出现的放射治疗和40年代出现的化学治疗等多种手段使得癌症治疗的方式更多样、更有效。[11]

另一方面，科学家们提出了癌症基因组学的理论，开始了从DNA遗传序列突变的角度对癌症发病机理进行研究。
在癌症基因组学的理论中，癌症细胞中的DNA遗传序列的细微改变会导致细胞产生蛋白质不能正常地工作， 这些蛋白质会使得细胞极其迅速地生长，并且对邻近的细胞造成伤害，从而损害人类的生理机能，导致疾病的产生。
通过研究这些癌症基因突变，科学家们可以发现DNA序列中的哪些变化对应了哪些癌症细胞的变化，有助于识别同一癌症的不同子型（如HER2+的乳腺癌子型）和针对患者提供最有效的个性化治疗。
随着人类基因组计划的进行，科学家们开始从基因组突变的层面上去研究癌症的发病机理、指导癌症治疗药物的研发，癌症基因组学正成为癌症治疗研究的主流方向。

#### 1.1.2 基因组测序技术的发展及对癌症治疗研究的意义

在过去几年中，DNA测序技术的发展使得基因组研究领域发生了革命性的改变，快速且低成本地产生大量的测序数据变得可行。
通过使用当前的高通测序设备，过去人类基因组计划[]用了超过13年的时间、耗费百万美元所获得的测序数据，如今只需用费数万美元、在几周之内即可获得。
测序成本的大幅降低意味着更多的研究者可以获取到DNA测序数据，促使癌症基因组学的蓬勃发展。
面对海量的DNA测序数据，科学家们采用各种统计归纳和机器学习的算法进行数据挖掘，从单基因研究的角度逐步扩展到多基因乃至全基因组的全局研究，
在更高层次上挖掘不同癌症的深层致病模式，对癌症基因组的研究产生了深远的影响。[3]

#### 1.1.3 癌症分类模型及致病机理研究

癌症分类是癌症基因组测序数据的一个重要应用。
癌症分类模型混合使用了多种DNA测序数据， 其中包括基因突变数据（Mutant)，拷贝数变化（Copy Number），DNA甲基化（DNA Methylation）等。
模型针对不同的数据类型分别进行合理的预处理，将病人对应的经过预处理的测序数据输入到模型中训练调整模型参数，反复训练以得到合理的分类结果。
通过基于海量癌症病人的DNA测序数据构造出的分类系统，可根据测试者DNA测序数据给出其患各种癌症的概率预测，对癌症患病作出智能评估，为癌症早期诊断数据支撑。

另一方面，在最近几年，很多癌症测序研究的论文得出了不同癌症产生其重要作用的驱动基因（Driver Gene），这些驱动基因的突变率明显的高于被动基因（Passenger Gene），
并且往往在蛋白质作用变化中起主要作用。
因此，根据测序数据进行分析，构造统计归纳模型，寻找各种癌症的致病关键的驱动基因以及不同癌症间共有的致病模式，正逐渐成为科学家们对癌症研究的新方向。



## 参考文献

1. Genome sequencing in microfabricated high-density picolitre reactors
2. Cancer genome sequencing: a review
3. Understanding and improving high-throughput sequencing data production and analysis
4. Cancer risk prediction models: a workshop on development, evaluation, and application
5. History of Cancer, Ancient and Modern Treatment Methods
6. Identifying cancer driver genes in tumor genome sequencing studies.
7. 基于基因表达秩序关系识别癌症预后与早期诊断标志
8. 基于支持向量机算法的癌症预测
9. Cancer classification by gradient LDA technique using microarray gene expression data
10. A colorectal cancer classification system that associates cellular phenotype and responses to therapy
11. Recent Advances in Cancer Therapy: An Overview

## 关键词
`癌症早诊早治项目`
