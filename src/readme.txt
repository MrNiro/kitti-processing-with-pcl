row_data为原始数据
exp_data为实验生成数据

kitti_oxt.py针对时间戳及位移等信息进行处理，得到相应的move_step文件，用于点云数据拼接。

pcl_kitti.cpp为点云数据处理的源码，其中包含所有处理过程所需的函数。
只需要建立好所需的文件夹结构，在主函数中只需要调用data_processing()函数，便可实现所有的功能
在该函数中，可以通过参数选择，确定需要执行的过程，具体在代码注释中可见