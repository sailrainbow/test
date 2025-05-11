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
lite_cog/                    
│
├── deb/                       
├── drivers/					#                    
├── nav/    					#                    
├── others/                    			#
├── pipeline/					#
|   ├──bulid					#
|   ├──devel					#
|   └──src					#
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
├── slam/					#                     
├── system/					#
|   ├──map					#
|      ├──lite3.pcd				#
|      ├──lite3.pgm				#
|      └──lite3.yaml				#
|   ├──scripts					#
|      ├──depth_camera				#
|      ├──lidar					#
|         ├──start_livox.sh			#
|         └──start_lslidar.sh			#
|      ├──nav					#
|         └──start_nav.sh			#
|      ├──slam					#
|         ├──gridmap.sh				#
|         ├──save_map.sh			#
|         └──start_slam.sh			#
|      ├──transfer				#
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
