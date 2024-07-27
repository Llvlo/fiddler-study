# 一. 第一课

# 初识fiddler，深入理解HTTP协议

- ## 简介

1. 介于B/S架构中间的HTTP代理

2. 浏览器原本就存在一个系统代理，而fiddler就是通过系统代理来操作的

3. 拉下来的包分为请求报文和响应报文

   ![拉下来的包分析](https://github.com/user-attachments/assets/778c4e24-de22-4059-8d9f-66ca6e26fb13)


   + 请求报文

     请求行+请求头+空一行+请求正文

   + 响应报文

     响应行+响应头+空一行+响应体

     #### 如果想把请求信息保存下来为JMeter做性能测试用步骤如下

     **Fiddler**

     1. 右键点击导出

     ![导出1](https://github.com/user-attachments/assets/b88e1e05-feaa-4b21-8c08-06c2b28058af)


     2. 选择cURL脚本

     ![导出2](https://github.com/user-attachments/assets/601f1908-d4a6-4a80-b73b-20f7b00b4650)


     **JMeter**

     3. 在JMeter的工具栏最底下有个导入cURL

     ![导出3](https://github.com/user-attachments/assets/76f9ae07-8e6d-414e-8c21-9ec0388b498d)


     4. 选择文件导入

     ![导出4](https://github.com/user-attachments/assets/442dc209-55f3-4af0-a953-52493da298f0)


     ![导出5](https://github.com/user-attachments/assets/e9fbb49b-4300-4ee1-9506-ecc7db6851fb)


# Fiddler工具详解及应用

## 1. 请求分析

设置**comment**(注释)

设置**文件**导出后可以给**直接打开**.saz文件

![导出可直接执行的saz文件](https://github.com/user-attachments/assets/4f571c39-3a3e-4d40-afad-7ece6638bc04)


**replay**(重放攻击)

* **快捷键**选中后按**R**
* 如果想一次性**重放固定次数**快捷键**shift+R**

**remove**(删除)

* **快捷键**delete
* 只想**保留选中**的请求，全选然后ctrl+左键点击+delete

 

## 2. 请求修改

* **修改**页面上的**图片**
  	![响应修改1](https://github.com/user-attachments/assets/c5b38868-d948-4616-8e8d-5125e73686b1)

* 修改响应体
  ![响应修改](https://github.com/user-attachments/assets/bebe369d-8e52-4ee9-b852-85a8f73f2834)


## 3. 响应修改

## 4. 网络限速

## 5. 断点调式

![断点调式](https://github.com/user-attachments/assets/ab54459b-9308-47b0-9ef4-b26b81b2b262)


## 6. 设计请求

## 7. 自动响应

## 8. mock测试

## 9. 配置



# HTTPS及手机app抓包

## 1. HTTPS抓包

## 2. APP抓包



