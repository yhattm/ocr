# install 
## create
* conda create --name paddle_env python=3.8 --channel https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
* conda init zsh
## activate
* conda activate paddle_env 
## install paddlepaddle
* conda install paddlepaddle==2.6.0 --channel https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/Paddle/
## install paddleocr
* sudo apt-get install libgl1-mesa-glx
* pip install "paddleocr>=2.0.1"