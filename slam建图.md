# Demo：（name）

## 前期了解：
* 本次实验需要涉及到哪些文件这些文件的作用是什么？关键参数说明（如果重要），目录结构说明
* example：
* Parameter：
	1. param_1:速度参数
	2. param_2:方向参数
	3. ...
* File：
	1. file_1: 这个文件控制移动（isolation）
		- 关键函数：move(parameter_1,parameter_2,...)
	2. file_2:
		- 
* Directory structure：(标注Demo所需关键文件)
```
Multi_robot/
├── pipline/
|  ├──build/
|  ├──devel/
|  ├──src/					#
│  	├── pipeline_tracking/			#
|           ├──action				#
|           ├──data				#
|           ├──Readme				#
|           ├──scripts/
|		├──__pycache__
|		├──.vscode
|               ├──constants.py
|               ├──dyn_reconfigure.py
|		├──MT.py
|		├──pub_target.py
|               ├──RobotCommander.py
|		├──start_MT.sh			#可以在Rviz中执行多目标跟踪、目标发布等任务
|		├──TA_minmax.py
|               ├──Task.py
|               ├──TaskPoint.py
|               └──TaskTransfer.py		#
|           ├──tools				#
|           ├──CMakeLists.txt			#
|           └──package.xml			#
|   └── CMakeLists.txt 				#
└──.catkin_workspace				#


lite_cog/                			#项目根目录
│
├── deb/                       			#
├── drivers/					#                    
├── nav/					#导航模块
|   ├──build/					#编译生成目录，存放编译中间文件
|   ├──devel/					#开发环境目录，存放编译后的可执行文件
|   └──src/					#导航功能源代码
│      ├──fast_gicp				#基于GICP算法，提供快速的点云配准算法实现，用于高精度地图匹配
│      ├──hdl_global_localization		#全局定位功能包，用于在已知地图中确定初始位置
│      ├──hdl_localization/			#定位功能包
|         ├──apps
|         ├──data
|         ├──docker
|         ├──include
|         ├──launch/				#启动文件目录
|            ├──hdl_localization.launch
|            └──local_rslidar_imu.launch    	#用于改变地图路径或名称时配置所需地图名称和路径
|         ├──msg
|         ├──rviz/				#Rviz配置文件
|            └──hdl_localization.rviz		#定位可视化配置
|         ├──scripts
|         ├──src
|         ├──CMakeLists.txt
|         ├──LICENSE
|         ├──nodelet_plugins.xml
|         ├──package.xml			#ROS功能包描述文件
|         └──README.md				#功能包使用说明
│      ├──move_base				#实现路径规划和导航控制
│      ├──navigation
│      ├──ndt_omp
│      ├──teb_local_planner
│      └──CMakeLists.txt                
├── others/                    			#
├── pipeline/					#
|   ├──bulid/					#编译生成目录
|   ├──devel/					#开发环境目录
|   └──src/					#
│       ├── pipeline_tracking/			#
|           ├──action				#
|           ├──data				#
|           ├──Readme				#
|           ├──scripts
|           ├──tools				#
|               ├──location_record.py		#
|               └──location_record_en.py	#
|           ├──CMakeLists.txt			#
|           └──package.xml			#
|      └── CMakeLists.txt 			#
├── slam/
|   ├──build/					#编译生成目录
|   ├──devel/					#开发环境目录
|   └──src/					#建图功能源代码
|      ├──faster-lio				#构建3D点云地图(.pcd)
|      ├──map_server				#保存和加载栅格地图(.pgm)
|      ├──octomap_mapping			#构建3D占用地图
|      ├──pcd2grid				#将三维点云地图(.pcd)转为栅格地图(.pgm)并发布
|      └──CMakeLists.txt		        #SLAM模块编译配置    
├── system/					#
|   ├──map/					#地图文件存储目录
|      ├──lite3.pcd				#3D点云地图文件
|      ├──lite3.pgm				#2D栅格地图图像文件
|      └──lite3.yaml				#地图配置文件，定义地图原点、分辨率等参数
|   ├──scripts/					#系统脚本目录
|      ├──depth_camera				#深度相机相关脚本
|      ├──lidar/				#激光雷达相关脚本
|         ├──start_livox.sh			#启动Livox系列激光雷达
|         └──start_lslidar.sh			#启动LS系列激光雷达
|      ├──nav/					#导航相关脚本
|         └──start_nav.sh			#启动导航功能
|      ├──slam/					#SLAM相关脚本
|         ├──gridmap.sh				#创建2D栅格地图
|         ├──save_map.sh			#保存地图
|         └──start_slam.sh			#启动建图程序
|      ├──transfer/				#数据传输相关脚本
|         └──start_transfer.sh			#启动数据传输功能
|      └──voa					#语音交互相关脚本
|   ├──all_start.sh				#实现开机自启动
|   └──kill_all.sh				#一键停止所有模块
├── track                         		#
├── transfer                  			#	
└── voa                  			#
```
## 步骤：
* 要求完整包括文字说明，等
* example：
	* 运行此程序要进行
.

			./run.exe

.


## 问题说明 & 解决

* 问题1：（说明简述即可不需要把error全部粘贴）
	* 解决说明：
		* ……
	* 解决步骤：
		1. 进行什么什么
		2. 运行什么什么
		3. 安装什么什么
