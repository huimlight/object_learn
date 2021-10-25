## widerface



-------------------------------------------------------

## 标注问题

找到没有标注的图片的目的：查看模型的FP有多高

#### WIDER_train中没有标注

0_Parade_Parade_0_452

2_Demonstration_Political_Rally_2_444

39_Ice_Skating_iceskiing_39_380

46_Jockey_Jockey_46_576

#### WIDER_val中没有标注

0_Parade_Parade_0_275

7_Cheering_Cheering_7_426  此张由于标注质量,影响了mAP的计算

37_Soccer_soccer_ball_37_281

50_Celebration_Or_Party_houseparty_50_715

----------------------------------------------------------

## WIDERR_val_ap=1

该目录选取了几张图片,用于mAP的调试.调试的时候可以自由修改val.txt,调试不同的情况.

## recall=1/ap=1

59_peopledrivingcar_peopledrivingcar_59_244,
1_Handshaking_Handshaking_1_107,这张图片有gt=1/4,检测dets>>1,ap=1

## recall=1/ap!=1

31_Waiter_Waitress_Waiter_Waitress_31_212,这张图片gt=1,检测dets>>1

结论：通过调试发现,如果TP的分数高于FP,ap=1. 如果FP的分数大于TP,虽然被召回了,但ap会下降.

## recall!=1/ap!=1

7_Cheering_Cheering_7_426,这张图片gt=0,所以ap=1

59_peopledrivingcar_peopledrivingcar_59_244,7_Cheering_Cheering_7_426.一起评测,ap!=1

结论:由于标注或者模型训练的问题,导致FP的分数过高,并且存在分数低但为PT的的dets时,此时会影响ap

通过调试可以发现,目标检测评价指标mAP的逻辑是在保证召回的情况下,来提高ap.




