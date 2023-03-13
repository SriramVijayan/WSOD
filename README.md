# WSOD
Working on algorithms for Weakly Supervised Object Detection

# coco_data_prep.ipynb
1) Prepare the training data and train the model with only image level labels. Training and validation split is using COCO train2017 dataset (~70% train, ~30% val).
2) Evaluate classification accuracy of trained model on COCO val2017 dataset

# eval_performance.ipynb
Evaluate object localization performance on val2017 dataset using the following algorithms:
1) Grad-CAM
2) Grad-CAM++
3) A gradient clustering technique using Grad-CAM++ to cluster feature maps and produce several heatmaps and combine them
4) Binary clustering technique based on Grad-CAM to aggregate feature maps to produce final heatmap
5) Binary clustering technique based on Grad-CAM++ to aggregate feature maps to produce final heatmap
