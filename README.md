# authcode
适用于微信小程序的authcode对称加密解密方法

## 用法

```
//引入
var authcode = require('./utils/authcode.js');

使用
1. 加密:  authcode.encode('需要加密的数据', '密钥');
2. 解密:  authcode.decode('需要解密的密文', '秘钥');
```
