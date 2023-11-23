# sim_arm_location_msg

# 概述

该功能包定义了仿真机械臂拾取物体demo中的服务

# 服务说明

| 类型                                    | 说明                             |请求                 |回复               |
| -------------------------------------------| -------------------------------- |---------------------|------------------|
| sim_arm_location_msg::srv::ChooseCube      | 用于用户选择想要拾取的方块号码      |uint16 num           |bool success      |
| sim_arm_location_msg::srv::TargetLocation  | 目标的三维坐标                     |float32 x, float32 y, float32 z |bool success      |