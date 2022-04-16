## 通过Surge Panel 显示及控制你的Netflix策略组 
脚本经本人测试已经可以正常运行，但仍可能存在bug，使用过程中遇到障碍请联系Telegram：https://t.me/okmytg 


### 模块说明：
 - 1:模块内脚本修改自 @Helge_0x00
 - 2:panel脚本和cron脚本相互依赖，你应当优先执行一次panel脚本，且必须手动运行一次cron脚本以获取节点列表
 3:点击panel时切换至下一个可解锁节点
 4:panel脚本允许自动更新，自动更新将刷新策略组信息，并可以自动选择更优选项
 5: cron脚本用于遍历Netflix策略组，以获取节点列表，你可以通过配置cron表达式以修改执行频率
 6:可用的自定义参数：
 icon1 color1:全解锁时的图标及颜色
 icon2 color2:仅自制时的图标及颜色
 icon3 color3:无可用节点的图标及颜色
 netflixGroup：网飞策略组名称
