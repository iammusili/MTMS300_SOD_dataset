# MTMS300_SOD_dataset
a Multiple-Targets-Multiple-Scales benchmark dataset for salient object detection
《MTMS300: 面向显著物体检测的多目标多尺度基准数据集》一文对应的公开内容：
（1）MTMS300数据集：
	共包含600幅图像，其中300幅为彩色可见光图像，300幅为像素级标注图，可见光图像与标注图一一对应。
（2）DSC：
	共包含638幅图像，其中319幅为彩色可见光图像，319幅为像素级标注图，可见光图像与标注图一一对应。
（3）模型评估代码：
	读取显著图和相应的标注图，计算显著图对应的AUC值、F值等指标得分。

补充说明（2021年2月17日）：
MTMS300数据集中图像主要来源为：新浪军事、中国军事图片中心和铁血论坛。
在本论文发表前，我们分别与新浪军事、中国军事图片中心、铁血论坛进行了联系，并就版权问题进行了沟通。
三家单位的答复均为：对于非商业用途，无须授权；注明出处，保留水印。
对于本文研究的显著物体检测任务来说，如果图像中带有水印，将干扰算法性能。
因此，在制作数据集的过程中，我们人为地去掉了原图的水印，最终发布的数据集没有水印。
所有带水印的原图，我们均妥善保存了下来。如果有版权问题，请与我们联系。
邮箱：iammusili@qq.com

补充说明（2021年2月23日）：
在之前的研究中，我们提出了一种结合布尔图和灰度稀缺性的显著性检测算法（已发表在《中国图象图形学报》2020年第二期）。
代码开源，欢迎测试和对比~
https://github.com/iammusili/BMGR_SOD_code

补充说明（2022年4月24日）：
引用格式：李楚为,张志龙,李树新. 2022. MTMS300:面向显著物体检测的多目标多尺度基准数据集. 中国图象图形学报,27(04) :1039-1055[DOI:10. 11834 / jig. 200612]

