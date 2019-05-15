# 关于代码怎么运行的说明：

注:tensorflow 我用的是1.1
(1)你会看到两个文件：main_resnet.py, resnet.py
(2)打开main_resnet.py, 定义好你的：batch_size，nb_classes，nb_epoch
(3)Training with Scratch, 就是没有加载Pretrain model 的，注释掉374行，选择375行
(4) Training with Pretrained model, 注释掉375行，选择374行
(5)然后在378行load model.

pretraining model with 50 layers for imagenet 地址 :
WEIGHTS_PATH = 'https://github.com/fchollet/deep-learning-models/releases/download/v0.2/resnet50_weights_tf_dim_ordering_tf_kernels.h5'

更多精彩内容请关注：
本人公众号：follow_bobo
知乎：蒋竺波
知乎专栏：卷积神经网络（CNN）入门讲解
