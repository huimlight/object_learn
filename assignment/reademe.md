创新点:关于iou预测分支的类别iou预测分支

创新点2：关于人脸半监督学习

实验设想：1% 5% 划分数据集(按照半监督coco来)

在加载预训练模型下与不加载预训练模型下的实验对比

代码学习：

调试libra rcnn

mmdet复现FPT

复现多层yolof

调试yolof

了解retinanet 这两个参数意思octave_base_scale=4,scales_per_octave=3,

论文学习：

Object_Detection_With_Deep_Learning_A_Review

Imbalance_Problems_in_Object_Detection_A_Review


实验

梧州13结点跑一组 detach为true的实验

dgx跑faster rcnn coco 与 之前的 faster rcnn mini coco作对比

验证之前face 过滤数据之后存在的问题

----------------------------------------------------------
人脸调试

将 train 和 val的图片进行统计,把recall 和 ap 不都是1的图片组成新的数据

-------------------------------------------------------------------
用pandas进行分析

