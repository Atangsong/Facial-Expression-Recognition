
dataset文件夹：数据集（ck+，fer2013，jaffe）

input文件夹：输入数据，用来测试GUI

models文件夹：通过训练集以训练好的模型

output文件夹：GUI输出的结果

src：源码

使用方法：
1.train.py :执行python src/train.py --dataset fer2013 --epochs 300 --batch_size 32 //将在指定的数据集（fer2013或jaffe或ck+）上按照指定的batch_size训练指定的轮次

或

2.直接运行gui.py。
