## capstone: dogs vs.cats 

代码分为三部分：

pre_process是简单的可视化预处理；

transfer_learning_single_model是第二部分，单模型利用预训练好特征向量迁移学习；

transfer_learning_finetune_InceResNV2_and_merge是第三部分，finetune inception_resnet_v2、融合以及可视化部分。


运行使用软件：

python3.6\cuda9.0(cudnn7.1.2)


运行依赖库：

numpy1.14.2\pandas0.22.0\Keras2.1.5\tensorflow-gpu1.6.0\scikit-learn0.19.1\Pillow5.0.0\opencv-python3.4.0.12\matplotlib2.2.0\seaborn0.8.1\h5py2.7.1\tqdm1.19.9



