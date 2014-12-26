OurTimes：基于位置的通讯录
---------------------------------------
[体验地址http://vczero.github.io/tuban/main.html#/](http://vczero.github.io/tuban/main.html#/)

+ 通讯录功能
+ 微博功能    
+ 分享功能  
+ 位置功能       

####一、技术方案
**N**ode.js + **A**ngularJS + **M**ongoDB
####二、项目
+ client-web：OurTimes主站
+ client-admin：后台管理系统
+ client-webkit:node-webkit打包后台    
   
####三、说明
时间匆忙，主要是为了练习angular.js,所以有很多地方比较粗糙，同时也没有使用jquery类库。秉着“小步快跑，不断迭代”的策略，后续针对特定功能使用最佳实现方式，比如后台的文章管理，采用richEdit等等。至于Node.js实现服务，我个人觉得服务功能单一化更好，这样，node.js服务的维护较为便利。后期，会根据业务的复杂程度，采用async等库进行优化。     
    
####四、部署
1. pc端：client-web文件夹，修改相关配置，部署静态文件服务器即可
2. 后台：client-admin:简易的后台管理系统。 
     
####五、项目截图
**1**. 首页：发表微博、点赞、评论、欣赏文章
![首页](pics/weibo.png)


**2**. 通讯录:你会看到其他用户地图分布、修改个人信息、地图搜索
![通讯录](pics/contacts.png)


**3**. 个人中心：删除以前微博、修改密码
![个人中心](pics/uc.png)


**4**. 文章欣赏：根据首页导过来的链接欣赏美文
![文章欣赏](pics/article.png)




