train.py
曲面通过vert和face文件分别存储
代码读取文件后会使用faces_information()计算曲面的更多信息如法向曲率等
把两个曲面的信息上传到surface_distance()函数就可以得到曲面的相似性度量
newmse()也是用于衡量曲面相似性可以加入surface_distance()函数
smoothloss()用于确保位移场的平滑性，loss_Jacobian()用于惩罚反折叠损失

test.py
可以展示离散点云，并且计算mse和ssim以衡量配准效果

3d.py
对点云possion重建
