# CSQAQ
scratch images, other information from CSQAQ

**Dataset Statistics[3]**
| Statistic | Non-rumors | FalseRumors | Images | Users | Comments |
|-----------|-----------|-------------|--------|-------|----------|
| PHEME[1]     | 1428      | 590         | 2018   | 894   | 242761 + 114320 = 357081     |
| Weibo[2]     | 877      | 590         | 1467   | 985   | 24740 + 9167 = 33907     |

文件夹 dataset/weibo/weibocontentwithreactions_relation/non_rumor/ 下的所有推文的评论数总数：242761
<br> 文件夹 dataset/weibo/weibocontentwithreactions_relation/rumor/ 下的所有推文的评论数总数：114320
<br> 文件夹 dataset/pheme/phemecontentwithreactions_relation/non_rumor/ 下的所有推文的评论数总数：24740
<br> 文件夹 dataset/pheme/phemecontentwithreactions_relation/rumor/ 下的所有推文的评论数总数：9167

**Dataset Statistics[4]**
| Dataset | Real News | Fake News | Images | Comments  |
|---------|----------|-----------|--------|-----------|
| PHEME   | 1520     | 623       | 2143   | 37,174    |
| Weibo   | 877      | 590       | 1467   | 334,794   |

* 数据集来源：
<br>[1].Changhe Song, Cheng Yang, Huimin
 Chen, Cunchao Tu, Zhiyuan Liu, and Maosong Sun.
 Ced: Credible early detection of social media rumors.
 IEEE Transactions on Knowledge and Data Engineering,
 33(8):3035–3047, 2019.
<br> [2].Arkaitz Zubiaga, Maria Liakata, and
 Rob Procter. Exploiting context for rumour detection in
 social media. In International Conference on Social Infor
matics, pages 109–123. Springer, 2017.
<br> [3].Zheng J, Zhang X, Guo S, et al. MFAN: 
Multi-modal Feature-enhanced Attention Networks for Rumor 
Detection[C]//IJCAI. 2022, 2022: 2413-2419.

引用[3]使用了这两个数据集, 这两个数据集的特点是包含评论(真实的评论, 其它方法所用的数据集不一定会涉及到真实的评论)
<br> 后续的工作可以考虑 LLM 的 Role-play 来生成一定的评论, 以便用于 Fake News 的 Early Detection!
