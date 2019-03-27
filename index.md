# 网军开发文档

>网军项目 OC 为主要语言

## 需求

1. 手机和设备好UUID绑定，同一台设备和同一个UUID只能绑定一个账号
2. APP 启动的时候检[Auth](#Auth)测账号是否与该设备绑定
3. 未绑定进入注册页面[QBWKAuthViewController](#QBWKAuthViewController)
4. 已经注册账号进入登录页面[login][#login]使用faceID 或者touchID进入系统


**文档目录**

- [Classes](#Classes)
 -  [AppDelegate](#AppDelegate)
 -  [Main](#Main)
 -  [Task(任务)](#Task)
 		-  [TaskReport(报表)](#TaskReport(报表))
 		-  [TaskReport](#TaskReport)
 		-  [ViewModel](#ViewModel)
 		-  [Model](#Model)
 		-  [View](#view)
 			-  [TaskGroupView](#TaskGroupView)
 			-  [TaskAssign](#TaskAssign)
 			-  [TaskView](#TaskAssign)
 			-  [AssignedTaskView](#TaskAssign)
 			-  TaskGroupDetailTableViewController.h
 			-  TaskGroupDetailTableViewController.m
 			-  TaskGroupDetai.storyboard(任务详情)
 		-	TaskAssing.storyboard
 		-  TaskAssignTableViewController.h
 		-  TaskAssignTableViewController.m
 		-  TasklistCell.h
 		-  TaskListCell.m
 		-  TaskList.storyboard
 -  [Authlogin](#Authlogin)
 -  [Other](#Other)
	 -  [审核部分#添加用于审核的**设置**和**个人中心**](#审核部分)
	 -  ShareSDK
	 -  ZFChart
	 -  DAcircularProgress
	 -  Tool
	 -  ZLPhoto


Classes
===

AppleDelegate
===

Main
===

Task
===

View
===
主页面下的视图,有任务的详细信息包括,查看和转发详细信息[TaskDeatilTableViewController](#TaskDeatilTableViewController.m),下方有各个部门的详细信息
		-  TaskGroupDetailTableViewController.h
 			-  TaskGroupDetailTableViewController.m
 			-  TaskGroupDetai.storyboard(任务详情)
 	

## TaskReport(报表)
===

- TaskReport.h

	选择人员上传所需要的模型
	
```
```

- TaskReport.h
- AllSelectBtn.h
	

