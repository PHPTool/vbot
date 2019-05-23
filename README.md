基于 Hanson/vbot 改版，微信网页登录

使用方式
```
composer require phptool/vbot
```
使用时配置
```php
config['is_multi'] = true, // 启用变动监听
config['session_key']  // 避免 session 重复使用
config['image_path'] = './images/session_port.png' // 二维码输出路径，不填写则是终端输出
```
图片输出到
./images/session_port.png
