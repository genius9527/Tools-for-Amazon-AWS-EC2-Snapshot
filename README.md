# Tools-for-Amazon-AWS-EC2-Snapshot
A tool for creating  Snapshot of EC2 using aws sdk for Javascript

**工具功能**：

1.创建EC2指定卷的快照，并可自定义快照描述

2.前台动态显示快照信息及快照创建进度


**使用方法**：

1.获取你的accessKeyId与secretAccessKey，EC2可用区的名称，填进代码对应位置。

2.在aws EC2 中创建你的卷，将VolumeId填入代码对应位置。

3.运行代码，自定义快照描述，创建快照。

**效果演示**：

初始状态：
![初始状态](https://github.com/genius9527/Tools-for-Amazon-AWS-EC2-Snapshot/blob/master/%E5%88%9D%E5%A7%8B%E7%8A%B6%E6%80%81.png)

前台结果：
![前台结果](https://github.com/genius9527/Tools-for-Amazon-AWS-EC2-Snapshot/blob/master/result1.jpg)

EC2后台结果：
![EC2后台结果](https://github.com/genius9527/Tools-for-Amazon-AWS-EC2-Snapshot/blob/master/result2.jpg)


**Tips**：

1.本工具不可用于商用，仅可用于个人使用，请注意保护自己的账号与密码。

2.动态分配权限的版本尚未开发，待作者有时间会进行版本迭代。
