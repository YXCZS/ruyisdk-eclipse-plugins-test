# 针对RuyiSDK Eclipse插件的测试

测试版本为 [v0.1.1](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases/tag/v0.1.1)

## 测试说明

以手动测试的方法，测试 [ruyisdk-eclipse-plugin](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/)

## 安装方法

- 见 [ruyisdk-eclipse-plugins/releases](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases)

## 环境配置

+ OS: Ubuntu 25.04 (Plucky Puffin)
+ CPU: 16 核 x86-64
+ 内存：4G
+ 镜像：https://releases.ubuntu.com/25.04/ubuntu-25.04-desktop-amd64.iso

## 测试结果

共 11 个测试用例，成功 8 个，失败 3 个。
|          测试用例          | 结果  |                                          备注                                          |
| :------------------------: | :----: | :----------------------------------------------------------------------------------------------------------: |
|  虚拟环境构建项目/创建虚拟环境并应用到项目 | 失败  |  创建虚拟环境时选择的路径若不在项目目录下则无法使用                     |
|  虚拟环境构建项目/创建虚拟环境并应用到项目 | 失败  |  创建虚拟环境时profile列表的排序不一致                                  |
| 包管理器/安装包 | 失败 | 选择开发板的界面没有排序文本 |
| 包管理器/安装包 | 失败 | 包在下载完成前还是可以点击继续 |
| RuyiSDK管理/自动检测与安装ruyi | 失败 | 在成功完成之前下一步按钮还是可以被点击 |
