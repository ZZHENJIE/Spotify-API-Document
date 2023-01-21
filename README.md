# 简介和安装  

## 简介

### 是调用Spotify官方API获取数据的,[官方文档](https://developer.spotify.com/documentation/web-api/reference/#/)
![](Docs/Image/Spotify_API.png)

## 安装

### 1. 启动项目
```shell
> git clone https://github.com/ZZHENJIE/Spotify-Music-Api.git
> cd Spotify-Music-Api
> npm install Or Yarn
> npm start
```
### 1. 打开[Spotify开发者网页](https://developer.spotify.com/dashboard)并登入  
### 2. 创建APP  
![](Docs/Image/Spotify_Dev1.png)
### 3. 填写APP信息  
![](Docs/Image/Spotify_Dev2.png)
### 4. 查看客户端信息  
![](Docs/Image/Spotify_Dev3.png)
![](Docs/Image/Spotify_Dev4.png)
### 5. 设置项目信息  
   #### 方法一
   > **设置信息示例:** ` /User/Set?id=123456&secret=123456 `

   ![](Docs/Image/Set_User_Data.png)
   #### 方法二
   > **在文件内修改信息示例:**

   ![](Docs/Image/Revise.gif)
### 6. 检测是否设置成功
> **获取示例:** `/User/Get`

![](Docs/Image/Get_User_Data.png)