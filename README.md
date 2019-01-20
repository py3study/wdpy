## 说明
websocket+Django+python+paramiko实现web页面执行命令并实时输出

## 环境依赖

| Project | Status | Description |
|---------|--------|-------------|
| python          | 3.5.4 | 在这个版本以及以上都课可以 |
| django                | 2.1.4 | 大于2.0，小于2.1.5 |
| paramiko                | 2.4.2 | 无 |

## 注意事项

django版本不能是2.1.5，使用websocket，谷歌浏览器会报错

`WebSocket connection to 'ws://127.0.01:8000/echo_once/' failed: Error during WebSocket handshake: Unexpected response code: 400`

## 安装依赖
`pip3 install -r requirements.txt`

或者

`pip3 install paramiko dwebsocket django==2.1.4`

## 运行方式

使用Pycharm直接运行即可

或者使用命令
`python manage.py runserver`


## 效果图

![Image text](https://github.com/py3study/bmt/blob/master/效果图.png)
Copyright (c) 2018-present, xiao You