# YOLOtest
第一步：下载mish_cuda并安装
  git clone https://github.com/JunnYu/mish-cuda
  cd mish-cuda
  python setup.py build install
  
第二步：下载权重，创建相应的文件夹
  (1）从(https://drive.google.com/file/d/1aXZZE999sHMP1gev60XhNChtHPRMH3Fz/view?usp=sharing) 下载yolov4-p5.pt，放在和detect.py相同目录下
  (2)创建inference/images和inference/output。inference/images存放需检测的图片，inference/output存放检测结果
第三步：运行detect.py
  
