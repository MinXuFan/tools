# ocr

[飞桨](https://www.paddlepaddle.org.cn/documentation/docs/zh/install/docker/macos-docker.html)
[仓库](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.6/doc/doc_en/quickstart_en.md)
```
docker pull paddlepaddle/paddle:2.3.2-jupyter
docker run -itd -p 80:80  --env USER_PASSWD="Test1024" -v $PWD:/home/paddle registry.baidubce.com/paddlepaddle/paddle:2.3.2-jupyter
python3 -m pip install paddlepaddle -i https://mirror.baidu.com/pypi/simple 
pip install "paddleocr>=2.0.1" 
pip install opencv-python-headless
```
