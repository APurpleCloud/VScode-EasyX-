# VScode-EasyX-

——在VScode上导入C++的第三方函数库EasyX，配置相关的.json文件。

---

### 1.下载对于MinGW的EasyX库

[跳转到下载页面](https://easyx.cn/t/download)

---

### 2.添加库文件和头文件到mingw64文件目录

对已下载的include和lib64/32文件夹自定义重命名

再分别放入mingw64文件表目录的include和lib文件夹

其中include文件夹内为.h头文件，lib文件夹内为.a库文件

文件夹如图所示：

![屏幕截图 2023-11-17 184318](https://github.com/APurpleCloud/VScode-EasyX-/assets/108115022/9f717515-5ea0-4849-93f8-cbcb41bc7bca)

---

### 3.在VScode中创建各项文件

#### 1)launch和tasks文件创建

先创建任意.cpp文件

再点击VScode文本编辑框右上角的小齿轮

如图所示：

![屏幕截图 2023-11-17 185911](https://github.com/APurpleCloud/VScode-EasyX-/assets/108115022/e36ce427-730b-4637-b562-3f54a7b5d8cb)

选择gcc或者g++生成和调试活动文件

会在生成一个vscode文件夹，内部有基本的launch.json和tasks.json配置文件

#### 2)c_cpp_properties文件创建

ctrl+shift+p打开命令面板

输入指令：C_Cpp.ConfigurationEditUI

会跳转到C/C++编辑配置界面

往下滑找到“包含路径”选项

在方框内添加EasyX头文件的文件夹路径

>当然也可以在c_cpp_properties文件的"includePath"项下面添加


如图所示

#### 复制EasyX头文件的文件夹路径

![屏幕截图 2023-11-17 193612](https://github.com/APurpleCloud/VScode-EasyX-/assets/108115022/98d86176-0d8a-4fbe-a44b-2bf7d8a42604)


#### 粘贴至VScode的C/C++编辑配置界面的“包含路径”选项

![屏幕截图 2023-11-17 194049](https://github.com/APurpleCloud/VScode-EasyX-/assets/108115022/79ce0147-e0e7-4145-bf8c-ee5698e9586c)

---


### 4.修改/增加配置文件参数























