- 训练结果  
Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.932  
Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.989  
Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.989  
Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000  
Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000  
Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.932  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.926  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.955  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.955  
Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000  
Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.955  
06/12 10:01:38 - mmengine - INFO - bbox_mAP_copypaste: 0.932 0.989 0.989 -1.000 -1.000 0.932  
06/12 10:01:38 - mmengine - INFO - Epoch(val) [40][56/56]  coco/bbox_mAP: 0.9320  coco/bbox_mAP_50: 0.9890  coco/bbox_mAP_75: 0.9890  coco/bbox_mAP_s: -1.0000  coco/bbox_mAP_m: -1.0000  coco/bbox_mAP_l: 0.9320  data_time: 0.0758  time: 0.1038  
- 测试结果  
Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.934  
Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.992  
Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.992  
Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000  
Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000  
Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.934  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.924  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.953  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.953  
Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000  
Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000  
Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.953  
06/12 10:48:15 - mmengine - INFO - bbox_mAP_copypaste: 0.934 0.992 0.992 -1.000 -1.000 0.934  
06/12 10:48:15 - mmengine - INFO - Epoch(test) [56/56]  coco/bbox_mAP: 0.9340  coco/bbox_mAP_50: 0.9920  coco/bbox_mAP_75: 0.9920  coco/bbox_mAP_s: -1.0000  coco/bbox_mAP_m: -1.0000  coco/bbox_mAP_l: 0.9340  data_time: 4.6002  time: 4.6331
- result下的数据集可视化 
![image](https://github.com/CloudMonica/MMdetection_Tutorials/assets/133513694/6d09f09a-e3a3-4d59-b1ff-10d5c7fccca7)
- 可视化backbone输出3通道   
![image](https://github.com/CloudMonica/MMdetection_Tutorials/assets/133513694/b71b660c-8ab9-4cd8-abbe-253d93995039)
- 可视化neck输出3通道  
![image](https://github.com/CloudMonica/MMdetection_Tutorials/assets/133513694/23f43e47-54cd-4fc3-bace-17c98010ec0b)  
- 查看neck输出最小输出特征值的Grand CAM  
![image](https://github.com/CloudMonica/MMdetection_Tutorials/assets/133513694/f551b550-e321-42f0-bcf8-968d3948ab75)
- 查看 neck 输出的最大输出特征图的 Grad CAM  
![image](https://github.com/CloudMonica/MMdetection_Tutorials/assets/133513694/31d972d1-2221-41e7-b0ee-7c4851731970)
