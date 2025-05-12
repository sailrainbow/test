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
lite_cog/                			#项目根目录
│
├── deb/                       			#
├── drivers/					#                    
├── nav/
|   ├──build/
|   ├──devel/
|   └──src/
│      ├──fast_gicp
│      ├──hdl_global_localization
│      ├──hdl_localization/
|         ├──apps
|         ├──data
|         ├──docker
|         ├──include
|         ├──launch/
|            ├──hdl_localization.launch
|            └──local_rslidar_imu.launch    	#用于改变地图路径或名称时配置所需地图名称和路径
|         ├──msg
|         ├──rviz
|         ├──scripts
|         ├──src
|         ├──CMakeLists.txt
|         ├──LICENSE
|         ├──nodelet_plugins.xml
|         ├──package.xml
|         └──README.md				#功能包使用说明文档
│      ├──move_base
│      ├──navigation
│      ├──ndt_omp
│      ├──teb_local_planner
│      └──CMakeLists.txt  					#                    
├── others/                    			#
├── pipeline/					#
|   ├──bulid/					#
|   ├──devel/					#
|   └──src/					#
│       ├── pipeline_tracking/			#
|           ├──action				#
|           ├──data				#
|           ├──Readme				#
|           ├──scripts				#
|           ├──tools				#
|               ├──location_record.py		#
|               └──location_record_en.py	#
|           ├──CMakeLists.txt			#
|           └──package.xml			#
|      └── CMakeLists.txt 			#
├── slam/
|   ├──build/
|   ├──devel/
|   └──src/					#建图功能包
|      ├──faster-lio				#构建3D点云地图(.pcd)功能包
|      ├──map-server				#保存栅格地图(.pgm)功能包
|      ├──octomap_mapping			
|      ├──pcd2grid				#将三维点云地图(.pcd)转为栅格地图(.pgm)并发布
|      └──CMakeLists.txt		                   
├── system/					#
|   ├──map/					#
|      ├──lite3.pcd				#
|      ├──lite3.pgm				#
|      └──lite3.yaml				#
|   ├──scripts/					#
|      ├──depth_camera				#
|      ├──lidar/					#
|         ├──start_livox.sh			#
|         └──start_lslidar.sh			#
|      ├──nav/					#
|         └──start_nav.sh			#
|      ├──slam/					#
|         ├──gridmap.sh				#
|         ├──save_map.sh			#
|         └──start_slam.sh			#启动建图程序的脚本
|      ├──transfer/				#
|         └──start_transfer.sh			#
|      └──voa					#
|   ├──all_start.sh				#
|   └──kill_all.sh				#
├── track/                         		#
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
