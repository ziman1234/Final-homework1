# Final-homework1
#####运行testRotation.py，会对文件夹中的1.png进行旋转，分别旋转0度，90度，180度和270度，并显示出来。
#####运行trainRotation.py，会自动下载CIFAR10到data文件夹中，并对其进行200个epoch的自监督学习，使用旋转特征rotation的自监督方法。
#####自监督学习的模型权重会保存到model_weights中，accuracy和loss会保存为txt文件，如resNet18_rotation
#####运行trainSupervise.py，会对CIFAR数据集进行200个epoch的有监督学习
#####在进行自监督和有监督学习后，运行answer.py，对自监督和有监督的Resnet18在CIFAR10数据集的表现进行图示。
