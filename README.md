Prototxt files that define models and solvers.

There are five networks defined here:

ZF_YYY: corresponding the method A in the project paper.

ZF_anchor: anchor.

ZF_multiscale.

ZF_res: residual net.

ZF_combination: Combination of all. Doesn't work very well actaully.

test syntax:
./experiments/scripts/faster_rcnn_test.sh 0 ZF_anchor output/faster_rcnn_end2end/kitti_train/zf_anchor_faster_rcnn_iter_100000.caffemodel 

train syntax:
./experiments/scripts/faster_rcnn_end2end.sh 0 ZF_anchor ZF

Those sh files are slightly changed for more inputs and variables. 


