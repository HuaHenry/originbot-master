# 基于OriginBot智能机器人修改的yolov5s避障


## 项目链接

### 项目主站

[https://www.originbot.org/](https://www.originbot.org/)

### 源码仓库

| 代码仓库                                                         | 说明                        |
| ------------------------------------------------------------ | --------------------------- |
[originbot ](https://gitee.com/guyuehome/originbot) | originbot机器人端功能包仓库 |
[originbot_desktop](https://gitee.com/guyuehome/originbot_desktop) | originbot电脑端功能包仓库   |
[originbot_controller](https://gitee.com/guyuehome/originbot_controller) | originbot控制器源码仓库     |

### 论坛交流

[https://guyuehome.com/Bubble/circleDetail/id/95](https://guyuehome.com/Bubble/circleDetail/id/95)


## 软件架构

- originbot_base：机器人底盘驱动
- originbot_driver：机器人设备驱动
    - serial_ros2：串口驱动包
    - ydlidar_ros2_driver：雷达驱动包
    - qpOASES： qpoASES解算包
- originbot_msgs： OriginBot自定义通信接口
- originbot_bringup：机器人启动相关的脚本和文件
- originbot_demo：机器人基础功能的编程示例
- originbot_linefollower：机器人视觉巡线功能包
- originbot_navigation：机器人建图与导航相关的脚本和配置文件
- originbot_deeplearning：机器人深度学习功能
    - body_tracking：机器人人体跟随功能包
    - gesture_control：机器人手势控制功能包
    - line_follower_perception：机器人AI视觉巡线功能包
    - parking_search：机器人车位寻找功能包
    - play_football：机器人踢足球功能包
- originbot_example： 机器人常见应用功能
    - originbot_autonomous：机器人轨迹跟踪
    - originbot_qr_code： 机器人二维码识别
    - originbot_teleop： 机器人按键控制
    - originbot_vlpr： 机器人车牌识别
    - send_goal： 机器人定点导航
    - take_pictures_node： 机器人图像获取
