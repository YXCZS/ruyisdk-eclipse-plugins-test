# 针对RuyiSDK Eclipse插件的测试

## 测试说明

以手动测试的方法，测试 [ruyisdk-eclipse-plugin](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/)

## 安装方法

- 见 [ruyisdk-eclipse-plugins/releases](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases)

## 环境配置

+ OS: Ubuntu 25.04 (Plucky Puffin)
+ cpu: 16 核
+ 内存：4G
+ 镜像：https://releases.ubuntu.com/25.04/ubuntu-25.04-desktop-amd64.iso

## 测试结果

共 10 个测试用例，成功 9 个，失败 1 个。
|          测试用例          | 结果  |                                          备注                                          |
| :------------------------: | :----: | :----------------------------------------------------------------------------------------------------------: |
|  虚拟环境构建项目/创建虚拟环境并应用到项目 | 失败  |  创建虚拟环境时选择的路径若不在项目目录下则无法使用                     |
|  虚拟环境构建项目/创建虚拟环境并应用到项目 | 失败  |  创建虚拟环境时profile列表的排序不一致                                  |
