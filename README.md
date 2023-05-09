# Honkai：Star Rail
# 崩坏：星穹铁道自动锄大地脚本
<img alt="LOGO" src="./temp/love!.png" width="768" height="1152" />


*****该脚本仍然处于测试阶段，可能会出现奇奇怪怪的BUG*****

***寻路撞墙？走的路径不对？嫌弃路线太慢？ 现在beta-2.7新增加地图录制功能，你现在可以使用tool目录下的record_v7.2.py自行录制地图路径，包你走到满意 XD***

找到BUG了？，代码问题想吐槽？欢迎加入 技术 & 吹水群：[星穹◇Time(QQ 群)](https://qm.qq.com/cgi-bin/qm/qr?k=xdCO46fHlVcY7D2L7elXzqcxL3nyTGnW&jump_from=webapi&authKey=uWZooQ2szv+nG/re7luCKn8LW1KibSb0vvi0FycA45Mglm5AGM1GP2iJ+SiWmDwg)<br>

~~该脚本当前版本仅支持 缩放150%，屏幕分辨率2560x1440，现在在大改动中，尽快解决屏幕旋转适配问题~~

****使用说明****

**1：脚本只支持PC端，如果你的电脑分辨率为2560\*1440，请将游戏分辨率请调为1920\*1080 （窗口化） ；如果你的电脑分辨率为1920\*1080，请将游戏分辨率调为1920\*1080（全屏幕）**

**2：脚本运行时请勿移动鼠标和键盘，避免寻路点位出现偏离** 

**3：强烈推荐使用远程角色开怪**

**4：战斗为游戏自带的自动战斗，确保你的队伍有足够实力平推小怪** 
(如启用了沿用自动战斗设定，请把config.json里的 "auto_battle_persistence" 改成 1) 

**5：如果脚本无反应，请使用管理员权限运行**

**6：脚本录制说明：wasd移动，x是进战斗，鼠标左键是打障碍物等，不要用鼠标移动视角，用方向键左右来移动视角（脚本运行后方向键左右会映射成鼠标），F9停止录制并保存**

**7：脚本录制完成后将会生成output.json文件，请把他重命名替换成你要更改的地图json即可使用** （原地图json将执行的路线将会在5月8日详细更新介绍）
 
 
 ## 注意
 
 1：识图继续屏幕截图为截取电脑屏幕全部画面，（句柄我不会emmmmm...），所以可能识图有可能出现一点点差错。。。
 
 2：该脚本暂时只支持**空间站【黑塔】**以及**雅利洛部分地图**，后续会更新（只要我不卡关）
 
 3：代码是屎山，后续会优化，暂时是这个框架了
 
 ****如果喜欢，点个星星~****

## 运行前须知

1. 确保你安装python（推荐3.9+）
2. 安装依赖：`pip install -r requirements.txt`

## 更新日志 (beta-2.7)

**1：增加了脚本录制功能，现在用户可以自行录制地图json感谢**[@AlisaCat](https://github.com/AlisaCat-S)<br>

2：模拟宇宙正在开发

3:后续将会新增找宝箱、锄大地顺带捡垃圾等功能

4：更新了新的地图json，解决的大部分撞墙问题

## 贡献者

感谢以下贡献者对本项目做出的贡献

<a href="https://github.com/Starry-Wind/Honkai-Star-Rail/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Starry-Wind/Honkai-Star-Rail" />

</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Starry-Wind/Honkai-Star-Rail&type=Date)](https://star-history.com/#Starry-Wind/Honkai-Star-Rail&Date)
