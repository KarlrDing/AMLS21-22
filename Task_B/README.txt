#This is Task B.
##Data
Dataset contains images and label.csv.
Data_process will generate 2 set of data named: img512.npy / ig224.npy / label.npy.
img is the three set of images and label is the label.

##Models
Models in Task B : RF, SVM, MLP.
Based on GPU and deployed in UCL server: VGG16-scratch, ResNet50-scratch.
Based on GPU/TPU and deployed in Colab: VGG16-Transfer Learning, ResNet50-Transfer Learning, Ablation Learning on VGG-1,Ablation Learning on VGG-2,Ablation Learning on VGG-3,Lightweight CNN.(!!!These files are inside COLAB folder!!!)
###UCL server
1.VPN on.
2.SSH to account.
3.use UCL_GPU.txt to activate enviroment.
###Colab setting
Mount file from google drive. These code will show on the .ipynb.
##checkpoints
callback function for vgg resnet to record the best model and history acc.
##figs
for RF SVM MLP to save boxplot
##logs
save for tensorbloard (also callback)
##weights
final weight for CNN models
##curve
history acc/val_acc/loss/val_loss data and can be used for learning curve