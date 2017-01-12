# 集成学习之Boosting
> Boosting是一族可將弱学习器提升为强学习器的算法。这族算法的工作机制类似：先从厨师训练集训练出一个基学习器，再根据基学习器的表现对训练样本分布进行调整，使得先前基学习器做错的训练样本在后续受到更多关注，然后基于调整后的样本分布来训练下一个基学习器；如此重复进行，直至基学习器数目达到事先指定的值T，最终将这T个基学习器进行加权结合。

- [Adaboost](./adaboost.ipynb) 以决策树桩为基学习器