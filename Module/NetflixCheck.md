## 通过Surge Panel 显示及控制你的Netflix策略组 
脚本经本人测试已经可以正常运行，但仍可能存在bug，使用过程中遇到障碍请联系Telegram：https://t.me/okmytg 

### 原仓库链接：
https://github.com/DivineEngine/Profiles/tree/master/Surge

## 模块说明：
### 新优化版本
- 1:优化版实用至上 大幅提高了使用效率 你可以更快速的控制你的策略组
- 2:首次执行或切换至新的子策略时会花费较长时间 这是在建立索引
- 3:**策略组应当为完全的子策略组嵌套且模式应当为select 你不应放置任何单独节点** 否则将失去效果 你可以隐藏你的子策略组
- 4:你可以调整cron代码以控制节点刷新的频率 但不宜过于频繁
- 5:参数部分与老版本相同
- 你可以配置捷径自动化实现打开Netflix自动检测

#### 配置自动化后可以根据需要减少cron执行频率甚至你可以删除cron脚本
#### NetflixShortcut相对于NetflixChecker仅增加一项通知弹窗，如果你不想看到通知 捷径执行的脚本名称应当为NetflixChecker


### 老版本
 - 1:模块内脚本修改自 @Helge_0x00
 - 2:panel脚本和cron脚本相互依赖，你应当优先执行一次panel脚本，且必须手动运行一次cron脚本以获取节点列表
 - 3:点击panel时切换至下一个可解锁节点
 - 4:panel脚本允许自动更新，自动更新将刷新策略组信息，并可以自动选择更优选项
 - 5: cron脚本用于遍历Netflix策略组，以获取节点列表，你可以通过配置cron表达式以修改执行频率
 - 6:可用的自定义参数：
 - icon1 color1:全解锁时的图标及颜色
 - icon2 color2:仅自制时的图标及颜色
 - icon3 color3:无可用节点的图标及颜色
 - netflixGroup：网飞策略组名称
