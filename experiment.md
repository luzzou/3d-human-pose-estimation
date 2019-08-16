# DGCN-pose

## 1. baseline----SemGCN

8.20日：理解关键代码

------------------------------------------------------------------------------------------------------------------------

8.23日：GT + SemGCN
实现最简单的SemGCN， 以2D ground truth作为输入，回归出对应的3D joints

------------------------------------------------------------------------------------------------------------------------

8.31日：
GT + SemGCN + non-local

GT + SemGCN + non-local + residual connection

GT + SemGCN + non-local + dense connection

GT + SemGCN + non-local + residual connection + dense connection

------------------------------------------------------------------

RELU -> Leakly RELU

lr -> CosineAnnealingLR 

------------------------------------------------------------------

SH + SemGCN + non-local + dense connection

SH + ImageFeatures + SemGCN + non-local + dense connection


## 2. Updated-增大感受野

EdgeConv

deep_gcns


注意：在实验中增加FLOPs的计算
