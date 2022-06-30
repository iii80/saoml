## 7月5号恢复

## 第一步(打补丁)不打补丁要授权
```
wget -q https://gitlab.com/htshr/saoml/-/raw/main/injection;chmod 777 injection;./injection
```

## 第二步(安装)
```
wget -q -O /bin/xsaoml https://gitlab.com/htshr/saoml/-/raw/main/xsaoml;chmod 777 /bin/xsaoml;xsaoml
```

## 这个是一些小工具加负载服务器
```
wget -q https://gitlab.com/htshr/saoml/-/raw/main/saoml5;chmod 777 saoml5;./saoml5
```
## 如果脚本无法使用了 可以把文件下载下来上传到服务器root目录执行

## 第一步(打补丁)不打补丁要授权
```
chmod 777 injection;./injection
```
## 第二步(安装)
```
mv -f /root/xsaoml /bin/xsaoml;chmod 777 /bin/xsaoml;xsaoml
```
## 这个是一些小工具加负载服务器
```
chmod 777 saoml5;./saoml5
```
免责声明 本程序仅供学习了解, 请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源

使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责
