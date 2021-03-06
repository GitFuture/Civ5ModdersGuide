文明 5 mod 制作教程 - 索引
==============
by Derek "Kael" Paxton version 1.00

## 目录

-----------------
* [核心概念](./civ5_Modders_Guide_part1.md)
    - 模组开发是什么？
    - 文明 5 有哪些改动？
    - 模块设计
    - XML
        * 模式
        * 理解相关性
        * XML 文件结构
    - SQL
        * 查看数据库
        * SQL 用例
    - Lua
        * XML 和 LUA 的关系
        * 参考
        * 脚本事件
* [制作模组](./civ5_Modders_Guide_part2.md)
    - ModBuddy
        * 制作模组
        * 组织项目
        * 模组属性
        * 创建对象
        * 更新对象
        * 删除对象
        * 如何添加文本
        * 修改文本
        * 如何添加文明
        * 如何添加图标
        * 如何添加首领
        * 如何添加特性
        * 如何添加单位
        * 如何改变艺术家的定义
        * 如何添加建筑
        * 如何修改建筑
        * 如何移除资源
        * 如何用 Lua 禁用单位图标
        * 如何用 InGameUIAddin 制作模块化的 UI 变化
        * 如何用 Lua 添加一个新镜头
    - WorldBuilder
        * 保存文明 5 的地图
        * 向模组中添加地图
    - 发布模组
        * 兼容性
    - 排除故障
        * Database.log
        * Lua.log
* [设计之理](./civ5_Modders_Guide_part3.md)
    - 做出你想玩的游戏
    - 避免设计缺陷
        * 多的危险
        * 特色的危险
        * 模式的危险
        * 复杂性的危险
    - 制作模组的过程
        * 书写设计文档
        * 经济性 = 缺乏资源时的选择
        * 困惑时，请相信 Firaxis
        * 制定优先级，学会拒绝
        * 组件队伍
        * 何时发布

---------------

> 注：
> * Firaxis 是一家美国游戏开发公司，由 Sid Meier 创立。 -- 来自 Wikipedia
> * 《文明 5》是由Firaxis Games负责开发，由2K Games出品的一款策略游戏。  -- 百度百科
> * 由于该文档篇幅较长，翻译时，将其分为 1 个索引和 7 个部分。
> * 另外，该教程已经有点过时了（在《文明 5》的 BNW 版本中，按照该教程中的一些步骤制作的模组无法正常运行，将会在每一部分的结尾做出说明，因此运行自制的模组前请确保看完了相应部分的内容）。
> * 本文的翻译已经在《文明》[论坛中](https://forums.civfanatics.com/categories/civilization-v.385/)联系过 Kael 本人，得到了 Kael 的[肯定和支持](https://github.com/GitFuture/MyTranslation/tree/master/translated/civ5_imgs/civ5moddersguide_authorized.png)。
> * 感谢“塞爱维&天邈”汉化团队做的汉化包，在翻译本教程中的一些专有名词时，参考了他们的汉化内容。

-------------

[pdfurl]:http://kael.civfanatics.net/files/ModdersGuide.pdf