训练：
 python train.py --weights yolov7x_training.pt --cfg cfg/training/yolov7x_custom.yaml --data data/custom.yaml --device 0 --batch-size 64 --epoch 10
 
测试：
 python detect.py --weights runs/train/exp/weights/best.pt --source inference/raccoon_images
