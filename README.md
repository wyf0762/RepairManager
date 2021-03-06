# RepairManager

[English](https://github.com/wyf0762/RepairManager/blob/master/doc/README_en.md)

一个用于管理机器报修的[MCDReforged](https://github.com/Fallen-Breath/MCDReforged/)插件，需要[PlayerInfoAPI](https://github.com/TISUnion/PlayerInfoAPI)作为前置。

# 安装

1. 将`RepairManager.py`和`PlayerInfoAPI.py`拖入`/plugins`文件夹
2. 使用`!!MCDR reload all`重载MCDR

# 使用

 - `!!repair` 显示报修列表（未修复）
 - `!!repair fixed` 显示报修列表（已修复）
 - `!!repair help` 显示帮助信息
 - `!!repair add <name> <comment> here` 在当前位置添加一个名为name的报修
 - `!!repair add <name> <comment> [<position>]` 在(x,y,z)添加一个报修
    - `<position>`为坐标，格式为`<x> <y> <z> <dim>` ；dim为纬度，0为主世界，-1为地狱，1为末地)
 - `!!repair detail <name>` 显示`<name>`的详细信息
 - `!!repair fix <name>` 标记`<name>`为已修复
 - `!!repair unfix <name>` 标记`<name>`为未修复s
 - `!!repair rename <name> <new_name>` 重命名`<name>`为`<new_name>`
 - `!!repair modify <name> <comment>` 修改`<name>`的注释为`<comment>`

