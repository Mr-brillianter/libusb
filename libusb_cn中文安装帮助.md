# libusb库文件配置/安装（C语言）

## 1.环境

**Windows10**

**X64**

**Visual Studio 2019**

**静态库配置**

## 2.参考网站

 [官网](https://libusb.info/) 

 [GitHub](https://github.com/libusb/libusb) 

 [api](https://libusb.sourceforge.io/api-1.0/libusb_api.html) 

[**静态库配置方法**](https://www.bilibili.com/video/BV1XE411k7PN)

(非本人视频)

## 3.安装

**其实就是简单的静态库配置步骤**

### 1.下载

**下载链接，我下的是[Windows二进制版本](https://github-releases.githubusercontent.com/15120676/d77ef600-4387-11eb-9e85-cecc8155315b?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20210802%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210802T012729Z&X-Amz-Expires=300&X-Amz-Signature=b67ccc83c4b201f036319873370b2bbe5da3f17996048bb22bb950bc22dc21a1&X-Amz-SignedHeaders=host&actor_id=60534303&key_id=0&repo_id=15120676&response-content-disposition=attachment%3B%20filename%3Dlibusb-1.0.24.7z&response-content-type=application%2Foctet-stream)**



### 2.解压



### 3.添加头文件

**解压后，新建空的C 解决方案，命名为libusb，将 libusb-1.0.24\include\libusb-1.0中的libusb.h添加到解决方案头文件**

### 4.添加测试文件

**将libusb-1.0.24\examples\source 中的 listdevs.c 添加到源文件**

### 5.选择X64

![1628246997039](libusb_cn中文安装帮助.assets/1628246997039.png)

### 5.配置属性

之后的步骤和静态库配置方法:https://www.bilibili.com/video/BV1XE411k7PN一样，区别在于需要选择x64平台，而且要在配置属性前选择，不然会配置到x86平台

![1628247284647](libusb_cn中文安装帮助.assets/1628247284647.png)

**右键单击解决方案libusb，弹出选项中选择最后一个“属性”...**

**静态库目录：libusb-1.0.24\VS2019\MS64\static**

**静态库文件：libusb-1.0.lib**

**后略：请查看视频**

### 7.运行



**运行即可**

**运行成功画面：**

![1628247402553](libusb_cn中文安装帮助.assets/1628247402553.png)

author:Github Mr-brillianter
