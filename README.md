# postman-Test
这里存的是我用postman练习的数据

2025-10-19
<img width="1117" height="759" alt="截屏2025-10-19 13 37 51" src="https://github.com/user-attachments/assets/6b3d663f-6f62-4f82-a913-99a087c6fc45" />
<img width="1117" height="759" alt="截屏2025-10-19 13 37 37" src="https://github.com/user-attachments/assets/2f29fd89-75e3-49e0-9010-7416766f389b" />
<img width="1117" height="598" alt="截屏2025-10-19 13 36 06" src="https://github.com/user-attachments/assets/fa2267d0-d513-41ba-982b-bdab96d1a4bb" />
<img width="432" height="598" alt="截屏2025-10-19 13 35 46" src="https://github.com/user-attachments/assets/67154228-7d86-4d98-ac44-754dae765f90" />
<img width="967" height="808" alt="截屏2025-10-19 13 30 25" src="https://github.com/user-attachments/assets/94f59a40-af1a-4d49-8306-259888e09f0e" />
这些基础还算顺利，只遇到了几个小问题
第一个：test功能没有找到，我以为是我下载有问题，但是我在官网下载的，怎么会，我在页面点了每一个可能的按钮，发现了这11版里，官方把test功能变成了scripts里的post-response。
第二个：在authtest里，https://reqres.in/api/users?page=2，当时一直报错missing api key，这个网站是正规可以直接访问的，没有设置no auth？不是。不是no enviroment？也不是，我问了ai，ai分析可能是现在reqres.in 现在需要 API 密钥才能使用其 API，官网拿了免费api密码就行了。解决问题的办法确实有很多种，就看想不想解决。
第三个：在run user那个文件时，报错了一个
  GET https://reqres.in/api/users/968
  404
  209 ms
  The request was sent using HTTP/1.x since requests with proxy are not supported over HTTP/2.0
  我尝试把之前犯的错的地方都检查，没有问题，我问ai，AI说它只是按照 API 规范，假装创建成功了，并返回一个看起来像那么回事的响应，是reqres.in的特性导致实验没有通过。
这是我印象比较深的小问题，总体还算顺利，目前来说，简单的使用没有问题。
