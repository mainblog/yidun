python主要模块 requests  execjs  loguru <br>
缺少什么安装什么就行了
运行效果：
![image](https://github.com/wuyuan456789/yidun/assets/166347308/3c60dce0-ca0f-4e59-8efb-f45a76bf5b6e)

可能错误：
execjs执行js报错;UnicodeEncodeError: ‘gbk‘
异常 UnicodeEncodeError: ‘gbk’ codec can’t encode character ‘\ufffd’ in position 160: illegal multibyte sequence
![image](https://github.com/wuyuan456789/yidun/assets/166347308/8b446b99-6a3c-4d50-bd9a-89aadbf2c41b)
方法一：修改subprocess.py文件的 encoding=None
![image](https://github.com/wuyuan456789/yidun/assets/166347308/9af3f163-3df3-4f64-80bf-f27a591ec82f)
