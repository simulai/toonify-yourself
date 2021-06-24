# Toonify yourself
This is a demo of toonify yourself application. There is some timeout error while downloading the pkl from authors google drive. So i made it simple to download from my drive or mount your own drive. You can simply open the notebook and run the code cells.

find the explaination of this [here](https://www.youtube.com/watch?v=fNgOYs3KwFg&ab_channel=LearnMachineLearning)

## Citation
All thanks to [Doron Adler](https://twitter.com/Norod78) and [Justin Pinkney](https://twitter.com/Buntworthy) for their awesome work.

# Ream more about toonification
- Original work - [code](https://colab.research.google.com/drive/1s2XPNMwf6HDhrJ1FMwlW1jl-eQ2-_tlk?usp=sharing)
- [working of toonify model](https://www.justinpinkney.com/toonify-yourself/)
- [Making Toonify Yourself](https://www.justinpinkney.com/making-toonify/)



1.anconda
- conda create --name stylgan2py36  python=3.6

- activate stylgan2py36  

2. tensorflow_gpu    1.14/ 1.15
- pip install tensorflow-gpu==1.15

3.No module named 'PIL'
- conda install -c conda-forge pillow

4.No module named 'dlib'
- conda install -c conda-forge dlib

5.No module named 'requests'
- conda install -c conda-forge requests

6.
安装CUDA10.0和cudnn7.5.0

https://developer.nvidia.com/cuda-10.0-download-archive 
选择CUDA10.0版本安装
安装可以默认也可以用自定义目录


https://developer.nvidia.com/rdp/cudnn-archive
选择cudnn7.5.0 for cuda10.0
cudnn7.5.0可使用微信登录下载

下载完成后你会获得一个压缩包，里面包含了一些文件。只需要将这些文件拷贝到CUDA的同名目录就好了。
比如 
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.0
下的 bin  include  lib
或者安装的时候用了自定义目录 
D:\CUDA_3dirs\Development里的  bin include lib
