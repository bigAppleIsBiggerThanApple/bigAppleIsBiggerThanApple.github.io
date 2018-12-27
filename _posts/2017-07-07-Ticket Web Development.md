---
layout:     post
title:      Ticket Web Development (Recommendation)
subtitle:   Improved personalized business recommendation based on search history and favorite records
date:       2018-01-07
author:     Xing Wan
header-img: img/post-bg-debug.png
catalog: true
tags:
    - Recommendation System
---
# What can this application do? 
**（1）Search near by events**:

When user login, it will send geolocation to our server, convert the geographic location into a key according to the api of our server, then send the request to TicketMaster to get the events and return to user. Below is what events looks like :)
![](https://lh3.googleusercontent.com/LKx_tHZupWoWw3tX0sEYQOsgUX5MJjijuMivfpX2s7xEMrN4NUToA6IlLUlrUKFCST8cH0jygpy6WcKSica_wRWLMVPunD_u097YgZoFWNZ_nVCDDrV3XfDqh-xkpRvAZUsSBQoKIUTGpwbjE_gW9EFSt6397AwQ4iY0c7s1MR3ryU8anXydUo15YYCkJ8417erfo4q9yRHM0EMSxc78cInluPpastZ7c6WVAo8reEYS1nU9y9-mXgd0D4KxNylxoPt7aSd5uUWIGtj8t9kWi18Y_cFLIc9jU27vgMUffkZFntw6MThVFWYC49anGfO2dlffr_TnFstXNjgk1Q6JQoMmPng-9G35OOp_RLcCJO6GPCnilGbEcVfMRoyktC3fhXzfM08kzNxFd_8dJ4oft167TzR7hoqFaeVt3NvZm06e8fSekHDYDB_fbMp3UPLCiOd1NHCKvhsduBWF9oShi0GZDo5r6sbLC4Ne7grRcs3BrJsfvNRooCpgUaXqgIApyittiP8RwF3aYBoTAGztUGjkX4gJsDpjScP0hMAa25G14fKktjPpMVJZVQT4549XRm9JZHAIuPqlEECuLsTUELdswzz3RKmkBjZVc59h90T6xMK1hd7Wv_v93UxfD3Dvg0hPtMrPHItHndPxMCrwuRpB=w1437-h676-no)

**（2）Favorite events**:

There is a heart icon on the right side of each event, users can save their favorite event simply click on that icon. Under this tab, user could check all the events saved before.
![](https://lh3.googleusercontent.com/ijLnP4nzAGpIs6M5NjV1VPhZD0murVUA3GOZpL7UJkb6KC9vCFCQSEMHGM_uNODFpY99cyPA-7c2eLsgo8IayQLqUrBGYsZYpTEHhoHQN7uEQP4WkyppmNlpUTbZLQNElPV7UN3KRO3YEX2GYZ_6uH_Rt7bWds8deXB1hfXT2840tvO1SIdOmYIu_gq_rqE-CRX2juNlZ-BXacguquUd977cx76xccReGPsen7wC18U0qzE6lTGPwlUFz2o7xIKeXclm914CcybGtq9imtBBTqcHZwuhwaTvk-KTcJKBhd0dAv16OT_DI2OhR2VWJ4U-4qKpuRL6oKZwlNnKSB92wnEmUEj7R9PxCmoIHs6UVO1txZRqFfbI7NnN6FvaX6VH0NPm1Sx2slWo4LfrZ8yKKOWnaEqJ-Iz9FbhSXSJ2nO3-V_lno42BOFoHepgaoTpMn_lcEA0jFVQ4CSCfp_XCMDMVWdqHQlu_DuyZKtJ1cytrQlHpma_Y9OPAerLQk2kV9dg5wGqH2QNsDEpbU131WnhCjsnoY-eDpujxEvdDy9I1mWGzyHvvwySGs_qnII2oJaQTMNHucImXZ73DKpvm72gHfqcUodlhsFgmrxya9aauyjnAm5fK_5gfCWkEIEiOGgZZPyjorm7IBWISTi7GvAjB=w1435-h694-no)

**（3）Recommendation tab**:

Our recommendation system is based on the type of events the user likes, and then recommend the corresponding events according to the recommended algorithm we designed. 
![](https://lh3.googleusercontent.com/jgM7-5-vpkbCGU6OKWIePOI4SC54qBWUhKvLAmConwJL8uleE5QxBDt5o669F3ePWL4K8htnrgVnK9GoL0BfZHr30TE0Ww5ygxOAtOGT49sASaZtN2CPvGyoXlx7QudQMB7o1YFvVjJouUY2Cj_XoaEsn5QWrSO7gIcOcDrjBIzguucAJ4AX4P0gfhKjKyaGSojgs_P7ZtXJ2QknYhzVdXlOYqr5mLn2bSbJhVPOiw6wEl7Zkhb0hP6cuI9m8bTcsm5L1AxsXBLPBwRYvI2WCHQ4vZB_2dGAAAf7ZUq1aSi04NNd2njh_32_wIGI8vYYHUNvQmTXbBZ_06cv9kVebAHOyU3jmr4UjBRo3RNoOFkE6kUjb-BLfGgDKkguZWEsvICGOQSX7AjI7YPLOuZ2AW-SHtRXSPqQMVwyIYuQhAiPNbNnIPCVrqrt2m3XzJ1pGgcEPoaO41TK4O5hTghI6oSBKuM48UmKrV7ViQA5xt8J_B0qVr8CoskZldAFHLH6Gx9jlYxtoWt8QyJZw9bHSTPSgXJ9tzFGwUVYjk4vTAQ9ioVnO7_ek3eQ4j_aQ5e1_cdGHj60QHTvq9ON1gktuAkriwprxe1x0mUEiQ1QIpLERjuW1jY4tMrBk9_kbqq1jGh8nMoTmB4hwTncEcB7jhq1=w1437-h695-no)

# App Implementation
**Backend**:
（1）Create Java servlets with **RESTful** APIs to handle HTTP requests and responses

（2）Build relational and **NoSQL** (MySQL, MongoDB) database to capture real business data from TicketMaster API

（3）Designed algorithms (e.g., **content-based** recommendation) to implement business recommendation

（4）Deployed server side to **Amazon EC2** to handle 150 queries per second tested by **Apache** **JMeter**

**Frontend**:
Designed an interactive web page utilizing **AJAX** technology (**HTML, CSS and JavaScript**)

**For details, please refer to** [github](https://github.com/bigAppleIsBiggerThanApple/ticketWebApp)

**Thanks!**
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjc5NDM0MDYwXX0=
-->