时间：2020年12月12日  
机器学习小白一枚，目前硕士研究生一年级在读，刚接触机器学习，该项目记录了自己小白的进阶之路，基于《机器学习实战》的代码复现，并基于自己的理解修改部分代码。  
目前已经写过基于KNN的手写数字识别和Logistic Regression的代码。  
手写数字识别代码改动较大，因为不了解原作者使用了何种方法处理的32*32的文本文档，原始文件的文本特征太“单一”，导致自己手写数字上传之后正确率为0。于是自己把原先的txt文件进行了处理（先讲全为0的行列删除，然后使用最近邻插值对原图像插值重新扩充为32*32的文本），然后把上传的图片也处理成相同的文本，最后进行预测。不过正确率仍然只有60%，应该是训练样本太小的原因。  
