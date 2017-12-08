# 基本组成部分
- nginx
- php-fpm
- mysql
- redis

# 项目目录
```
.
├── api							//lumen项目文件夹
├── deploy						//docker各个容器配置参数
├── docker-compose.yml			//docker-compose配置文件
└── README.md
```

# 复制文件,并创建lumen项目
```
$ mkdir lumen-new-app && cd lumen-new-app
$ cp path/to/仓库文件 path/to/lumen-new-app
$ rm api -R
$ composer create-project --prefer-dist laravel/lumen api
```