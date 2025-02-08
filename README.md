# [ds-apisix] 
基于APISIX3.x版本，支持GM国产密码算法(Sm2、Hmac-Sm3、Sm4)实现

## 背景

1.开源版本的APISIX不支持国密算法实现，现在能找到的基本上都是国际密码算法
2.网关的应用场景对密码算法的需求更迫切
2.国内软件行业绕不开国密算法的使用，需要在网关层提供解决方案
3.虽然可以通过插件机制使用其他语言实现，但是性能方面可能受影响

## 特点

1. 完全兼容APISIX原生插件，只是增加自定义插件
2. 支持国密算法，适应当前国内软件对国密算法的要求.(当前github能找到的加解密算法基本上只有国际密码算法，比如sha、rsa、md5等）
3. 支持openssl3.x，（apisix3.8版本升级openresty后，内置openssl版本由1.1.x升级到了3.x）

## 其他

承接自定义插件开发，有意者私信
