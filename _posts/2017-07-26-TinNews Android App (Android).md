---
layout:     post
title:      TinNews Android App
subtitle:   Designed the Instagram Flavor News app based on **MVP** architectural pattern
date:       2017-08-26
author:     Xing Wan
header-img: img/post-bg-hacker.jpg
catalog: true
tags:
    - Android
---

# Schematic diagram for this app:
From the 
 ![](https://lh3.googleusercontent.com/2HyD7DfLyQwR_v3SWy1n-jarb-dc0RwNmpQReCESp49aXQK-ohkEFMJBc_72GrH_nbQAP7v6Zbxr4xjtFcAbyajUMzCv8kjS81GU-m-GqFAMveQZfwVgGUWqP-egTuVIiwtG3G5EUfpkr-aMTA-DcqQAwc1Y_NKgHIwA92OBQDaHJ5kFjtMWRwUgVVHIq8BhxTFjCOzjEuwlA5LmmLvsOc45ZHZWy3EaFbvJ9Ol6vnLgZRpo_znaZfKOi_sYVhhvToQlM3ly_IJpPkDQkcNQMw5alSIF3RsnqPfhqk_UVMBj3zlDxdUYcyT38ekaOiITJWtILoqZzwB9X51wDbrg30LhMlptEDBCzTwPt4Ydux9UIVKdXKhhEtWQ063koP_mwjVry1feLlKn0EqJxX6YJkM-baDeXDFk78Wdhtz_NQTEjn3aBDHCSbIe52PzFIsZxnVT2PVfDwbzJb81qwEeQOA_-SLAvuqRDZBDGSphsam8DThtWc8VtE9FJBY1zujL3j7ZkXur_OC0hpuSjcr42nTFjtsKlUTk-fKkuMTyDocOgSjVGxZrip5XfHotfqe1xyUe4eX3ylJh3oxEIsfEudWpMdlZIX5C0Z7z3q6HXElK1QBNKGm6HEmDOS9G3eeN7eIo8FpOXRExNtRZ3p1iQsMk=w639-h513-no)
# What can this application do? 
**（1）Present news**:

The news data of this project is taken from newsapi.org, and then every time 10 news will be rendered to user. And the user can like or dislike any news on the homepage, and the liked news will be stored in the save tab.
![](https://lh3.googleusercontent.com/F2vUzjeDiOCFTacIyZ0oqyri9UfEeisiW583PKAZkgwEcrn5Lb869JtpIXnqzulhiH1_D_H5A1KapAteRcFUUjxexKJVTbQ6HZTgvjGts-HIrhvlhYr7VP6u1F-jaEBLISwTKKeJzc0ueGJ_XdY64eA84hAUEfE_hPVKkAw-LGMUMEJtglCsYWe6vApl3wVGHL8i6Niql61cZTYiKJ02XaV78oaAnQJyQQyvVBTy6ZaQnNvSJL4tKuZd5MpxHEsznFjsxMUFRjvY-Jm2UEtTPlpWWckJivjJP4mzvxMQsBAxrBduYHji_6BwygYIAJc0pD5R0ub0zxiI8CCbUcY2SyHXL0zmDh6dG3CVLQxD_t8icAaW4izZw3QlCaN88ZhwLAFBKZ8Py1q-RrnCpDFJ2sWBfbCKZIc8-WKDgAdkZH7hKbt_H9rKsmbcuuGBwV5C1f4Au6idFfUsCKgdSTz6nAuR-Fzzpi47mt7aIt_5JKHGh3y4H2d9Zc-lu-snlE2oSRKnUP-dKYkiX6UyxjeMyzvBBQkdOzMIWF79xBK2_yNCDvg1clf42rjaQb-mi5poX3Okk1c_pBlHcPxRHBJTeZFNu6SkVmMyaxFW-i5YWOzliWcIcIcY4yIIWH8nXEycIVtRluMDnMjrbWa_MgqXogyl=w273-h451-no)


**（2）View saved news**:

Under this tab, users could check the news they liked and  click it to view the news details.
![](https://lh3.googleusercontent.com/mrZCdTy6PyOzJxJeKSTgbqk_4NAaAF2QAcMsYMzGBToRZvGLv2G9QZfnbsPE0IQQyDqJcA6-K4bQPYscVC9QVDoBHf0UK6FzNBimKMHWu_qk4hT0kLYd0S1GZkB-pRAx4HOWrLx-cxEPYjXzOAdNz_XXd-6QFQBo91IdvYQ3r93IqvN6IRCaP2CA680cVbUpnZ7_i7lVVip63vBGZyTXtPFfM_1PQNu3AtKMk1sfwDSLWkhx2dd6hKa7Vn5LU18E1P6wDun2VeNNRL3_zMg7ewzMqVHxNnRLXdgOMGoCDRA0dzlah2EFH59wVrRTHZISAdnabNXqCpmCw6MYEUS_LGzAKId1DTF3LitVSFtexK5LIxIXoPfjkOEy3am40eodZ3NHHYsfBxFSaJ9Et1aN_xrm15kG6X7981wOv3KjNF25Dob9HLB_ZjYgB6v7B1Lu1NBDFaukepZRItriYJH8EqHc3CTOi97Vdud2Vpmw75lQ9TuYupwNZ098kN0Ty7KZC9blDKgCtmyOqzLU-AuAoEbmgK5aGUIrUaDZt6s9V_TBRh1UnFOlJkjWYZOc08I-QZdc54u9NyPDFSZvlT1l9SD6UydB62pLNTuh5GwlB4EOvV3wdP8x-4Dzr_7dzY8j3euxJOz3VFVE1vt4-6mUl0oY=w272-h448-no)


![](https://ws4.sinaimg.cn/large/006tNc79gy1fhxct12udnj311x0s3grw.jpg)

## 正文

我最近的项目中，退出登录后（跳转到登录页），发现首页控制器没有被销毁，依旧能接收通知。

退出登录代码：

```objc
UIStoryboard *storyboard = [UIStoryboard storyboardWithName:@"Login" bundle:[NSBundle mainBundle]];
AppDelegate *appDelegate = (AppDelegate *)[UIApplication sharedApplication].delegate;
appDelegate.window.rootViewController = [storyboard instantiateViewControllerWithIdentifier:@"LoginVC"];
```

很明显发生了循环引用导致的内测泄漏。

接下来就使用 **Debug Memory Graph** 来查看内测泄漏了。

### 运行程序

首先启动 Xcode 运行程序。

### Debug Memory Graph

![](https://ws3.sinaimg.cn/large/006tNc79gy1fhxend1a8aj315y0s3gw5.jpg)

点击 Debug Memory Graph 按钮后，可以看到红框内的是当前内存中存在的对象。其中，绿色的就是视图控制器。

这样，我们随时都可以查看内测中存在的对象，换句话说，就是可以通过观察 Memory Graph 查看内测泄漏。

### 调试你的App

继续运行你的程序

![](https://ws2.sinaimg.cn/large/006tNc79gy1fhxeuh1np5j30v90kvn03.jpg)

然后对App进行调试、push、pop 操作，再次点击 Debug Memory Graph 按钮。那些该释放而依旧在内测中的 `控制器` 或 `对象` 就能一一找出来了。

接下来，只要进入对应的控制器找到内测泄漏的代码就OK了，一般是Block里引用了 `self`，改为 `weakSelf` 就解决了。

```objc
#define WS(weakSelf) __weak __typeof(&*self)weakSelf = self;

WS(weakSelf)
sView.btnBlock = ^(NSInteger idx){
    [weakSelf.tableView reloadSections:[NSIndexSet indexSetWithIndex:idx] withRowAnimation:UITableViewRowAnimationAutomatic];
};
```

## 结语

就这样，利用 Debug Memory Graph，可以简单快速的检测内测泄漏。

一般由两个对象循环引用的内测泄漏是比较好发现的，如果是由三个及其三个以上的对象形成的大的循环引用，就会比较难排查了。
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA1OTQ0MzkyMywzODc4MzgxODEsLTEyMD
U2ODk5MTQsLTMzMTk2NTQ0OF19
-->