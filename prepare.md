* https://github.com/hoya012/deep_learning_object_detection
* https://github.com/hoya012/deep_learning_object_detection

# 目录

* detection 问题定义
* 数据集
  * PASCAL VOC Object Detection Challenge
  * ILSVRC Object Detection Challenge
  * MS COCO Object Detection Challenge
  * Open Images Object Detection Challenge
  * DOTA
  * Objects365
* 评价指标
  * Average Precision
  * Mean Average Precision
  * AP Across Scales
  * Average Recall
  * AR Across Scales
* 算法模型
	* R-CNN
	* Fast R-CNN
	* Faster R-CNN
	* Mask R-CNN
	* Cascade R-CNN
	* YOLO
	* YOLO v2
	* YOLO v3
	* SSD
	* ...





RPN生成更多的RoI能得到更高的mAP ？

如何训练的，正负样本如何选取？分stage训练还是end to end

Fast(er) R-CNN的速度

每篇论文的时间、会议、作者





$ Precision = \frac{TP}{TP + FP} = \frac{TP}{all \ detections}$

$Recall = \frac{TP}{TP+FN} = \frac{TP}{all \  groundtruth}$

