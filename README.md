# ASR_WORD
采用端到端方法构建声学模型，以字为建模单元，采用DCNN-CTC网络结构。

1.必要的库
  python 3.x
  keras 2.0
  Tensorflow 1.8.0
  numpy
  wave 
  python_speech_features
  random
  os
  scipy
  difflib

2.运行要求
  由于数据较大，程序的实验数据可以从 http://www.openslr.org/18/ 下载，在此感谢清华大学对语音识别领域的贡献；
  下载完成解压后放在程序的同级目录；
  程序不仅是对中文语音识别声学模型以字为建模单元的的构建，而且为英文语音识别以字为建模单元提供一定的指导意义；
  欢迎各位朋友提出宝贵建议；交流QQ群：737145025

3.项目要求
  本程序感谢江南大学、西安电子科技大学、湘潭大学等众多高校合作完成，目前程序采用的是Thchs30数据集为基础数据集，采用的深度卷积神经网络与连接时序分类损失函数构建端到端语音识别声学模型，由于数据只有30h左右，目前的识别字错误率在85-90%左右，后续开发者可以在此基础模型上增加数据，改进模型，修改预处理方案等改进声学模型的准确率；
  具体的数据可以从 http://www.openslr.org/ 下载数据集进行数据扩充，具体有STCMDS、Aishell-01、Aishell-02等中文数据集；
  由于脚本申请版权保护，学术使用免费，商用请联系本人QQ :76859420或者项目组长伍哥 QQ：1840658279;
  欢迎各位朋友对本程序提出宝贵建议；交流QQ群：737145025
