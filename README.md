### rsa加密
小程序rsa加密方法，支持文本超长加密

### 使用示例
```js
  let PubKey="xxxxxxxxx";
  let EncInfo="xxxxxxxxxxxxxxxxxx"
  let encrypt = new JSEncrypt();
  encrypt.setPublicKey(PubKey);
  let encData = encrypt.encryptLong(EncInfo);
```
