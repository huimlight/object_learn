创新点:关于iou预测分支的类别iou预测分支


代码学习：

调试libra rcnn

mmdet复现FPT

复现多层yolof

调试yolof

了解retinanet 这两个参数意思octave_base_scale=4,scales_per_octave=3,

论文学习：

End-to-End Semi-supervised Object Detection with Soft Teacher

Object_Detection_With_Deep_Learning_A_Review

Imbalance_Problems_in_Object_Detection_A_Review

yolof

实验

梧州13结点跑face (face)(验证8卡face效果)
梧州13结点跑一组 detach为true的实验

梧州14结点跑face (face14)(验证14结点对face项目可以吗)

dgx跑faster rcnn coco 与 之前的 faster rcnn mini coco作对比

梧州15结点跑yolof (yolof15)

208跑face的alpha参数的影响 alpha 0.4

验证之前face 过滤数据之后存在的问题

----------------------------------------------------------
人脸调试

recall 和 ap都为1,看看对应那种情况

recall为1 但ap不为1的图片挑出来,看看原因是什么

recall 和 ap 都不唯一的图片挑出来,看看原因是什么

