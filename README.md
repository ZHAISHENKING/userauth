# userauth
用户登录token生成

目录文件

<img src="http://qiniu.s001.xin/user/userauth.png">

### 如何运行？

1. git clone 地址

2. 修改settings.py 数据库配置，自己建一个shop数据库

3. ```bash
   # 安装依赖环境
   pip install -Ur requeirements.txt
   ```

4. ```bash
   # 迁移数据库
   python manage.py makemigrations
   python manage.py migrate
   # 注册超管
   python manage.py createsuperuser
   ```

5. 测试

<img src="http://qiniu.s001.xin/user/postman.png">

看到最终返回的token并且密码是加密存储的