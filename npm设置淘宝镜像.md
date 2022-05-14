# npm使用淘宝镜像

**单次修改：**

```shell
npm install --registry=https://registry.npm.taobao.org
```



**永久使用：**

```shell
npm config set registry https://registry.npm.taobao.org
```



**检测是否成功：**

```shel
npm config get registry
```



**还原**

```shell
npm config set registry https://registry.npmjs.org/
```

