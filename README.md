# Programming-In-C

## 1. 登录github账户，搜索`TuringDataScience/Programming-In-C`项目
![image](https://user-images.githubusercontent.com/97928376/201569142-720ca702-0151-459a-9a7c-0731d5553091.png)
## 2. fork项目
搜索到项目之后，点击进入项目，在项目的右上角点击`fork`，将项目复制到自己的github仓库
![image](https://user-images.githubusercontent.com/97928376/201569400-0bcb5ae7-b05b-4c6a-9fb3-d18d28e5b6f7.png)
![image](https://user-images.githubusercontent.com/97928376/201569548-671376b3-4fc4-4077-8635-2dee861b4a13.png)
![image](https://user-images.githubusercontent.com/97928376/201569719-bfeb56da-df4d-406d-82b0-2fcd5ea723c4.png)
## 3. 在fork的仓库中添加自己的作业编码
在本机中使用git克隆自己的github中复制的仓库到本地，在本地工作目录中根据作业清单完成编码，将编码提交本地仓库，然后推送到自己的github仓库
```
 1. 在自己的电脑上搜索安装git，自行百度搜索，然后使用默认选项安装
 2. 在电脑中找到空闲的地方，点击鼠标右键，找到git bash here(安装成功就会创建)
 3. 打开之后进行简要配置
    git config --global user.name 用户名(自行设定)
    git config --global user.name 邮箱
 4. 在自己的github中找到fork的仓库，点击进入，然后再页面中找到`code`,里面包含3种协议，选择https并复制路径   
 5. 克隆github中的仓库,网速原因，可能超时，可多次尝试，仓库克隆只需要第一次使用时下载即可
   git clone xxxxx.git(复制的仓库路径)
 6. 克隆成功后在本地就会存在Programming-In-C的文件夹，然后将自己的代码程序放到指定的目录中
 7. 添加并提交本地仓库(此处注意查看当前git bash所在目录，如果不在Programming-In-C的目录中，可以使用cd命令切换进去，确保在当前位置行能看到(main))
    git add 存放代码的目录
    git commit -m '更新内容简要说明'
  8. 提交自己的github仓库
    git push origin main
    
  ------------------------------------------
  以后每天提交
  1. 在自己的github的Programming-In-C仓库中找到sync进行仓库同步
  2. 在自己电脑的Programming-In-C目录中打开git bash here
  3. 更新仓库到本地
     git pull origin main
  4. 添加代码并提交
    git add 存放代码的目录
    git commit -m '更新内容简要说明'
  5. 提交自己的github仓库
    git push origin main   
  
```
## 4. 提交pr请求合并
将自己github仓库中的内容创建pull request到TuringDataScience/Programming-In-C请求合并。
![image](https://user-images.githubusercontent.com/97928376/201569911-6435461d-b51e-4dc0-992c-d9057be99383.png)
![image](https://user-images.githubusercontent.com/97928376/201570081-662582b0-d280-45b8-94c6-aa49bf391d29.png)
![image](https://user-images.githubusercontent.com/97928376/201570177-68b6a6dd-e33c-48e2-8c7f-c17d31134ba3.png)
