# [ds-apisix] 
基于APISIX3.x版本，支持GM国产密码算法(Sm2、Hmac-Sm3、Sm4)实现

## 特点

1. 完全兼容APISIX原生插件，只是增加自定义插件
2. 支持国密算法，适应当前国内软件对国密算法的要求.(当前github能找到的加解密算法基本上只有国际密码算法，比如sha、rsa、md5等）
3. 支持openssl3.x，（apisix3.8版本升级openresty后，内置openssl版本由1.1.x升级到了3.x）

## 其他

承接自定义插件开发，有意者私信
