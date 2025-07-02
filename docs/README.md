[![GitHub issues](https://img.shields.io/github/issues/datawhalechina/easy-rl)](https://github.com/datawhalechina/easy-rl/issues) [![GitHub stars](https://img.shields.io/github/stars/datawhalechina/easy-rl)](https://github.com/datawhalechina/easy-rl/stargazers) [![GitHub forks](https://img.shields.io/github/forks/datawhalechina/easy-rl)](https://github.com/datawhalechina/easy-rl/network) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdatawhalechina%2Feasy-rl%2F&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) ![Downloads](https://img.shields.io/github/downloads/datawhalechina/easy-rl/total)
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a>


# 蘑菇书EasyRL

李宏毅老师的《深度强化学习》是强化学习领域经典的中文视频之一。李老师幽默风趣的上课风格让晦涩难懂的强化学习理论变得轻松易懂，他会通过很多有趣的例子来讲解强化学习理论。比如老师经常会用玩 Atari 游戏的例子来讲解强化学习算法。此外，为了教程的完整性，我们整理了周博磊老师的《强化学习纲要》、李科浇老师的《世界冠军带你从零实践强化学习》以及多个强化学习的经典资料作为补充。对于想入门强化学习又想看中文讲解的人来说绝对是非常推荐的。

本教程也称为“蘑菇书”，寓意是希望此书能够为读者注入活力，让读者“吃”下这本蘑菇之后，能够饶有兴致地探索强化学习，像马里奥那样愈加强大，继而在人工智能领域觅得意外的收获。

## 使用说明

* 第 4 章到第 11 章为[李宏毅《深度强化学习》](http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLDS18.html)的部分；
* 第 1 章和第 2 章根据[《强化学习纲要》](https://github.com/zhoubolei/introRL)整理而来；
* 第 3 章和第 12 章根据[《世界冠军带你从零实践强化学习》](https://aistudio.baidu.com/aistudio/education/group/info/1335) 整理而来。


ℹ️ **勘误修订表**：https://datawhalechina.github.io/easy-rl/#/errata

## 在线阅读(内容实时更新)

地址：https://datawhalechina.github.io/easy-rl/

## 最新版PDF下载

地址：https://github.com/datawhalechina/easy-rl/releases

国内地址(推荐国内读者使用)：链接: https://pan.baidu.com/s/1isqQnpVRWbb3yh83Vs0kbw 提取码: us6a

压缩版(推荐网速较差的读者使用，文件小，图片分辨率较低)：链接: https://pan.baidu.com/s/1mUECyMKDZp-z4-CGjFhdAw 提取码: tzds 


## 内容导航

| 章节                                                         | 习题                                                         | 相关项目                                                     | 配套代码                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [第一章 强化学习基础](https://datawhalechina.github.io/easy-rl/#/chapter1/chapter1) | [第一章 习题](https://datawhalechina.github.io/easy-rl/#/chapter1/chapter1_questions&keywords) |                                                              |                                                              |
| [第二章 马尔可夫决策过程 (MDP)](https://datawhalechina.github.io/easy-rl/#/chapter2/chapter2) | [第二章 习题](https://datawhalechina.github.io/easy-rl/#/chapter2/chapter2_questions&keywords) |                                                              | [值迭代算法](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/Value%20Iteration/value_iteration.ipynb) |
| [第三章 表格型方法](https://datawhalechina.github.io/easy-rl/#/chapter3/chapter3) | [第三章 习题](https://datawhalechina.github.io/easy-rl/#/chapter3/chapter3_questions&keywords) | [Q-learning算法实战](https://datawhalechina.github.io/easy-rl/#/chapter3/project1) | [Q-learning](https://github.com/datawhalechina/easy-rl/tree/master/notebooks/Q-learning)，[Sarsa](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/Sarsa.ipynb)，[蒙特卡洛](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/MonteCarlo.ipynb) |
| [第四章 策略梯度](https://datawhalechina.github.io/easy-rl/#/chapter4/chapter4) | [第四章 习题](https://datawhalechina.github.io/easy-rl/#/chapter4/chapter4_questions&keywords) |                                                              | [策略梯度](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/PolicyGradient.ipynb) |
| [第五章 近端策略优化 (PPO) 算法](https://datawhalechina.github.io/easy-rl/#/chapter5/chapter5) | [第五章 习题](https://datawhalechina.github.io/easy-rl/#/chapter5/chapter5_questions&keywords) |                                                              | [PPO](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/PPO.ipynb) |
| [第六章 DQN (基本概念)](https://datawhalechina.github.io/easy-rl/#/chapter6/chapter6) | [第六章 习题](https://datawhalechina.github.io/easy-rl/#/chapter6/chapter6_questions&keywords) |                                                              | [DQN](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/DQN.ipynb) |
| [第七章 DQN (进阶技巧)](https://datawhalechina.github.io/easy-rl/#/chapter7/chapter7) | [第七章 习题](https://datawhalechina.github.io/easy-rl/#/chapter7/chapter7_questions&keywords) | [DQN算法实战](https://datawhalechina.github.io/easy-rl/#/chapter7/project2) | [Double DQN](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/DoubleDQN.ipynb)，[Dueling DQN](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/DuelingDQN.ipynb)，[PER DQN](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/PER_DQN.ipynb)，[Noisy DQN](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/NoisyDQN.ipynb) |
| [第八章 DQN (连续动作)](https://datawhalechina.github.io/easy-rl/#/chapter8/chapter8) | [第八章 习题](https://datawhalechina.github.io/easy-rl/#/chapter8/chapter8_questions&keywords) |                                                              |                                                              |
| [第九章 演员-评论员算法](https://datawhalechina.github.io/easy-rl/#/chapter9/chapter9) | [第九章 习题](https://datawhalechina.github.io/easy-rl/#/chapter9/chapter9_questions&keywords) |                                                              | [A2C](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/A2C.ipynb) |
| [第十章 稀疏奖励](https://datawhalechina.github.io/easy-rl/#/chapter10/chapter10) | [第十章 习题](https://datawhalechina.github.io/easy-rl/#/chapter10/chapter10_questions&keywords) |                                                              |                                                              |
| [第十一章 模仿学习](https://datawhalechina.github.io/easy-rl/#/chapter11/chapter11) | [第十一章 习题](https://datawhalechina.github.io/easy-rl/#/chapter11/chapter11_questions&keywords) |                                                              |                                                              |
| [第十二章 深度确定性策略梯度 (DDPG) 算法](https://datawhalechina.github.io/easy-rl/#/chapter12/chapter12) | [第十二章 习题](https://datawhalechina.github.io/easy-rl/#/chapter12/chapter12_questions&keywords) | [DDPG算法实战](https://datawhalechina.github.io/easy-rl/#/chapter12/project3) | [DDPG](https://github.com/datawhalechina/easy-rl/blob/master/notebooks/DDPG.ipynb) |
| [第十三章 AlphaStar 论文解读](https://datawhalechina.github.io/easy-rl/#/chapter13/chapter13) |                                                              |                                                              |                                                              |
| [视觉强化学习论文清单（Awesome Visual RL）](https://github.com/qiwang067/awesome-visual-rl) |                                                              |                                                              |                                                              |
## 算法实战

算法实战部分包括附书代码和JoyRL代码：

* [蘑菇书附书代码](https://github.com/datawhalechina/easy-rl/tree/master/notebooks)
* [JoyRL离线版](https://github.com/johnjim0816/rl-tutorials/tree/master/joyrl)
* [JoyRL上线版](https://github.com/datawhalechina/joyrl)

## 经典强化学习论文解读

[点击](https://github.com/datawhalechina/easy-rl/tree/master/papers)或者网页点击```papers```文件夹进入经典强化学习论文解读

## 扩展资源
- 对**强化学习玩我的世界（Minecraft）游戏**感兴趣的读者，可阅读 [LS-Imagine](https://github.com/qiwang067/LS-Imagine)
- 对**视觉强化学习**感兴趣的读者，可阅读[Awesome Visual RL](https://github.com/qiwang067/awesome-visual-rl)
- 对**深度学习**感兴趣的读者，可阅读[李宏毅深度学习教程LeeDL-Tutorial](https://github.com/datawhalechina/leedl-tutorial)

## 相关视频内容

* [《Datawhale强化学习教程》出版](https://www.bilibili.com/video/BV1rb4y1x7Zd/?spm_id_from=333.999.0.0&vd_source=642fa389e9e78cff4881c038963ac312)
* [蘑菇书起源与RL入门指南](https://www.bilibili.com/video/BV1HZ4y1v7eX/?spm_id_from=333.999.0.0&vd_source=642fa389e9e78cff4881c038963ac312)
* [蘑菇书开源组队学习活动](https://www.bilibili.com/video/BV1Ha41197Pg/?spm_id_from=333.999.0.0&vd_source=642fa389e9e78cff4881c038963ac312)
* [蘑菇书开源学习与成长](https://www.bilibili.com/video/BV1xW4y1B72o/?spm_id_from=333.999.0.0&vd_source=642fa389e9e78cff4881c038963ac312)

## 引用信息

```
王琦，杨毅远，江季，Easy RL：强化学习教程，人民邮电出版社，https://github.com/datawhalechina/easy-rl, 2022.
Qi Wang, Yiyuan Yang, Ji Jiang，Easy RL: Reinforcement Learning Tutorial，Posts & Telecom Press，https://github.com/datawhalechina/easy-rl, 2022.
```

```bibtex
@book{wang2022easyrl,
title = {Easy RL：强化学习教程},
publisher = {人民邮电出版社},
year = {2022},
author = {王琦，杨毅远，江季},
address = {北京},
isbn = {9787115584700},
url = {https://github.com/datawhalechina/easy-rl}
}
```

```bibtex
@book{wang2022easyrl,
title = {Easy RL: Reinforcement Learning Tutorial},
publisher = {Posts & Telecom Press},
year = {2022},
author = {Qi Wang, Yiyuan Yang, Ji Jiang},
address = {Beijing},
isbn = {9787115584700},
url = {https://github.com/datawhalechina/easy-rl}
}
```

如果您需要转载该教程的内容，请注明出处：[https://github.com/datawhalechina/easy-rl](https://github.com/datawhalechina/easy-rl)。



## LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。
