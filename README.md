# -一个参考算卦的随机数生成模块。

目前版本内容
---
模拟金钱起卦的过程，得到六爻卦，以及对应的成功概率参考值、解卦资料。

吉凶&成功概率
---
吉凶为经验上的吉卦、凶卦。

'吉':1,'中吉':0.75,'平':0.5,'中和':0.5,'吉凶參半':0.5,'困':0.5,'中兇':0.25,'凶':0,'兇':0

主爻所占比例p为变量，成功概率=主爻×p+副爻×(1-p)。

解卦资料
---
内含卦和爻的《易经》原文，白话文，解释，可以人工解读，对生成的吉凶结果进行合理调整。

规划
---
研究六十四卦具体内容，细化卦对应的参数。
* 例如说一样是吉卦，乾卦的“大吉大利”看上去就好像比坤卦的“厚德载物”更顺利一点。

