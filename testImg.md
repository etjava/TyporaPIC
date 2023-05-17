# 测试本地图片上传至github

## 1、下载typora 

```
typora.cn
```

## 2、下载picgo 图床软件

```
https://mirrors.sdu.edu.cn/github-release/Molunerfinn_PicGo
```

![image-20230517180420293](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517180420293.png)

## 3、下载之后以管理员身份执行 （普通权限有时会被防火墙拦截）



## 4、GitHub中创建仓库

```
在github中创建一个存放图片的仓库 
然后需要重新生成一个token
	token生成方式 ： 
	用户头像下拉选择settings -> 右侧菜单栏选择Developer settings -> Peronal access tokens
			-> Tokens(classic) 选择创建token
```

![image-20230517181029884](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517181029884.png)

![image-20230517181114652](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517181114652.png)

## 5、设置Picgo

```
参数解释
设置仓库名: {你自己的用户名}/{仓库名}
设置分支名: main
设定Token: 将复制的token粘贴到这里;
指定存储路径: img/ ; 会自动在你创建的仓库内创建img这个文件夹, 当然也可以不设置, 留空即可;
设定自定义域名: https://cdn.jsdelivr.net/gh/{你的用户名}/{仓库名}
		cdn.jsdelivr.net/gh 是图床使用的代理 可以有效防止访问失败
```

![image-20230517181210402](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517181210402.png)

## 6、设置Typora上传图片

文件 -> 偏好设置

![image-20230517181507981](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517181507981.png)

## 7、测试

![image-20230517175923850](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517175923850.png)

## 8、注意事项

每次使用图片上传功能时 必须保证picgo是开启的 例如

![image-20230517181613793](https://cdn.jsdelivr.net/gh/etjava/TyporaPIC/img/image-20230517181613793.png)
