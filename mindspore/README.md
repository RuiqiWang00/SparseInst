# Installation  
1.create python 3.8 environment  
> conda create -n sparseinst-ms python=3.8  
  
2.activate the new environment  
> conda activate sparseinst-ms    
  
3.install mindspore   
> pip install https://ms-release.obs.cn-north-4.myhuaweicloud.com/1.8.1/MindSpore/gpu/x86_64/cuda-11.1/mindspore_gpu-1.8.1-cp38-cp38-linux_x86_64.whl --trusted-host ms-release.obs.cn-north-4.myhuaweicloud.com -i https://pypi.tuna.tsinghua.edu.cn/simple 
     
4.install indepencies   
> pip install mindvision pycocotools opencv-python numpy yacs   

# Model
SparseInst_r50_g-iam [百度网盘](https://pan.baidu.com/s/1ZmZ6nqZrwt4ALYP1B2kdCA?pwd=7xsb)

# Demo
> python test.py --config /path/to/your/checkpoint  --image_name /path/to/your/image --visualize  

The result image will be saved in ./image_name/
