# awesome-3d-object-detection
list of papers, code, datasets and other resources


## Survey
* A survey of 3D object detection

##LiDAR based
### Region Proposal based methods (two stage)

* PointRCNN [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_PointRCNN_3D_Object_Proposal_Generation_and_Detection_From_Point_Cloud_CVPR_2019_paper.pdf) [[code]](https://github.com/sshaoshuai/PointRCNN)
* Fast Point R-CNN [[paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Fast_Point_R-CNN_ICCV_2019_paper.pdf) [[code]]()
* PV-RCNN [[paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Shi_PV-RCNN_Point-Voxel_Feature_Set_Abstraction_for_3D_Object_Detection_CVPR_2020_paper.pdf) [[code]](https://github.com/sshaoshuai/PointCloudDet3D)
* Deformable PV-RCNN [[paper]](https://arxiv.org/pdf/2008.08766) [[code]](https://github.com/AutoVision-cloud/Deformable-PV-RCNN)



### Single shot methods

* PIXOR [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf) [[code]](https://github.com/mileyan/pseudo-LiDAR_e2e)
* SECOND [[paper]](https://www.mdpi.com/1424-8220/18/10/3337/htm) [[code]](https://github.com/traveller59/second.pytorch)
* PointPillars [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lang_PointPillars_Fast_Encoders_for_Object_Detection_From_Point_Clouds_CVPR_2019_paper.pdf) [[code]](https://github.com/nutonomy/second.pytorch)

## Monocular image based


## RGB-D based


## Sensor Fusion

* 3D-CVF [[paper]](https://arxiv.org/pdf/2004.12636) [[code]]()



## Datasets

- KITTI (CVPR'12) [[paper]](http://www.cvlibs.net/publications/Geiger2012CVPR.pdf) [[project page]](http://www.cvlibs.net/datasets/kitti/eval_3dobject.php)
    - _3D objecct detection_ [[data]](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d) [[results]](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d)
    - _BEV_ [[data]](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=bev) [[results]](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=bev)
- ApolloScape (TPAMI'19) [[paper]](http://ad-apolloscape.bj.bcebos.com/public%2FApolloScape%20Dataset.pdf) [[data]](http://apolloscape.auto/tracking.html#to_data_href) [[results]](http://apolloscape.auto/leader_board.html)
- Argoverse (CVPR'19) [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf) [[data]](https://www.argoverse.org/data.html#download-link) [[project page]](https://www.argoverse.org/index.html)
- A*3D (arXiv'19) [[paper]](https://arxiv.org/pdf/1909.07541) [[data]](https://github.com/I2RDL2/ASTAR-3D#Download) [[project page]](https://github.com/I2RDL2/ASTAR-3D)
- Waymo (arXiv'19) [[paper]](https://arxiv.org/pdf/1912.04838) [[data]](https://waymo.com/open/licensing/) [[project page]](https://waymo.com/open/)
