# 91160
健康160自动挂号

## 功能

- 自动预约

- 自动挂号

- 自动抢号


## 第三方库

```
pip install -r requirements.txt
```


## 使用

1. 使用pip命令安装所需库

   `pip install -r requirements.txt`

2. 运行main.py

   `python3 main.py`

3. 后台运行
   `nohup python3 main.py >> output.log 2>&1 &`

   `tail -fn 20 output.log`

   `ps -aux | grep main.py`

   `kill id`

## 接入IP池

1. git clone https://github.com/jhao104/proxy_pool.git

2. 开启 redis

3. 配置 proxy_pool setting

4. 设置 enableProxy 为 True

4. 运行

   `python3 proxyPool.py schedule`

   `python3 proxyPool.py server`

## REF

Inspired by [@pengpan](https://github.com/pengpan)