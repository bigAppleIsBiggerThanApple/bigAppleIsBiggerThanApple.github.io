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

**（2）Favorite events**:

There is a heart icon on the right side of each event, users can save their favorite event simply click on that icon. Under this tab, user could check all the events saved before.
[](https://lh3.googleusercontent.com/ijLnP4nzAGpIs6M5NjV1VPhZD0murVUA3GOZpL7UJkb6KC9vCFCQSEMHGM_uNODFpY99cyPA-7c2eLsgo8IayQLqUrBGYsZYpTEHhoHQN7uEQP4WkyppmNlpUTbZLQNElPV7UN3KRO3YEX2GYZ_6uH_Rt7bWds8deXB1hfXT2840tvO1SIdOmYIu_gq_rqE-CRX2juNlZ-BXacguquUd977cx76xccReGPsen7wC18U0qzE6lTGPwlUFz2o7xIKeXclm914CcybGtq9imtBBTqcHZwuhwaTvk-KTcJKBhd0dAv16OT_DI2OhR2VWJ4U-4qKpuRL6oKZwlNnKSB92wnEmUEj7R9PxCmoIHs6UVO1txZRqFfbI7NnN6FvaX6VH0NPm1Sx2slWo4LfrZ8yKKOWnaEqJ-Iz9FbhSXSJ2nO3-V_lno42BOFoHepgaoTpMn_lcEA0jFVQ4CSCfp_XCMDMVWdqHQlu_DuyZKtJ1cytrQlHpma_Y9OPAerLQk2kV9dg5wGqH2QNsDEpbU131WnhCjsnoY-eDpujxEvdDy9I1mWGzyHvvwySGs_qnII2oJaQTMNHucImXZ73DKpvm72gHfqcUodlhsFgmrxya9aauyjnAm5fK_5gfCWkEIEiOGgZZPyjorm7IBWISTi7GvAjB=w1435-h694-no)
		$ tree

- 限制层级

		$ tree -L 2

- 指定当前目录下的某个文件夹

		$ tree Desktop
	
#### 导出文件  
用`> 文件名.格式` 的形式导出

	$ tree -L 1 > tree.md
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTg1MDc2MDgxLC01OTk1Nzg3MDQsLTE5OD
U5MzY2MSwtNDg1NDk2MzFdfQ==
-->