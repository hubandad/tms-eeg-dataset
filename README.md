### Public TMS-EEG Dataset



**经颅磁刺激**（Transcranial Magnetic Stimulation, TMS）技术是一种基于电磁感应与电磁转换原理的神经调控技术，它具有无痛，绿色，安全等特点。自诞生起的二十多年间，TMS在临床和科研中都具有非常广泛的应用。它的问世，无疑将神经功能的干预，调制和治疗提升到一个新的高度。 

**脑电图**（Electroencephalography, EEG）是一种记录活体大脑神经元活动时所产生的电位活动的技术，脑电图在临床诊疗和科研中得到非常广泛的应用，且应用技术十分成熟。 

同步经颅磁脑电（TMS-EEG）将这两种强大的技术结合，这种结合也使得科研工作者成功发现了经颅磁在对大脑起调控作用时，脑内神经元所发生的微观变化。关于TMS-EEG技术更系统的综述研究，可参考frontiers in Neural Circuits中的这篇题为《Characterizing and Modulating Brain Circuitry through Transcranial Magnetic Stimulation Combined with Electroencephalography》的文献。 

以下数据集整理自互联网，供各位作为参考。

***

**1. TESA 工具箱样例数据**

TESA（TMS-EEG signal analyser）工具箱是一个eeglab下的开源扩展插件，该插件集成了众多TMS-EEG数据预处理和分析的函数，功能非常强大。 

今天介绍的这一例数据是由蒙纳士大学克莱顿分校的TESA工具箱作者 Dr. Nigel Rogasch分享的。该数据包含一名受试者在左上侧顶叶接受神经导航引导下的单相TMS时的EEG数据。

访问TESA主页，了解更多信息：https://nigelrogasch.github.io/TESA/ 

TESA example data 获取地址：https://figshare.com/articles/TESA_example_data_and_scripts/3188800 

P.s 另一个被广泛用来分析TMS-EEG数据的工具箱  TMSEEG toolbox http://www.tmseeg.com/ 

***

**2. 不同布鲁德曼分区的TEPs数据**

4例单试次TEP（Electroencephalographic Potentials Evoked by Transcranial Magnetic Stimulation）数据，分别对应了四个不同的布鲁德曼分区（BA4/BA6/ /BA7/BA19）。
所有数据都经过预处理。

数据集详细介绍及获取地址：https://data.mendeley.com/datasets/hzjrks365b/1 

***

**3. TEPs-MEPs数据集**

同样是来自蒙纳士大学克莱顿分校的研究者（Mana Biabani）贡献的 TEP和MEP数据，该数据集包含在运动皮层进行TMS时的MEP和TEP数据，所有数据已经预处理，不过可以联系Mana获取原始数据。

参考文献：Mana Biabani, Alex Fornito, James P. Coxon, Ben D. Fulcher, Nigel C. Rogasch. The correspondence between EMG and EEG measures of changes in cortical excitability following transcranial magnetic stimulation. 

数据集详细介绍：https://researchdata.edu.au/teps-meps/1424449  

数据库获取地址：https://bridges.monash.edu/articles/dataset/TEPs-MEPs/8251799 

***

**4. Nature scientific data 数据集**

2016年发表在nature scientific data的一项用于探究双稳态知觉任务中顶叶功能分区的TMS-EEG研究，该研究使用TMS-EEG技术探索顶叶皮层的功能分区，TMS的选择性干预特点，暂时激活或抑制某一功能区的功能，可以很好地区分大脑不同分区的功能特点。该研究采集了16名受试者在接受sTMS时的EEG数据，以及同步MRI数据。

参考文献：Schauer, G. et al. Fractionation of parietal function in bistable perception probed with concurrent TMS-EEG. Sci. Data 3:160065 doi: 10.1038/sdata.2016.65 (2016).  

文章获取链接：https://www.nature.com/articles/sdata201665 

数据集获取链接：https://zenodo.org/record/4990628 

***

**5. TMS-EEG 用于大脑皮质研究的数据集**

先前的研究证据表明，大脑不同皮层皮质区域有不同的神经元振荡活动。在一篇发表在预印本网站bioRxiv的研究中，研究者为了探索在静息态和任务态下大脑皮层神经元活动的频率是否会发生变化，使用TMS-EEG技术，扰乱受试者大脑右半球的三个区域的振荡活动，并给予相应的任务，测量健康人受试者在静息态（N=12）和任务态(N=12)下三个TMS脑区和任务态激活脑区的神经振荡活动频率变化。研究发现，当大脑在积极主动参与到一项任务时，会采用更高的，且占据主导频率的模式工作，无论使用TMS刺激哪个脑区，在任务期间诱发的频率在整个皮质区域都占据主导地位。此项研究的24例TMS-EEG数据已共享到开源社区。

参考文献：Stanfield-Wiswell, C., & Wiener, M. (2019). Subject Raw Data [Data set]. figshare. https://doi.org/10.6084/M9.FIGSHARE.8052953.V4  

数据库获取：https://figshare.com/articles/dataset/Participant_Raw_Data/8052953 

***



#### The End
