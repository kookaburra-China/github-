#### 一、Git与Github ﻿00:05﻿

##### 1. Git ﻿00:10﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-1?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-u3G1h%2FAp0QMtFNBSfawr8AmjViE%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-3f69307f560d567ac6f9ccfa562c77f9f13a3cf0425a6d1beacf8260501cc1f405024af60c1a9dbfa690e784fed7959b9d50f7026cffb5e6305a5e1275657320&expires=8h&r=522771619&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-1&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-1&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=718800a01e5121ca56afef5411c6cb25f9e3e4c4c9764544305a5e1275657320&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 定义: Git是一个开源免费的软件。
- 功能: Git的主要功能是版本控制。

###### 1）版本控制 ﻿00:13﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-2?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-jYKn2Dczm%2BNRUzd8aVoNB9P8V48%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-195b699ed309e64b934d8580af97f5667f11f9f3139c92774134a5bb0f158b3fc02c9574a4c3c19526ad09430de123ff132d550a852504ec305a5e1275657320&expires=8h&r=181395882&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-2&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-2&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=718800a01e5121ca020d2a5e6e5fb2b705a1af5617752771&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 示例: 论文写作过程中，会有第一版、第二版、第三版等多个版本，保存这些版本以应对突发情况，如找回历史版本的某个段落。
- 原始方式: 最原始的版本控制是纯人工方式，对于大型项目和多人协同开发，这种方式无法负担。

###### 2）提交 ﻿01:24﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-3?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-9HN1po9OSvM9XDJx5Pys7a7SEn0%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-5b5e40f929e6e6fc0a70314ec0520e862acdf2a03bff4f38c3b97916824f7451f270b0e55a61a5ba7bbd9eab76c77dd9fb175b6f63491d17305a5e1275657320&expires=8h&r=722032651&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-3&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-3&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=2a0349c66f068e0f8925277fca57b5b2d030e9dde0acac29&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 基本单元: Git使用commit（提交）作为版本控制的基本单元。
- 快照记录: 每完成一次commit，Git都保存一个仓库此时状态的快照，记录文件夹里所有文件的状态。
- 历史链路: 随着commit的增多，会形成一条commit的历史链路，整个仓库变得可回溯。

###### 3）仓库分类 ﻿01:48﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-4?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-N%2BO55p6cD%2BB4QgNhfW1n%2FnmqMus%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-26983fe46bdc035d2c13f33a51c7c05693e8cd6bdb4a1a7f73301e7cff8181a82f071502d9f19bbf1de75cdf75c38e9e5c6e01b06d934835305a5e1275657320&expires=8h&r=496906414&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-4&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-4&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=12146e4ffd7df3c94d0fd3222e69667c05a1af5617752771&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)

- 分类: Git的仓库分为本地仓库（Local Repository）和远端仓库（Remote Repository）。

- 远端仓库 

  01:52

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-5?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-M2haDILSx%2FRu27QtzDcnQNizsD8%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-9df4ec7cc7ecddaf705b6d9943e88846bb763eca03d99f83793c2deba48b945e345f38a572a4a24819fb36c837a5d5130bf61b23e74a3f73305a5e1275657320&expires=8h&r=990881051&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-5&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-5&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=12146e4ffd7df3c9bc45b0a936301765f9e3e4c4c9764544305a5e1275657320&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)

##### 2. Github ﻿02:34﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-6?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-NLA9vJNNoirx8jejPm6GaEAVhOw%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-b9c6554d1f9e46da2275796d9e2714a12cb87c1d65c3da256c6bbfcb1d281542b014adf14f97edb290e826ca57029d516dcf004eb5ea447a305a5e1275657320&expires=8h&r=934893208&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-6&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-6&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=83f2b583554fba15962799e45bad74b305a1af5617752771&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 定义: GitHub是一个免费提供远端仓库的网站，名字中的“HUB”意为中心、汇聚，是git仓库的集合。
- 功能: GitHub是全球最大的代码仓库托管与协作平台，可以存储、分享代码，并与他人一起编写代码。

###### 1）仓库分类 ﻿03:26﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-7?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-GSLk%2BhUKTdMOXyR647sGK8DlBZ0%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-8886d63a13dee66f44efa9a9ed220c22235d6db84dbadd6961787410aed1d383a2d0fd55c7e8aabe43227e0859b030ecec210edf5137858f305a5e1275657320&expires=8h&r=632044931&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-7&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-7&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=875e0ff32ac7bd89d661990646758ae005a1af5617752771&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 分类: GitHub上的仓库分为公开仓库和私有仓库。
- 公开仓库: 所有公开仓库都可以被搜索到，且开放源代码，任何人都可以浏览学习其中的代码。

###### 2）世界最大的开源社区 ﻿03:43﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-8?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860545&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-wu1CXMHky28aLH7LOy41QFgY%2F2A%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-8b0d6bcc1530c4bf218cefaa6d0b7b3a3eae0e50e5ed1a52d43cc5128b7755217e27857d4c445f8761541c2082652cbf5545c8f76731d62e305a5e1275657320&expires=8h&r=852645714&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-8&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-8&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=b3434a369726e9249598d5fd5939298962e58b51964f6c90978956776b5d738c&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 地位: GitHub也是世界上最大的开源社区，许多著名项目如Linux操作系统、CPython（Python的C语言解释器）等都托管在GitHub上。
- 开源重要性: 开源是计算机科学的基石与瑰宝，大部分软件都是在开源软件基础上进行二次开发或依赖开源软件。

##### 3. Github加速 ﻿04:11﻿

###### 1）Watt Toolkit ﻿04:22﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-9?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860546&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-h%2BEjDUqcF91jNhpTCv8Zq%2BkX7jI%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-4178444695bb46356b2eb6b8e32033233766b1a63c4e2af343b0f4d15f3d47bb990c1fb1057d8facb2532a4ba44e25eca1c86f21d339beaa305a5e1275657320&expires=8h&r=180191150&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-9&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-9&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=1524a5cd531d02e5d5c5445e5877de9ef9e3e4c4c9764544305a5e1275657320&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 工具: Watt Toolkit（原名Steam++）是一个开源跨平台的多功能工具箱。
- 安装: 在浏览器输入steampp.net，找到适合自己操作系统的版本下载并安装。
- 加速步骤: 安装好后右键以管理员身份运行，选择左侧的“加速GitHub”，点击一键加速即可。

###### 2）dev-sidecar ﻿05:03﻿

- ![img](https://bjbgp01.baidupcs.com/file/p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-10?bkt=en-3de6f374fcad9f514a94920d227b7f50&fid=282335-250528-&time=1742860546&sign=FDTAXUVGEQlBHSKfWqij-GBWOGYTBgG0KqHy7wNbwoLTVMyJyK6xE-vyVy9ytXH8GgVbiuDib4A3ZK774%3D&to=75&size=10&sta_dx=10&sta_cs=0&sta_ft=&sta_ct=7&sta_mt=7&fm2=MH%2CBaoding%2CAnywhere%2C%2C%E6%B9%96%E5%8C%97%2Cpbs&ctime=0&mtime=0&dt3=0&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=10&vuk=0&iv=2&vl=0&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-b5b5dea85b75bcc5ed8e741fa6beee0640c30d63fc04057fbdb19802b0347f440cf51510a53e87678ba50d3144004bb530d83493dd0811e2305a5e1275657320&expires=8h&r=548107525&vbdid=-&fin=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-10&fn=p-51f03c9923bf4506fb5cf996cbb41c2e-40-2025032100-10&rtype=1&dp-logid=8850195890903779677&dp-callid=0.1&hps=1&tsl=0&csl=0&fsl=-1&csign=dmayhhcqdS1jXSxjkf6DN1P7N8o%3D&so=0&ut=1&uter=-1&serv=-1&uc=3766977543&ti=66239664855e8068c32f23017ea016b062e58b51964f6c9054086130d5ff933c&hflag=30&from_type=&adg=n&reqlabel=250528_n_c3bfaaef2c1be3deab947c44a2a4be4e_0_edf74c5f754ecb119c9a3a2091e04c14&chkv=5&bid=250528&by=themis)
- 项目: dev-sidecar是一个开发者边车项目，用于解决GitHub访问加速等问题。
- 搜索与安装: 在GitHub首页搜索dev-sidecar项目，找到后点击进入，下载最新版本的安装包（如1.8.3版本）。
- 安装与证书: 安装完成后打开软件，第一步需点击安装根证书，按照向导将证书添加到受信任的根证书颁发机构。
- 效果: 安装证书并完成设置后，访问GitHub的速度会有显著提升。

#### 二、知识小结

| 知识点                  | 核心内容                                                     | 考试重点/易混淆点               | 难度系数 |
| ----------------------- | ------------------------------------------------------------ | ------------------------------- | -------- |
| git与git HUB介绍        | git：开源免费的版本控制软件；git HUB：提供远端仓库的网站     | git与git HUB的关系及各自功能    | 🌟        |
| 版本控制的重要性        | 解决项目文件多版本管理问题，提高协同开发效率                 | 版本控制的基本概念与重要性      | 🌟        |
| git的基本功能           | 文件夹被git管理后变为git仓库，使用commit作为版本控制的基本单元 | git仓库与commit的概念           | 🌟🌟       |
| git仓库类型             | 本地仓库（local repository）与远端仓库（remote repository）  | 本地仓库与远端仓库的区别与联系  | 🌟🌟       |
| git HUB的功能           | 提供免费远端仓库，是代码仓库托管与协作平台                   | git HUB作为远端仓库的作用       | 🌟        |
| git HUB的开源社区价值   | 世界上最大的开源社区，大量开源项目托管于此                   | 开源软件的重要性与git HUB的价值 | 🌟🌟       |
| 国内访问git HUB加速方法 | 方法一：使用what工具箱加速；方法二：安装开发者边车软件       | 加速方法的操作步骤与注意事项    | 🌟🌟🌟      |
| git HUB的注册与使用     | 在git HUB上注册账号，准备开始使用                            | 注册账号的步骤与后续学习方向    | 🌟        |
| git HUB主要界面讲解预告 | 下一节将深入讲解repository（代码仓库）界面                   | 预告下一节的学习内容            | 🌟        |