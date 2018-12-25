---
layout:     post
title:      Ticket Web Development
subtitle:   Improved personalized business recommendation based on search history and favorite records
date:       2017-05-07
author:     Xing Wan
header-img: img/post-bg-debug.png
catalog: true
tags:
    - Recommendation
---
# What can this application do? 
**（1）Search near by events**:

When user login, it will send geolocation to our server, convert the geographic location into a key according to the api of our server, then send the data to TicketMaster to get the events and return to user. Below is what events looks like :)
![](https://lh3.googleusercontent.com/LKx_tHZupWoWw3tX0sEYQOsgUX5MJjijuMivfpX2s7xEMrN4NUToA6IlLUlrUKFCST8cH0jygpy6WcKSica_wRWLMVPunD_u097YgZoFWNZ_nVCDDrV3XfDqh-xkpRvAZUsSBQoKIUTGpwbjE_gW9EFSt6397AwQ4iY0c7s1MR3ryU8anXydUo15YYCkJ8417erfo4q9yRHM0EMSxc78cInluPpastZ7c6WVAo8reEYS1nU9y9-mXgd0D4KxNylxoPt7aSd5uUWIGtj8t9kWi18Y_cFLIc9jU27vgMUffkZFntw6MThVFWYC49anGfO2dlffr_TnFstXNjgk1Q6JQoMmPng-9G35OOp_RLcCJO6GPCnilGbEcVfMRoyktC3fhXzfM08kzNxFd_8dJ4oft167TzR7hoqFaeVt3NvZm06e8fSekHDYDB_fbMp3UPLCiOd1NHCKvhsduBWF9oShi0GZDo5r6sbLC4Ne7grRcs3BrJsfvNRooCpgUaXqgIApyittiP8RwF3aYBoTAGztUGjkX4gJsDpjScP0hMAa25G14fKktjPpMVJZVQT4549XRm9JZHAIuPqlEECuLsTUELdswzz3RKmkBjZVc59h90T6xMK1hd7Wv_v93UxfD3Dvg0hPtMrPHItHndPxMCrwuRpB=w1437-h676-no)

**（2）Create video posts**:

Under this tab, you could also simply upload your video posts with a create post button and check all the user post videos around you. What's more, the layout of posts is implemented with react-grid-galary.
	
		$ tree

- 限制层级

		$ tree -L 2

- 指定当前目录下的某个文件夹

		$ tree Desktop
	
#### 导出文件  
用`> 文件名.格式` 的形式导出

	$ tree -L 1 > tree.md
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5ODU5MzY2MSwtNDg1NDk2MzFdfQ==
-->