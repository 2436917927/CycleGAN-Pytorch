
## 训练步骤
1. 训练前将期望转换的图片文件放在datasets文件夹下，一共两类，训练目的是让A类与B类互相转换。
2. 运行根目录下面的txt_annotation.py，生成train_lines.txt，保证train_lines.txt内部是有文件路径内容的。  
3. 运行train.py文件进行训练，训练过程中生成的图片可查看results/train_out文件夹下的图片。  
