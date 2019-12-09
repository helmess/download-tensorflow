# download-tensorflow
step1:
build your tensorflow enviroment,at first ,open anaconda prompt
key as fllows:
conda create --name tensorflow python=3.5

step2:
activate tensorflow and then install tenosorflow by configure condrc,path of the file is /usr/usr_name
attention:replace https with http.
/*******************************************/
channels:

  - http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
  - http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
show_channel_urls: true
ssl_verify: true
/*******************************************/
step3:
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple/https://mirrors.tuna.tsinghua.edu.cn/tensorflow/windows/cpu/tensorflow-1.1.0-cp35-cp35m-win_amd64.whl

