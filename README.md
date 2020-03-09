# PL_tmp


명령어
CUDA_VISIBLE_DEVICES=0 python detect_test.py --image_folder data/samples/ --weights_path weights/plate.weights --img_size 800 --Detection Darknet --Transformation TPS --FeatureExtraction ResNet --SequenceModeling BiLSTM --Prediction Attn --saved_model OCR/saved_models/TPS-ResNet-BiLSTM-Attn-Seed1111/best_accuracy.pth
