## 添加容器

!!! Abstract ""

    - 从菜单中选择 **容器**，然后单击 **创建容器**。
    - **根据需要配置容器设置**。    

| Field/Option | Overview |
| --------------------- | --------------------- |
| Name                  | Give the container a descriptive name.|
| Registry              | Select the registry that contains the image that you want to use for your container.|
| Image                 | Enter the name of the image you want to use.|
| Always pull the image | Toggle on to enforce pulling the image from the registry instead of using the locally cached copy (if you have used the image previously). |

## 检查容器

!!! Abstract ""
    点击目标容器名称，有关容器的所有信息都将显示在树视图中。

## 查看容器日志

!!! Abstract ""

    - 支持查看最近一天，最近 4 小时，最近 1 小时，最近 10 分钟的容器日志。
    - **追踪：** 实时刷新容器日志
    - **下载：** 下载容器日志

## 访问容器的控制台

!!! Abstract ""

    - 选择要授予访问权限的命令和用户，然后单击 **连接**。
    - **注意：** 对于 Alpine Linux 容器，选择 /bin/ash 命令。
    - 如果需要定义除提供的命令之外的命令，请将 **自定义** 选项切换为打开。

## 查看容器统计信息

!!! Abstract ""
    支持查看的信息包括：

    - 内存使用率
    - CPU 使用率
    - 磁盘 IO 使用情况
    - 网络使用情况

    ***可以随时更改刷新间隔***。